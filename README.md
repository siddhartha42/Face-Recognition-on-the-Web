# Face-Recognition-on-the-Web
Given a link, the program can extract images and identify the faces of people it has been trained on. The dataset used is very small, please feel free to contribute

## Setup
1) Install python version - `3.11.6`
2) Create virtual environment 
```
python -m venv /path/to/new/virtual/environment
```
3) Activate the python environment
  ```
  virtual_env_path/Scripts/Activate    
  ```
5) Install required packages 
```
pip install -r requirements.txt
```

## Instructions to run
* Download the [dataset](https://drive.google.com/file/d/11pa4iob0gWzg9t7UF7WdEfEyqh9ZXr6h/view?usp=drive_link) and save it in local folder
* Download the arcface_weights from this link (https://drive.google.com/file/d/1cnQF0pnWFsR-73pcGB0N59I42dlq2t1w/view?usp=sharing) and save it in the same folder. It contains the weights of the pretrained arcface model.
* Create folder for test images and save them and assign path `test_folder` variable
* Run the Jupyter NoteBook

## Refer to the project report for more details on the algorithm used

