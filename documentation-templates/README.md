

# PGE RISK API SERVER
Deployment Guide

### Description

## Prerequisites
1. Node 4.x
2. NPM



## Local Deployment
1. Install the application: `npm install`
2. Configure config.json for server to db connection
3. Configure config_seed.json for database population/creation
4. Configure config_api.json for api key ONLY CHANGE THE VALUE PLEASE
5. Create Database 
`node create.js` (for populated database) /
`node create-empty.js` (only business and industrial are populated)
`node create-empty-all.js` (for empty database )
6. Start the server: `npm start`
7. Use postman extension/app to test the api. postman file is name postman-collection

