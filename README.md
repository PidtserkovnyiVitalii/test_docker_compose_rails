1. Create .env file with this info:
POSTGRES_USER=postgres
POSTGRES_PASSWORD=password
POSTGRES_HOST=db
SECRET_KEY_BASE=secret
2. Run docker conrainers with:
docker-compose up -d
3. in Docker container start rails server with:
bundle exec rails s -b 0.0.0.0