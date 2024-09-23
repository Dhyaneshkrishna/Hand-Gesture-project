1.Features
Slide Navigation: Use specific hand gestures to move between slides.
Annotation Drawing: Draw on slides using hand gestures for marking key points.
Dynamic Interaction: Real-time hand detection and gesture recognition.
Gesture Threshold: A visual line that differentiates between navigation gestures and drawing gestures.

2.Hand Gestures
Gesture Functionality
✋ Index finger up-Start drawing annotations
🤚 Thumb up-	Go to the previous slide
👊 Pinky finger up-	Go to the next slide
✌️ Index & middle up-	Draw a point on the slide
🤟 Three fingers up	-Undo last annotation

3.Clone the repository:

git clone https://github.com/your-repo/gesture-presentation.git
cd gesture-presentation

4.Install required packages: Install the dependencies using pip:
pip install opencv-python cvzone numpy

5.Organize presentation images:
Place your slide images in a folder named Presentation inside the project directory.
Supported formats include .png, .jpg, .jpeg.

6.Usage
Run the script:
python gesture_presentation.py

7.Navigate and Annotate:
Start the webcam feed.
Use gestures to navigate between slides or annotate the current slide.
Press 'q' to exit the presentation.

8.Requirements
Python 3.x
OpenCV
CVZone
NumPy
