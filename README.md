# google-aerial
Get aerial views of a specific home address.

<img width="320" height="190" alt="google-aerial" src="https://github.com/user-attachments/assets/55130bca-b34a-4868-ae9c-8d361d17836f" />

### Google Aerial View API
- [API overview](https://mapsplatform.google.com/maps-products/aerial-view/)
- [API docs](https://developers.google.com/maps/documentation/aerial-view/overview)
  
```
curl -X POST -d '{
  "address": "{ $STREET_ADDRESS}"
}' \
-H 'Content-Type: application/json' \
"https://aerialview.googleapis.com/v1/videos:renderVideo?key={$API_KEY}"
```

```
curl -X GET "https://aerialview.googleapis.com/v1/videos:lookupVideo?key={$API_KEY}&videoId={$VIDEO_ID_FROM_POST}"
```
  
