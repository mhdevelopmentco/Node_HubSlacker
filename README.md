HubSpot Lead Notifications for Slack
=====================================

Receive lead notifications from HubSpot form submissions direct to a Slack Channel or a designated user.  Customize the information you receive in the notifications using the app.
  
Project Period
----------------------
- Start: 2015.8.23
- End: 2015.10.21

## Environment
- Server: Heroku
- DB: MongoDB
- Programming Language: Node(Express, EJS, Mongoose)
- CSS Framewokr: [Skeleton](http://getskeleton.com/)

## Project History
- Full Site Build with Laravel
- Plugins Integration: Marker Cluster, Glyph Icons, Bootstrap
- Controller: Map, Reminders, Dashboard, Vineyard, Wine, User, Settings

### Middleware
- body-parser - https://www.npmjs.com/package/body-parser
- cookie-parser - https://www.npmjs.com/package/cookie-parser
- express-session - https://github.com/expressjs/session
- connect-mongo - https://www.npmjs.com/package/connect-mongo (session logger)
- csurf - https://www.npmjs.com/package/csurf
- uuid - https://github.com/broofa/node-uuid
- dot-env - https://www.npmjs.com/package/dotenv
- passport-local-mongoose - https://github.com/saintedlama/passport-local-mongoose

### SLACK APIS
  - Oauth - https://api.slack.com/docs/oauth
    - token request - https://api.slack.com/methods/oauth.access
    - Scoping - https://api.slack.com/docs/oauth-scopes
    - test connection code - https://api.slack.com/methods/api.test
    - test authToken - https://api.slack.com/methods/auth.test
  - Real Time Messaging API - https://api.slack.com/rtm
  - Bot user - https://api.slack.com/bot-users
  - Post message - https://api.slack.com/methods/chat.postMessage
  - List channels - https://api.slack.com/methods/channels.list
