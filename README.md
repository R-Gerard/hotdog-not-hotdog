# hotdog-not-hotdog
Yet another convolutional neural net (CNN) for classifying images with the presence or absence of a hotdog, using TensorFlow/Keras with demonstrations using Jupyter notebooks.
- https://keras.io/
- http://jupyter.org/

# Running
The preferred method to run the notebooks is with Docker. You can launch a Docker container with Jupyter and Tensorflow pre-installed by running the following command from the root directory of this project:

```
docker run -it --rm -p 8888:8888 -v "$(pwd):/home/jovyan/work" jupyter/tensorflow-notebook:db3ee82ad08a
```

You should see this message after the container has started, followed by a URL to copy-paste into your browser:

>Copy/paste this URL into your browser when you connect for the first time, to login with a token:
