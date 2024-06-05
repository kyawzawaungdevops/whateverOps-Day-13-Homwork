# Docker Compose Setup for MongoDB, Redis, and Node.js App

This repository contains a Docker Compose setup for running a MongoDB, Redis, and a Node.js application. The `docker-compose.yml` file defines the services and the network required for the setup.

I updated line 29 of index.mjs like following:

```javascript
const client = redis.createClient({url: `redis://${redisHost}:${redisPort}`});
```
## Screenshots

![image](https://github.com/kyawzawaungdevops/whateverOps-Day-13-Homwork/assets/80774788/5ed5ce59-bf85-41b8-8842-1a0e91350b50)

![image](https://github.com/kyawzawaungdevops/whateverOps-Day-13-Homwork/assets/80774788/ead21f1f-29c7-41d7-b4c5-26d60b376370)
