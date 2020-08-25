# FacialRecognitionMTCNN
Follow the steps below to extract faces from videos and save them as images.

1. Mount your google drive to access videos and save frames extracted from videos.
2. Import MTCNN from facenet_pytorch module and OpenCV module.
3. Get the count of frames in the video.
4. Set the batch size to extract a given number of frames from the video. eg 8 or 16.
5. Append frames in a list as long as the length of the list is not greater than the batch size.
6. Once the batch size is exceeded, reset the frames list as esmpty.
7. Continue this process untill all the videos in your specified directory have been processed.
8. TQDM package can optionally be used to show a progress bar for each video as it is being processed.
