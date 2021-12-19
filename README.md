# Facial Emotion Detection and Recognition

### METHODOLOGY
- First, the Haar cascade method is used to detect faces in each frame of the wbcam feed.
- The region of image containing the face is resizd to 48X48 and is passed as input to the CNN
- The network outputs a list of softmax scores for the seven classes of emotions
- The emotion with maximum score is displayed on the screen

We can clearly see the wonders of AI in facial recognition. The amazing python library of
face_recognition, pretrained deep learning models and open-cv have already gained so much
performance and have made our life easier. There are lots of other materials that are helpful
and bring into picture different approaches used in achieving the same goal.

### DEPENDENCIES
- Opencv
- Cmake
- Dlib
- face_recognition
- Keras

### CONCLUSION
I have proposed and tested a general biulding designs for creating real-time CNNs. My proposed architectures have been systematically built in order to reduce the amount of parameters. I began by eliminating completely the fully connected layers and by reducing the amount of parameters in the remaining convenctional layers via depth-wise separable convolutions. I have shown that my proposed models can be stacked for multi-class classifications while maintaining real-time inferences. Specifically, I have developed a vision system that performs face detection and emotion classification in a single ntegrated module. <br>
I have achieved human-level performance in our classification tasks using a single CNN tthat leverages modern architecture constructs. My architecture reduces the amount of paramenters 80x while obtaining favorable results. Finally, I presented a visualization of the learned features in the CNN using the guided back-propagation visualization.
