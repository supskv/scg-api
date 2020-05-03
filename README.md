# api

> A Express.js project

## API Setup

Default endpoint: http://localhost:4000. You can change it in .env file on PORT variable. Then run again.
And you must add other variable below

```bash
# optional
PORT=8000

# required (can see all my token in mail)
# Use for line bot webhook
LINE_CHANNEL_ACCESS_TOKEN=

# Use for getting notification from line bot
LINE_ME_USERID=

# Use for Google maps API Directions
GOOGLE_MAPS_API_KEY=
```

## Build Setup

```bash
# install dependencies
npm install

# serve
node src/app.js
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
