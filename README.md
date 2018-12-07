
```
 wget --quiet \
  --method POST \
  --header 'Authorization: <your eCX API token key goes here>' \
  --header 'Content-Type: application/json' \
  --body-data '{"url": "http://schoolbusinessalert.space/sd/","brand": "University of South Wales","date_discovered": 1539429978,"confidence_level": 100}' \
  --output-document \
  - https://api.ecrimex.net/phish
 ```
