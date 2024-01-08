# Data Collection and Wrangling Overview

In this capstone assignment, we will work with SpaceX launch data gathered from the SpaceX REST API. Our goal is to predict whether SpaceX will attempt to land a rocket or not based on various launch parameters. The SpaceX REST API endpoints start with `api.spacexdata.com/v4/`, and we will focus on the `/launches/past` endpoint.

## Using SpaceX REST API

- We will perform a GET request to `api.spacexdata.com/v4/launches/past` using the requests library to obtain past launch data.
- The response will be in JSON format, representing a list of JSON objects, each representing a launch.
- We will use the `json_normalize` function to convert the structured JSON data into a flat table, suitable for further analysis.

## Web Scraping Falcon 9 Launch Data

- An alternative source for Falcon 9 Launch data is web scraping related Wiki pages.
- We will use the Python BeautifulSoup package to scrape HTML tables containing Falcon 9 launch records.
- Data from these tables will be parsed and converted into a Pandas data frame for visualization and analysis.

## Data Cleaning and Transformation

- We aim to transform raw data into a clean dataset for addressing specific issues:
  - Filtering out Falcon 1 launches.
  - Dealing with NULL values in the PayloadMass column by calculating the mean and replacing NULL values.
  - Leaving the LandingPad column with NULL values, representing cases where a landing pad is not used.

## Attributes for Analysis

### Attributes to Review for Data Wrangling

Flight Number, Date, Booster version, Payload mass Orbit, Launch Site, Outcome (first stage status), Flights, Grid Fins, Reused, Legs, Landing pad, Block, Reused count, Serial, Longitude, and Latitude of launch.

### Key Attributes Descriptions

- **Launch Site:** Different launch sites, including Vandenberg AFB, Space Launch Kennedy Space Center, CCAFS SLC 40.
- **Orbit:** Different orbits of the payload, e.g., LEO (Low Earth Orbit), GTO (Geosynchronous Orbit).
- **Outcome:** Indicates if the first stage successfully landed, with possible values like True ASDS (successful landing), False ASDS (unsuccessful landing), etc.
- **Grid Fins and Legs:** Affect landing, and Reused count provides information on how many times a component has been reused.

### Data Classification Variable (Y)

- We want to convert landing outcomes to classes (y), where 0 represents a failed landing, and 1 represents a successful landing.
- The variable Y will serve as the classification variable, indicating the outcome of each launch.
