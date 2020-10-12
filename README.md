An example of how to use <a href="https://github.com/fastai/fastai">fastai</a> to classify newspaper pages.

The combination worked considerably better for various classification tasks on the Berliner Börsen-Zeitung
than using a default resnet18:

* xresnet18
* mixed precision training
* <a href="https://github.com/lessw2020/Ranger-Deep-Learning-Optimizer">lessw2020's implementation of Ranger</a> 
* downscaling to 448 pixels
