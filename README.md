# face_recognition_and_tracking_with_mtcnn
Important links, code is inspired from:
- original url: https://github.com/vudung45/FaceRec
- models (need to download): https://github.com/davidsandberg/facenet
- MTCNN Face Detection: https://kpzhang93.github.io/MTCNN_face_detection_alignment/
- Augmentation code: https://github.com/vxy10/ImageAugmentation
- Fancy borders: https://www.codemade.io/fast-and-accurate-face-tracking-in-live-video-with-python/

Facenet:
- example network is based the work done by David Sandberg here: 
- https://github.com/davidsandberg/facenet
Facenet is not a classifier that is trained to classify a face as 
belonging to a particular individual that it was trained on. Instead it is trained to find and quantify 
landmarks on faces in general. By comparing the face landmark quantification values (network inference output) 
on two images, it is possible to determine how likely the two faces are of the same person.

Face tracking using dlib:
- https://www.guidodiepen.nl/2017/02/detecting-and-tracking-a-face-with-python-and-opencv/
- https://www.guidodiepen.nl/2017/02/tracking-multiple-faces/
- https://github.com/gdiepen/face-recognition
Face tracking using opencv:
- https://www.learnopencv.com/object-tracking-using-opencv-cpp-python/

More intersting links:
- https://github.com/yobibyte/yobiface
- https://github.com/ageitgey/face_recognition
- https://github.com/shaoanlu/faceswap-GAN

## Instructions
- Download models
- Collect images of persons that appear in your video. Put them in the images folder
- Get a video (for example https://www.youtube.com/watch?v=NuhCoO6GO5U). Put it in the videos folder
- Change name of video in code and run
- Output should be similar to: https://drive.google.com/file/d/1URUCyngQ1lsZvKu3up2Vdnuc8172WXYb/view?usp=sharing
