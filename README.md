# gifmaking
advance programming fun for middle schoolers

Prerequisites
pip install opencv-python
pip install dlib
brew install imagemagick
pip install imutils
    
#grab the files you need from git

git clone https://github.com/denniswall/gifmaking.git
    
## To run the python file type:
      
    python create_gif.py --config config.json --image images/inputname.jpg --output outputname.gif
    
 
Building a Deal With It meme generator using OpenCV can teach us a number of valuable techniques used in practice, including:

1)How to perform deep learning-based face detection.

2)How to use the dlib library to apply facial landmark detection and extract the eye regions.

3)How to take these two regions and compute the rotation angle between the eyes.

4)And finally, how to generate animated GIFs with OpenCV (with a little help from ImageMagick).


In order to build our meme generator, we leveraged computer vision and deep learning in a number of practical ways, including:
- Face detection
- Facial landmark prediction
- Extracting regions of the face (in this case, the eyes)
- Computing the angle between the eyes, a requirement for face alignment
- Generating transparent overlays via alpha blending
