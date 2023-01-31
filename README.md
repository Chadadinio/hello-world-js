Minimal Node.js Hello World example
This repo contains a minimal hello world application written in Node. This repo will document the many ways you can deploy this application.

Run locally
npm install
npm start

Run in a container
docker build -t node-hello-world:latest .
docker run -it -p 8080:8080 --name node-hello-world node-hello-world:latest
