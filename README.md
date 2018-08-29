# handedness.js

Experimental JS library with 0 dependencies to predict user handedness (or at least try) using touch events.

- [Use case demo](https://roquef.github.io/handedness/)
- [Use case demo invision](https://invis.io/E8N5FXJ7JDK)

```
new Handedness((h) => {
    console.log(h.last_handedness); // last classification
    console.log(h.classification.handedness); // actual classification
});
```
