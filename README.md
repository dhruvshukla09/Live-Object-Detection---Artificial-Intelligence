Files needed for the Project 

python3
numpy
argparse 
imutils
time 
opencv(CV2)
os

for running the image.py code
in the 8th line
ap.add_argument("-i", "--image", default="C:/Users/vidhi/OneDrive/Desktop/Live detection/images/1.jpg"
set the path to the image

to run the file 
on command prompt 
set the path to the folder 
python3 image.py

for running video.py code
in the line 9,replace the path where u want the video from, 
ap.add_argument("-i", "--input", default="C:/Users/vidhi/OneDrive/Desktop/Live detection/videos/maharastraaa_01.mp4",
	help="path to input video")
	
in the line 11,replace the path where u want the video to be saved to,
ap.add_argument("-o", "--output", default="C:/Users/vidhi/OneDrive/Desktop/Live detection/output/maharastraaa_01_output.avi",
	help="path to output video")

in the line 13,replace the path of yolo-coco folder,
ap.add_argument("-y", "--yolo", default="C:/Users/vidhi/OneDrive/Desktop/Live detection/yolo-coco",
	help="base path to YOLO directory")

to run the file 
on command prompt 
set the path to the folder 
python3 video.py

to run the test_live which is for object detection on live feed
on command prompt 
set the path to the folder 
python3 test_live.py

q on the cam window to stop the feed