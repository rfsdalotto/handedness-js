# handedness.js

JS library with 0 dependencies to predict user handedness (or at least try) using touch events.

### [Mobile Demo](https://rfsdalotto.github.io/hand.html)
<img src="https://raw.githubusercontent.com/rfsdalotto/handedness-js/master/ss.png" width="200"></img>

```
new Handedness(function (newH) {
    var body = document.getElementsByTagName('body')[0];
    
    body.classList.remove(newH.last_handedness); // remove last handedness class
    body.classList.add(newH.classification.handedness);  // add actual handedness class
});
```
