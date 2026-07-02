# IP Geolocation Reporter (Python)

A Python script that fetches IP geolocation data from an API and sends a structured report to a specified endpoint.

---

## Overview

This project uses an external API to collect information about an IP address and sends the data as a JSON report.

You use this to learn:

- API requests  
- JSON handling  
- Data extraction  
- Sending data to endpoints  

---

## Features

- Fetch IP data using a geolocation API  
- Extract useful fields (country, city, ISP, coordinates)  
- Format data into JSON  
- Send report to a custom endpoint  

---

## How It Works

- The script sends a request to the IP geolocation API  
- API returns data in JSON format  
- The script extracts key fields:
  - IP address  
  - Country  
  - City  
  - ISP (provider)  
  - Latitude and longitude  
  - Proxy status  
- Data is formatted into a JSON report  
- Report is sent to a defined endpoint using a POST request  

---

## Usage

### 1. Set your API key and endpoint

```python
API_TOKEN = "your_api_key"
ENDPOINT = "your_endpoint_url"
