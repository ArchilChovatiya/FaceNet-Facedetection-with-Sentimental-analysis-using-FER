# FaceNet-Facedetection-with-Sentimental-analysis-using-FER
### Installation Python Libraries:
- Tensorflow (1.4.0)
- Scipy (0.17.0)
- Scikit-learn (0.19.1)
- Opencv (2.4.9.1)

### Process to train facenet model
- Place Dataset of images in folder containing Label same as person name and place it in ./train_img.
- After that run data_preprocess.py and then run train_main.py
- in ./pre_img you will find processed (cropped) images of faces

### Usage:
- Well this facenet is defined and implementation of facenet paper published in Arxiv (FaceNet: A Unified Embedding for Face Recognition and Clustering). And also contain the idea of two paper named as "A Discriminative Feature Learning Approach for Deep Face Recognition" and "Deep Face Recognition". For deep understanding about its concept you can follow upper paper. One also main part is that for genearating your own model you can follow this link Face Recognition using Tensorflow. David Sandberg have nicely implemnted you can also find it on Github for complete code and uses.