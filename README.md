# FREAK

About the project

This is a Face recognition Lock built using Python(OpenCV), Raspberry Pi, PiCam, Arduino and the following Algorithms:

Eigen Faces
Local Binary Pattern Histograms
Fisher Faces



How it works

The model runs a server client model. The PiCam takes the image and the Pi sends it to the server. The server runs the Haar Cascade Files and detects the face. It then recognizes the face using a model trained by the above 3 algorithms. The decision is then sent by the server to the Arduino which opens the lock if its the authorized person. Using the Twilio API we also maKe sure that the owner gets a SMS if there is a heist. 
