# Konok

Konok helps Android developers test location-based apps without traveling the route themselves. A tester can select a fixed point or simulate a trip between two addresses, adjust the speed, and pause or resume along the way.

[Google Play](https://play.google.com/store/apps/details?id=app.konok) · [Product website](https://konokapp.com/)

## Inside the app

- The native Android app is written in Java. MapLibre renders the map, and the route planner uses OpenStreetMap road data.
- Testers can enter coordinates directly, search for an address, or reuse a favorite saved on the device. The route preview shows distance and estimated travel time at the chosen speed.
- Google Play Billing handles monthly and annual subscriptions for simulation. The interface supports English, Russian, and Spanish, plus a choice of miles or kilometers.

## Route preview

This 2.04 km example in downtown Chicago shows both endpoints, the estimated trip time, and the control that starts the simulation.

<img src="screenshots/route.png" alt="Konok on Android with a Chicago route, two numbered stops, and an estimated five-minute trip" width="320">
