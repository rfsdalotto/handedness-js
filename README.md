# handedness.js

(WIP) Experimental library to predict mobile user handedness (or at least try) using touch events and sensors.

- [Use case demo - swipe](https://roquef.github.io/handedness/)
- [Use case demo - swipe - invision](https://invis.io/E8N5FXJ7JDK)

```
        var h = new Handedness({
            listener: (newH) => {
                console.log(newH);
                var body = document.getElementsByTagName('body')[0];
                body.classList.remove(newH.last_handedness);
                body.classList.add(newH.classification.handedness);
            }
        });
```
