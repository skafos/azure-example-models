# Object Detection
<a href="https://notebooks.azure.com/Skafos/projects/object-detection-examples">    <img src="https://notebooks.azure.com/launch.svg" /></a>

Object detection is the task of locating and identifying objects within images. Here we start you off with a basic
 example:

 - **People, Bikes, and Cars**: Trains a model to detect and classify objects in images of people, bikes, and cars.
 - **Coffee, Pens, and Computers**: Trains a model to detect and classify objects in images of coffee mugs, pens and computer monitors.
 - **Couches, Chairs, Tables and Beds**: Trains a model to detect and classify objects in images of couches, chairs, tables and beds.

## Tips and "Gotchas"
-  **Azure Notebooks**: While Notebooks are in `Preview` mode (beta), some features might be buggy or not available. If you are having trouble with dependencies in your JLab environment. Try waiting a few minutes, restarting the Python 3.6 kernel, and trying again.
-  **Training Data**: In order for an object detection model to identify a particular object, it must have seen
other objects with the same label. To build an object detection model that identifies what you want, you would need
to retrain the model, using bounded and labeled images of the type you want.
-  **Model Runtime**: The out-of-the box model takes a long time to train on CPU. At this moment, Azure doesn't support GPU training on notebook instances. So if you need that, please check out some of these [Google Colab examples](https://github.com/skafos/colab-example-models).
-  **Model Size**: Try converting the CoreML model's weights to half-precision if you are worried about the size of the
resulting model. This doesn't mean you sacrifice half of your accuracy, it simply means it uses less floating points
in the weights of the model. To read more about this, check out [Apple's article](https://developer.apple.com/documentation/coreml/reducing_the_size_of_your_core_ml_app) on this topic.


## Need Help?
Didn't find something you need? Confused by something? Need more guidance?

- [**Check out our platform documentation**](https://docs.skafos.ai)

Please contact us with questions or feedback! Here are two ways:

-  [**Signup for our Slack Channel**](https://join.slack.com/t/metismachine-skafos/shared_invite/enQtNTAxMzEwOTk2NzA5LThjMmMyY2JkNTkwNDQ1YjgyYjFiY2MyMjRkMzYyM2E4MjUxNTJmYmQyODVhZWM2MjQwMjE5ZGM1Y2YwN2M5ODI)
-  [**Find us on Reddit**](https://reddit.com/r/skafos)

Also check out Turi Create's [**documentation**](https://apple.github.io/turicreate/docs/userguide/object_detection/)
 on object detection basics.
