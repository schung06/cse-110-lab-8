# Lab8-Starter

## How are graceful degradation and service workers related?
Graceful degradation ensures a web app is still functionally accessible despite the user's browser not supporting some features. Service workers are a way to implement graceful degradation by making the web app default to cached content when there's no network connection, so the user can still access the app's functionality even if they're offline.