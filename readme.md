# StoryBooks

> Create public and private stories from your life

This app uses Node.js/Express/MongoDB with Google OAuth for authentication

## Usage

Add your mongoDB URI and Google OAuth credentials to the config.env file

```
# Install dependencies
npm install

# Run in development
npm run dev

# Run in production
npm start
```
## Setup
```
# Setup local Mongo DB instance in a Container
docker run -p 27017:27017 -d mongo:3.6-xenial

# Check DB status
docker ps

# Fix MongoDB connection
npm install connect-mongo@latest
```
## Docker
```
# Setup
create the following files

.dockerignore
Dockerfile
docker-compose.yml

# Build
docker  build -t storybooks-app .





