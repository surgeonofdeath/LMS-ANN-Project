# LMS-ANN-Project
Project done under Dr. Sainath Bitragunta.

The aim of this project is to compare the performance of Least-Mean-Squares Algorithm and Artificial Neural Networks for the purposes of Active Noise Cancellation to judge which performs better and is less computationally complex.

The hardware imlementation of the same can be found in this [repository](https://github.com/Aakriti05/DSP-implementation_LMS_RNN).

The python packages required to run this code are as follows:
1. `Tensorflow` - This is the machine learning framework on which the architectures are built.
2. `Keras` - Wrapper package for rapid prototyping.
3. `Matplotlib` - For visualizing the Normalized Mean Square Error.
4. `Soundfile` - For reading the most common audio format files.
5. `Sounddevice` - For audio recording and playback through code.

Run the command `python3 call_lms.py` or `python3 call_RNN.py` to run the Least-Means-Squares or Recurrent-Neural-Network filter respectively.

Authors -

Rohitkumar Arasanipalai - f2015666p@alumni.bits-pilani.ac.in

Aakriti Agrawal - f2015276p@alumni.bits-pilani.ac.in
