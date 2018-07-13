# Open Sky CronJob Microservice

This application will execute and shutdown.  It's sole purpose is to communicate with the [Open Sky](https://opensky-network.org/apidoc/) flight data service, make the necessary data transforms, then publish to a message queue to trigger any additional work that any other services need to perform based on updated data this service produces.