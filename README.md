# handedness.js

Experimental JS library with 0 dependencies to predict user handedness (or at least try) using touch events.

### [Mobile Demo](https://roquef.github.io/handedness/)
### [Demo Invision](https://invis.io/E8N5FXJ7JDK)

```
new Handedness(function (newH) {
    var body = document.getElementsByTagName('body')[0];
    
    body.classList.remove(newH.last_handedness); // remove last handedness class
    body.classList.add(newH.classification.handedness);  // add actual handedness class
});
```
