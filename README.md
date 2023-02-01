This Project
------------

### ← index.html

We simply have a script tag in our HTML to grab the latest version of TensorFlow.js

In this case we simply reference the following:

```HTML
<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs/dist/tf.min.js" type="text/javascript"></script>
```

However, if you want to pull in a particular version of TensorFlow.js you can do so like this:

```HTML
<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@1.4.0/dist/tf.min.js" type="text/javascript"></script>
```

Optionally, if you want to include our TF.js visualization library you can do so using this import:

```HTML
<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs-vis/dist/tfjs-vis.umd.min.js" type="text/javascript"></script>
```
However feel free to remove if you are not using this for visualizing training etc. [More details here](https://github.com/tensorflow/tfjs/tree/master/tfjs-vis).

### ← style.css

Nothing to see here. Just styles to make it look prettier. You can use or ignore these as you please.

### ← script.js

this is where the model is loded and put into operation with some lines of code to show the objects shapes
-------------------
