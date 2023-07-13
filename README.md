# Object Recognition for Visually Challenged Individuals

This project is aimed at helping visually challenged people to detect, recognize and describe their surroundings using object recognition and text-to-speech. It employs YOLO model v8 for object detection and recognition, and pyttsx3 for text-to-speech conversion. This can be beneficial in helping visually challenged individuals in understanding the environment around them.

## Setup <br />
1. Clone the repository <br />
```
git clone https://github.com/rawbeen248/object-recognition-for-visually-challenged
```

3. Navigate to the directory: <br />
```
cd object-recognition-for-visually-challenged
```

5. Create a virtual environment: <br />
```
python -m venv venv
```

6. Activate the virtual environment: <br />
   On Windows: ```.\venv\Scripts\activate``` <br />
   On Linux or macOS: ```source venv/bin/activate```

7. Install the requirements: <br />
```
pip install -r requirements.txt
```
8. Run the script or notebook obj_rec_main.ipynb

## Future Improvements
- One of the possible improvements is calculating the distance between the objects and the camera. This would allow the system to describe objects with more precision, informing if they are close or far.
- Different approaches can be used for distance estimation, including monocular depth estimation models, or using cameras with built-in depth sensors like Intel RealSense.
