# Web App
Just a quick container to test.

## The architecture
This is a demo webapp written in go that uses the native golang http server then serves a basic html page that listens on port 3000.

## Building 
Build locally `docker build -t webappdemo .`

## Running 
To run the app `docker run -it --rm --name webapp -p 3000:3000 webappdemo    `
