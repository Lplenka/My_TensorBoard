# My_TensorBoard
My experiments with TensorBoard. A tool for visualising neural networks in TensorFlow
## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Tensorflow](https://www.tensorflow.org/install/)  installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/Lplenka/My_TensorBoard/
# Go into the repository
cd My_TensorBoard
# Run the Python Script
Python3 mnist.py
# After complete execution run Tensorboard using command
tensorboard --logdir /tmp/mnist_tutorial/
# It shall show the below line
Starting TensorBoard b'47' at http://0.0.0.0:6006
# Open the browser and enter the above URL to see your neural network in action
