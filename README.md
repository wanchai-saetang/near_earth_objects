# Explore Close Approaches of Near-Earth Objects

CLI to search for and explore close approaches of near-Earth objects (NEOs), using data from NASA/JPL's Center for Near Earth Object Studies.

## Description

A command-line tool to inspect and query a dataset of NEOs and their close approaches to Earth.

Read data from both a CSV file and a JSON file, convert that data into structured Python objects, perform filtering operations on the data, limit the size of the result set, and write the results to a file in a structured format, such as CSV or JSON.

you'll be able to inspect the properties of the near-Earth objects in the data set and query the data set of close approaches to Earth using any combination of the following filters:

- Occurs on a given date.
- Occurs on or after a given start date.
- Occurs on or before a given end date.
- Approaches Earth at a distance of at least (or at most) X astronomical units.
- Approaches Earth at a relative velocity of at least (or at most) Y kilometers per second.
- Has a diameter that is at least as large as (or at least as small as) Z kilometers.
- Is marked by NASA as potentially hazardous (or not).

## Getting Started

### Dependencies

This project requires Python 3.6+. To see the version of your environment's Python 3, run `python3 -V` at the command line. You should see: `Python 3.X.Y` where X >= 6.

Fortunately, this project has no dependencies external to the Python standard library, so there's no need for virtual environments.

All of the examples use the `python3` executable. Only if your environment's `python -V` is also Python 3.6+ can you use `python` instead of `python3`.

### Installing

clone the project to your local machine with `git clone`

### Executing program

python3 -m unittest --verbose
