# TODO
1. Make batch processing job start automatically
1. Implement all required batch precomputations
1. Implement all endpoints in fastapi-app

# Docs

## Configuration

Configure currencies you want to track in [`websocket-client/config.json`](./websocket-client/config.json) file:
```json
{
    "currencies": ["XBTUSD", "ETHUSD", "LTCUSD"]
}
```

## Deployment
`1`
**Launch the application**
```bash
docker-compose up --build -d
```


## Debug
`1`
**Launch admin console**
```bash
./admin-tools/start.sh
```
