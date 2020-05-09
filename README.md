# users-full-stack
Full stack web application to manage 'user' data. Uses Angular, Micronaut, and MongoDb Atlas. This is currently set up to only run locally.

# Setup

## frontend (hornungt/users-web-interface)
1. cd into frontend/
2. run `npm install`

## backend (hornungt/BasicRestApi)
1. cd into backend/src/main/resources and configure application.yml for your mongo instance

# Run
1. cd into frontend/ and run `ng serve -o`
2. cd into backend/ and run `./gradlew run`

# Stop
1. Go to terminal window running 'ng serve -o' and press Ctrl+c
2. Open new terminal window, cd into backend/ and run `./gradlew --stop`