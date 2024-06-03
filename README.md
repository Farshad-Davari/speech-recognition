<h1 align="center">Project Name: Speech Recognition</h1>
<hr>
<h2 align="center">Project Details: A complete speech recognition in python and tensorflow</h2>  
<hr>

Prerequisites:
```
1-Install vscode
2-Install python
3-Install git
4-Install jupyter notebook extension on vscode
```
<hr>

Step 1: <br>
Install these packages: <br>
Tensorflow, numpy, seaborn, Ipython, matplotlib, sklearn <br>
run this command:
```
import sys
!{sys.executable} -m pip install -r requirements.txt
```
<br>

Step 2: <br>
Download the mini dataset: <br>
run this code:
```
data = tf.keras.utils.get_file( 
  'mini_speech_commands.zip', 
  origin="http://storage.googleapis.com/download.tensorflow.org/data/mini_speech_commands.zip", 
  extract=True, 
  cache_dir='.', cache_subdir='data')
os.listdir('./data/')  
```
<br>

<h4>Important: </h4>

> Due to the large size of the dataset, it was not possible to upload it to GitHub.

