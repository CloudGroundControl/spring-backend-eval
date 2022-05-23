# spring-backend-eval

This exercise will help us evaluate your knowledge of Spring framework and your ability to tackle a problem independently.

## Exercice

[Flighradar24](https://www.flightradar24.com) is an internet-based service that shows real-time aircraft flight tracking information on a map. It includes flight tracking information, origins and destinations, flight numbers, aircraft types, positions, altitudes, headings and speeds. They also provide a live data REST endpoint.

As a user, I would like to subscribe to a WebSocket endpoint using a `position` (coordinates) and a `radius` (in meters) to get access to a 1Hz stream of flying planes details and position in the area defined by the position and radius. The websocket connection should only stream new information.

You can access Flightradar24 live data using the following endpoint: `https://data-live.flightradar24.com/zones/fcgi/feed.js?bounds=...`. See FlightRadar24 API documentation for further details (provided separately).

## Technology to use

- Java and Spring Framework
- The output of the websocket stream should be in `JSON`
- Docker

## Deliverable

To be successful in this exercise, your submission should:
- be a github repository
- explain how to run your service as a docker container
