# Apilot

Developer APIs for accessing real-time Amazon marketplace data.

Apilot builds infrastructure for developers who need reliable programmatic access to Amazon product and marketplace information.

Our first product, **Azone**, provides a modern REST API that enables developers to retrieve structured Amazon data in real time.

---

## Azone – Amazon Data API

Azone is designed for developers building applications that require Amazon marketplace intelligence.

The API provides structured access to:

- Product details
- Pricing and offers
- Reviews and ratings
- Seller information
- Best sellers and categories
- Deals and promotions
- Amazon Haul search
- Amazon Haul categories

All responses are returned in clean JSON and designed to integrate easily into modern backend systems.

---

## Built For

Azone is commonly used for building:

- price tracking tools  
- product research platforms  
- e-commerce analytics dashboards  
- competitor monitoring systems  
- deal discovery services  
- Amazon marketplace intelligence tools  

---

## Key Characteristics

- Real-time marketplace data  
- Developer-friendly REST API  
- Clean JSON responses  
- Designed for automation and integrations  
- Resilient backend infrastructure  
- Containerized and scalable architecture  

---

## Quick Example

You can access Azone through RapidAPI.

Example request using `curl`:

```bash
curl --request GET \
  --url 'https://azone-real-time-amazon-data-api.p.rapidapi.com/product-details?asin=B0XXXX&country=US' \
  --header 'X-RapidAPI-Key: YOUR_RAPIDAPI_KEY' \
  --header 'X-RapidAPI-Host: azone-real-time-amazon-data-api.p.rapidapi.com'



Example request using `python`:

import requests
url = "https://azone-real-time-amazon-data-api.p.rapidapi.com/product-details"
querystring = {
    "asin": "B0XXXX",
    "country": "US"
}
headers = {
    "X-RapidAPI-Key": "YOUR_RAPIDAPI_KEY",
    "X-RapidAPI-Host": "azone-real-time-amazon-data-api.p.rapidapi.com"
}
response = requests.get(url, headers=headers, params=querystring)
print(response.json())  



