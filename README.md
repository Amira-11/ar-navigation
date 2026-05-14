GymGuide: Intelligent Gym Assistance System
GymGuide is an AI-driven image classification system designed to bridge the gap between gym beginners and professional exercise techniques. By leveraging Computer Vision, the system identifies gym equipment from a single photo and provides an immediate, relevant YouTube tutorial, empowering users to train safely and correctly without needing human assistance.
Project Objective
The core mission of this project is to provide a simple, interactive, and autonomous learning environment for gym-goers. It solves the common problem of "gym intimidation" or "incorrect form" by offering instant guidance at the point of need.
Key Features
Autonomous Identification: Recognizes gym machines using a custom-trained Convolutional Neural Network (CNN).

Interactive Guidance: Automatically fetches a specific YouTube tutorial for the identified machine.

User-Centric Design: Focuses on simplicity and accessibility for beginners.

Academic Rigor: Evaluated with detailed metrics to ensure reliable performance in a real-world gym environment
Evaluation & Results
The system was tested on a diverse dataset of 293 images across 6 machine classes, achieving a robust 88% Overall Accuracy.

Detailed Performance Metrics:Equipment Class,Precision,Recall,F1-Score
Bench Press,0.82,0.89,0.86
Bicycle,0.96,0.86,0.91
Leg Press,0.85,0.72,0.78
Pec Deck,0.84,0.95,0.89
Rowing,0.83,0.81,0.82
Treadmill,0.96,1.00,0.98
Technical Stack
Frameworks: TensorFlow & Keras for Deep Learning.

Processing: ImageDataGenerator for real-time image rescaling and normalization.

Environment: Google Colab with GPU acceleration.

Evaluation: Scikit-learn for classification reporting
ow it WorksCapture: User uploads an image of the equipment.Process: The system rescales the image to $224 \times 224$ and normalizes it.Classify: The CNN model predicts the equipment class.Assist: The system displays the machine name and the direct YouTube link for the tutorial.
