# Face-Matching-system
Face Matching System built with Python, DeepFace, and OpenCV for fast and accurate image-based face recognition.

Methods Applied
🔹 Data Preparation

Organized dataset into labeled folders for each person.

Ensured clear, front-facing images for accurate encoding.

🔹 Face Matching Process

Used DeepFace library with Facenet model to extract embeddings.

Compared input image embeddings with dataset embeddings.

Computed Euclidean distance to determine the best match.

Displayed both the input and matched images using OpenCV.

Tools & Libraries

Python 3.8+

DeepFace

OpenCV

NumPy

Pandas

TensorFlow / Keras (backend for DeepFace)

Results

Successfully matched faces from a dataset of multiple individuals.

Reported matching accuracy using distance scores (lower = more similar).

Displayed visual confirmation with side-by-side images.

Future Work

Integrate real-time recognition using webcam feed.

Add pre-trained model selection (ArcFace, VGG-Face, etc.).

Improve speed by pre-caching embeddings.

Build a simple GUI or web interface for user testing.
