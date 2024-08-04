# Driver-Accident-Detection-System
This is the code for my undergraduate capstone project. This contains code for 3 submodules - Driver Sleep Detection, Driver Drunkeness Detection and Vehicle Collision Detection.

## Vehicle Collision Detection
### Directory Structure
```
dataset_h5<br/>
├── test_set<br/>
│   ├── .npz files<br/>
├── train<br/>
├── val<br/>
```

### Train and test the detector
```
Vehicle\ Collision\ Detection/vehicle\ collision.ipynb
```

## Driver Sleep Detection
Please refer to its own repository for more details on how to set and run this.

## Driver Drunkenness Detection
### Directory Structure
```
data<br/>
├── test<br/>
│   ├── data_folders<br/>
│   └── test.pkl<br/>
├── train<br/>
├── val<br/>
```
Dataset Preparation
```
python split_data.py
```
### Train and test the detector
```
Driver\ Drunkenness\ Detection/jupyter/drunk\ detect\ final.ipynb
```


