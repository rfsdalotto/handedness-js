# handedness.js

```
<script src="handedness.js"></script>
<script>
    var h = new Handedness(function (newH) {
        var body = document.getElementsByTagName('body')[0];
        body.classList.remove(newH.last_handedness);
        body.classList.add(newH.classification.handedness);
    });
</script>
```
