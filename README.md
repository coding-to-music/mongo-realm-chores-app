# mongo-realm-chores-app

# 🚀 Javascript full-stack 🚀

https://github.com/coding-to-music/mongo-realm-chores-app

https://mongo-realm-chores-app.vercel.app

From / By

## Environment variables:

```java
const { Expo } = require("expo-server-sdk");
let expo = new Expo({ accessToken: context.values.get("expoKey") });

realm-backend/realm_config.json
{
    "config_version": 20210101,
    "app_id": "mongo-realm-chores-app-qhlli",
    "name": "mongo-realm-chores-app",
    "location": "US-VA",
    "deployment_model": "GLOBAL",
    "environment": "production"
}

realm-backend/values/expoKey.json
{
    "name": "expoKey",
    "value": "expo",
    "from_secret": true
}

realm-backend/data_sources/mongodb-atlas/config.json
{
    "name": "mongodb-atlas",
    "type": "mongodb-atlas",
    "config": {
      "clusterName": "Cluster0",
      "readPreference": "primary",
      "wireProtocolEnabled": false
    }
  }

```

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/mongo-realm-chores-app.git
git push -u origin main
```

# chores-manager-app

## Setup

```bash
cp src/constants/envConfig.example.js src/constants/envConfig.js
yarn install
pod install --project-directory=ios
```

Install dev-tools
https://www.apollographql.com/docs/react/integrations/react-native/#apollo-devtools

## Start

```
yarn start
yarn ios
yarn android
```
