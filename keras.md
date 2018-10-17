## Tensorflow
```bash
sudo apt-get install -y python-pip python-dev
# check the following link if: Unable to locate package python-pip
# https://blog.csdn.net/yyinhai/article/details/53056973

wget https://github.com/WangYuchenSJTU/installTensorFlowJetsonTX/raw/master/TX2/tensorflow-1.3.0-cp27-cp27mu-linux_aarch64.whl
pip install tensorflow-1.3.0-cp27-cp27mu-linux_aarch64.whl
```

## jupyter
```bash
sudo pip install pyzmq==17.0.0
sudo pip install jupyter
```

## keras
```bash
sudo apt-get install libhdf5-dev
# check the following link if: Unable to locate package libhdf5-dev
# https://askubuntu.com/questions/148638/how-do-i-enable-the-universe-repository/148645#148645

sudo pip install h5py
sudo pip install keras
```

## Reference

https://shiroku.net/robotics/install-jupyter-notebook-on-jetson-tx2/

https://github.com/jetsonhacks/installTensorFlowJetsonTX

https://stackoverflow.com/questions/29985453/linux-error-when-installing-keras
