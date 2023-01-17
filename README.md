## Webrtc Monitor dashboard

1. rename .env.dashboard into .env
2. update the environment variables as desired
3. deploy the project by running `docker compose up`
4. visit [http://localhost:3000](http://localhost:3000)


## Webrtc Monitor Jitsi-meet deployment

1. clone [docker-jitsi-meet](https://github.com/jitsi/docker-jitsi-meet) and checkout to stable-7577-2
2. copy jitsi-meet/docker-compose.yml in here and replace docker-compose.yml of that repo
3. make sure to put API_BASE_URL=http://host.docker.internal:9100 in .env and update it at desired
4. deploy the project according to README in that repo
