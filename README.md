# google-aerial

## Google Aerial View API example
[https://developers.google.com/maps/documentation/aerial-view/overview](https://developers.google.com/maps/documentation/aerial-view/overview)

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
