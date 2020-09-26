# Monitoring-Social-distancing

#### Github usually doesn't support files larger than 25 Mb.You can have to download Yolo Weight from the official [website](https://pjreddie.com/darknet/yolo/) of YOLO.

# For CPU:

## To run this code in your terminal:
* ***Open your terminal**
* ***Change directory to where you have downloaded this code***
* ***Install python3 if you have not, if installed already then it's ok!***
* **Run**  `  python3 -m venv venv  ` ***to create a virtual environment named venv.***
* **Run**   `  source venv/bin/activate  ` 
***to activate your environment!***
* **Write**   `  pip install -r requirements.txt  ` 
***to install the python dependencies related to this project like opencv,numpy,scipy etc.***
* **Run the command** `time python social_distance_detector.py --input pedestrians.mp4 --output output.avi --display 1
` ***to run your social distance detection project***

#### After you run the last line of command,a window will pop up and after execution of the file a `output.avi` file will be showing up in your directory like this:
![Output avi file](https://github.com/kanishksh4rma/Monitoring-Social-Distancing--Using-Machine-Learning/blob/master/output_file.avi)

# For GPU:
You can run the same code at your local machine if you have a GPU or  in Google Collab (just select "GPU" as Runtime Type).

## Contacts:

* **Created by: [Kanishk Sharma](https://github.com/kanishksh4rma) **
* **LinkedIn: [Kanishk Sharma](https://www.linkedin.com/in/kanishksh4rma/)**
