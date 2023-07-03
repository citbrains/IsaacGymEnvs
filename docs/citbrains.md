## CIT Brains

### Environment  
OS: Ubuntu18.04, 20.04  
Python3.8  

### Install
  
- Download the following
IsaacGym_Preview_4_Package.tar.gz

- Unzip and copy to your home directory

- Change to the python folder and type
```
pip install -e .
```

- Clone this repository
```
git clone https://github.com/citbrains/IsaacGymEnvs
```

- Go to your IssacGymEnvs folder and type
```
pip install -e .
```

- In the Issacgymenvs folder, type
```
python train.py
```

- To avoid errors, lower the version of numpy.
```
pip install numpy==1.23.0
```

- Install the following to save the video
```
pip install Pillow==9.5.0
```

- To use tensorboard
```
pip install tensorboard
```

### Excecute

```
Python train.py task=GankenKun capture_video=True capture_video_freq=1500 capture_video_len=300 force_render=False
```
