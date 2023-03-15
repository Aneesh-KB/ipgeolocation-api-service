# ipgeolocation-api-service

docker container run \
-d \
--network geolocation-net \
--restart always \
--name geolocation-caching-service \
-p 8080:8080 \ --port exposing

-e REDIS_PORT="6379" \ --Redis server listening port

-e REDIS_HOST="geolocation-caching" \ --Redis server name/ip

-e APP_PORT="8080" \ --Application port

-e API_KEY="44bfed87136f4b29a3e5230e7060aa22" \ --Api key to connect with ipgeolocation (use your key here)

aneeshkbawaits/ipgeolocation-caching:latest
