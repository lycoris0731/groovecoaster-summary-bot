# Groove Coaster Summary
===

## Description  
Groove Coaster Summary generates summary of last result in Groove Coaster 3.  
Also GC-Summary listening in HTTPS.  
If accessed to the server, it returns response with summary plain text.  

## Equipments
- Heroku (or any PaaS, servers)
- Redis

## Installation
``` go
$ go get github.com/lycoris0731/gc-summary-server
```

## Usage
You need to set environment variables.  
``` sh
export NESICA_CARD_ID=""  # Your NESiCA ID
export NESICA_PASSWORD="" # Your NESiCA ID password
export PORT=""            # Port for listening
export REDIS_URL=""       # Redis server URL
```

Start server.  
``` go
$ ./gc-summary-server
```

## License
Please see LICENSE.
