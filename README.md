----
# Setup
----

`cd ~/project`

## Install dependencies

`npm install`

`bower install`

----
# Running the server
----

`cd ~/project`

`node node_modules/http-server/bin/http-server`

----
# Project structure
----

```
.
├── README.md
├── app
│   ├── app.module.js
│   ├── app.routes.js
│   ├── assets
│   ├── components
│   └── shared
├── bower.json
├── index.html
├── node_modules
│   ├── bower
│   └── http-server
└── package.json
```

----
# Testing small code snippets
----

`st ~/project/app/shared/testing/testingControllers.js`

`st ~/project/app/shared/testing/testingDirectives.js`

.. and so on for services, etc
