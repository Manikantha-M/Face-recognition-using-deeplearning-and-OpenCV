# TG-hackathon-1
# Outputs of webcam stream
## output1
 <p align="center">
   <img src="output221.gif">
  </p>
  
## output2
 <p align="center">
   <img src="output222.gif">
  </p>


## sample dataset for known(Manikantha)
 <p align="center">
   <img src="cap21.JPG">
  </p>
  
## sample dataset for unknown
 <p align="center">
   <img src="cap22.JPG">
  </p>


# Theory
To build our face recognition system, we’ll first perform face detection, extract face embeddings from each face using deep learning, train a face recognition model on the embeddings, and then finally recognize faces in both images and video streams with OpenCV.

Detect faces
Compute 128-d face embeddings to quantify a face
Train a Support Vector Machine (SVM) on top of the embeddings
Recognize faces in images and video streams
All of these tasks will be accomplished with OpenCV, enabling us to obtain a “pure” OpenCV face recognition pipeline.
