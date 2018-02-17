# Hack-HW Deep Learning Workshop
## Getting Started
  * If on a Mac, open a terminal
  * Download the following repository: `git clone https://github.com/mihail911/deep-hwack`
  * Go into the repository: `cd deep-hwack`
  * Install Jupyter:
     ```
     python3 -m pip install --upgrade pip
     python3 -m pip install jupyter
     ```
    Or
     ```
     python -m pip install --upgrade pip
     python -m pip install jupyter
     ```
  * Install Tensorflow: `pip install tensorflow`
  * Once installed run the following short program within a Python interactive shell to see that everything works:
    ```
    import tensorflow as tf
    hello = tf.constant('Hello, TensorFlow!')
    sess = tf.Session()
    print(sess.run(hello))
    ```
  * Now install Keras: `pip install keras`
