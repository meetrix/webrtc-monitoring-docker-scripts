## Webrtc Monitor dashboard

1. rename docker-compose-dashboard.yml into docker-compose.yml in the server
2. rename .env.dashboard into .env
3. update the environment variables as desired
4. deploy the project by running `docker compose up`


## Webrtc Monitor Jitsi-meet deployment

1. clone [docker-jitsi-meet](https://github.com/jitsi/docker-jitsi-meet) and checkout to stable-7577-2
2. copy web service content from docker-compose-jitsi-meet.yml in here and put in docker-compose.yml web service of that repo
3. make sure to put API_BASE_URL= in .env and update it at desired
4. deploy the project according to README in that repo
