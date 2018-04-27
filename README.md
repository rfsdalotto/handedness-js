# handedness.js

```
new Handedness(function (newH) {
    var body = document.getElementsByTagName('body')[0];
    
    body.classList.remove(newH.last_handedness); // remove last handedness class
    body.classList.add(newH.classification.handedness);  // add actual handedness class
});
```
