# AI_Security

### This is an AI based project which specifically on `Computer Vision` domain.

### _This Repository contains program which detects faces from its database and keeps record in "output_data" folder._

> Moudules reuired:
 
    -opencv-contrib-python
    -os*
 
 *os module isn't required to install
 
<br/> 
 
Just download the `Downloads.zip` file or `git clone https://github.com/InvisiblePro/AI_Security.git` and install all requirements from `requirements.txt` using `pip install -r requirements.txt` and get your model ready!..
<br/>

### Steps to follow:-

1. First install all pre-requirements using these command-- `pip install -r requirements.txt`.

2. After installing all modules, first run `data_collector.py` which ask `Face ID:` you can set it as 0,1,2,3.... then a pop-up window opens and starts capturing your face pictures.

3. Now run `modelTrainer.py` file to train your model.

4. Now get into the code of `face_recognition.py`, search for  
```python
names=['person1','person2'] # give these names as same array index as of Face ID:
```

5. Now, just run this file, you will see your face getting detected on screen.

6. After closing window by pressing `escape` key, you will get `output_data` folder in which you will find a recording of camera and 2 log files.

7. Great if you haven''t got errors.....    You are done 👍🏻👍🏻

<br/>
<hr>

[<img src="https://img.shields.io/badge/GitHub-InvisiblePro-blue?logo=github&style=for-the-badge" alt="InvisiblePro">](https://github.com/InvisiblePro)
