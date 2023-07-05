https://github.com/GaryClarke/docker-php

Run production
docker compose up -d

Run development
docker compose -f docker-compose.yml -f docker-compose.dev.yml --env-file .env.local up -d
