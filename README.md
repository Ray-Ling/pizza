# Pizza Detector
This program will look at a picture of a pizza and recognize the stage of cooking it is in. The various stages include: "perfect", "slightyly chared", and "burnt". 
It uses imagenet to detect the amount of burnt areas and determine the specific stage of the pizza. 

# To run the program
1. Open VScode and ssh to your nano IP address
2. Go to the directory where the python file called "imagnet.py" and upload different pizza pic
3. Enter this comman in the terminal 
~/jetson-inference/python/examples$ python3 imagenet.py (your file) (result file name)
