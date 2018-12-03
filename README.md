ASL Classification using a retrained Inception v3 network.

Authors: William Moser, Jacob Hopkins, Jacob Sanchez

Needed System: Windows OS

1. Installation
	- Python 3.6 or newer must be installed (Prefered version is 3.6.6)
	- Run a command terminal (possibly as an Administrator) to use these commands:
		pip3 install --upgrade tensorflow
		pip3 install --upgrade opencv-python

2. To execute the program, in the command terminal
	- go to the program's main directory
	- use the command py webcam.py
	
3. The title window will appear. Press any key to continue

4. The stream will appear. Make a hand sign within the window.
   Press the space bar to capture the frame.

5. The tester function of test.py will then be called and executed

6. Two image windows will be displayed: the tested frame and the predicted class image.

7. Press the escape key to continue.

8. You can capture any frame to test once the stream window is displayed

9. Or you can press the escape key to close the program.

10. If network needs to retrained, open a command terminal

11. Change directory to the application's directory

12. Use the command to "py retrain.py" to begin training.

13. The training may take up to 8 hours.
