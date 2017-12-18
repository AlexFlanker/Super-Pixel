# Super-Pixel
Tianjie Sun@Cornell University <br /> Feng Yang@CIOMP <br />
This repo is an archive of research and project about Super-Pixel <br />
This is also a worklog which can conduct whole project, here is also a link which can help to be familiar with git workflow!
http://rogerdudler.github.io/git-guide/

<br />
<br />
# Prerequisite & Tips
Tensorflow installed, the tensorflow_examples folder include two example python codes: mnist_tf.py is just to download the dataset of MNIST and try simple estimator, mnist_deep_tf.py can then run a deep learning instance which can recoginze writing image with a 99.8% accuracy score! <br />
<br />
Until now, there are some pre-installed libraries and tools have been settled down, the whole arduous trial is worthwile and I will give a summary about troubleshooting of such libraries and tools.

<br />
Workable configuration lists:<br />
Ubuntu 16.04 LTS<br />
Python3.5<br />
Pip 9.0.1<br />
NV Drivers 384<br />
CUDA 8.0<br />
cuDNN v6.0 Extremely important, since now, tensorflow hasn't supported CUDA 9.0 and cuDNN 7.0 or higher!!!<br />
Tensorflow with GPU support 1.4 version<br /> 
