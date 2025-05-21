# n8n + evolution API

## Manage Services

### Start services
```
docker-compose up -d
```

### Stop services
```
docker-compose stop
```

### Destroy Services and data
```
docker compose down -v
```


## n8n
URL: http://localhost:5678/

To install the evolution API plugin
* Go to "Setting" from the bottom left (in the three dots of the user)
* Go to "Community Node"
* "Install community nodes" put n8n-nodes-evolution-api



## Evolution API
URL http://localhost:8080/manager/

API KEY: 429683C4C977415CAAFCCE10F7D59999



## Configure n8n integration with evolution API

### Configure webhook evolution in n8n
Watch from 2:05 to 6:25
https://www.youtube.com/watch?v=CTSNMmCVpy4

n8n internal URL: http://n8n:5678/webhook......

### Configure evolution API in n8n to send messages
https://www.youtube.com/watch?v=7Nhx6hOXqgk
See from 4:48 

evolution_API internal URL: http://evolution_api:8080

API KEY: 429683C4C977415CAAFCCE10F7D59999

