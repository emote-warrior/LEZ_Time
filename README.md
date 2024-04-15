# LEZ_time

This repository contains the Python script `lez_time.py` that fetches traffic data for specified locations using the Google Maps API and logs this data to an Excel file. The data fetching is automated using GitHub Actions, which triggers the script every 30 minutes starting from 12 AM IST on the specified start date.

## Description

The `lez_time.py` script uses the Google Maps Directions API to fetch duration in traffic between specified pairs of locations. The results are saved in an Excel file with the timestamp of execution as the filename. This process is automated with GitHub Actions to run the script every 30 minutes.
