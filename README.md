
# group-detection

group-detection-tensorflow-0.9.0

## 1. Requirements
* Python 2.7
* TensorFlow 0.9.0

## 2. Installation
### 2.1. Install pip if it is not already installed:
```bash
$ sudo apt-get install python-pip python-dev -y
```

### 2.2. Then, select the correct binary to install:
#### 2.2.1 Linux - CPU
```bash
# Ubuntu/Linux 64-bit, CPU only, Python 2.7
$ export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.9.0-cp27-none-linux_x86_64.whl
```

#### 2.2.2 Linux - GPU
```bash
# Ubuntu/Linux 64-bit, GPU enabled, Python 2.7 
# Requires CUDA toolkit 7.5 and CuDNN v4.
$ export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/linux/gpu/tensorflow-0.9.0-cp27-none-linux_x86_64.whl
```

### 2.3. Install TensorFlow:
```bash
# Python 2
$ pip install --upgrade pip
$ sudo pip install --upgrade $TF_BINARY_URL
```

### 2.4. You can now test your installation. Open a terminal and type the following:
```bash
$ python
>>> import tensorflow as tf
>>> tf.__version__
'0.9.0'
>>> 
>>> hello = tf.constant("Hello, TensorFlow!")
>>> sess = tf.Session()
>>> print(sess.run(hello))
Hello, TensorFlow!
>>> 
```


### to be continued ...

