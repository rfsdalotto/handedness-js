# handedness.js

(WIP) Experimental library to predict mobile user handedness (or at least try) using touch events and sensors.

- [Use case demo - swipe](https://roquef.github.io/handedness/)
- [Use case demo - swipe - invision](https://invis.io/E8N5FXJ7JDK)

```
new Handedness((h) => {
    console.log(h.last_handedness); // last classification
    console.log(h.classification.handedness); // actual classification
});
```
