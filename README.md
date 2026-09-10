# SmallscaleWeather

A small-scale AI agent that fetches live weather data for any city in the world, 
built as a focused exercise in chaining API calls into a single, simple tool.

## What this project does

- Takes a city name as input
- Geocodes it to precise latitude/longitude coordinates
- Fetches current weather conditions and local time for that location
- Returns temperature and weather state in a clean, readable format

## Why this matters

The interesting part isn't the weather data itself — it's the pipeline: turning 
an ambiguous, human-typed input (a city name) into a precise, resolvable location, 
then chaining a second API call off the result. That geocode-then-fetch pattern 
is the same shape used in a lot of real-world agent and tool-use workflows.

## Tech stack

Python 3 · Jupyter Notebook · Geocoding API · Weather API

## Running it locally

```bash
git clone https://github.com/Jericho301/SmallscaleWeather.git
cd SmallscaleWeather
jupyter notebook smallscaleweatherAI.ipynb
```

## Example

*(Add a short example here, e.g.:)*
