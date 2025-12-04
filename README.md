Here’s your revised project description with the name changed from Akash to Sai Spandana:

***

## Gesture Sense — Empowering the Needed

Gesture Sense is an intelligent system designed to automate the analysis of hand gestures using advanced LSTM-based deep learning networks.

![](Images/action_identifier_pipeline Gesture Detection

The platform offers an interactive detection experience where it captures video frames in real time, processes them to extract keypoints, and utilizes a trained LSTM model to recognize specific gestures.

![](# Key Features

#### Data Collection
Gesture Sense collects video frames via OpenCV and processes them using MediaPipe to extract relevant keypoints. These keypoints are then stored for further analysis and model training.

#### Preprocessing
Before training, the data undergoes normalization, sequence formation, and splitting into training and validation sets, ensuring clean and consistent inputs for the LSTM model.

#### Model Building and Training
Using TensorFlow, a Sequential model integrating LSTM and Dense layers is constructed. The model is compiled with an appropriate loss function and optimizer, then trained on the preprocessed dataset. Training progress and metrics are monitored through TensorBoard.

#### Evaluation and Prediction
Model performance is evaluated using metrics such as multilabel confusion matrix and accuracy score from scikit-learn. Once trained, Gesture Sense can predict gestures in real time with impressive precision.

### Try It Out

Make sure you have git installed: [https://git-scm.com/](https://git-scm.com/)

```
git clone [https://github.com/Swam244/Action_Identified.git](https://github.com/Swam244/Action_Identified.git)
```

Then run:
```
cd Gesture_Sense
pip install -r requirements.txt
```

### Technology Stack

**TensorFlow:** Used for building and training the Sequential model with LSTM and Dense layers.  
**OpenCV:** Handles video capture and frame processing for keypoint extraction.  
**MediaPipe:** Provides holistic models for detecting poses, hands, and facial features, enabling efficient keypoints extraction.

***

## My Motivation — Sai Spandana

One of the projects I’m most proud of is Gesture Sense. The inspiration came from seeing posters featuring hand signs for the International Day of Sign Languages. While there are many language-learning apps like Duolingo, I realized there were very few accessible tools for learning sign language. This thought coincided with our hackathon ideation phase and ultimately shaped the core concept of our project.

My team of five brainstormed several ideas, but the one I proposed—an intelligent gesture recognition system—stood out. Our biggest challenge was accurately identifying and classifying gestures in motion. Having prior experience with OpenCV but limited knowledge of video-based models, I took the initiative to explore Recurrent Neural Networks (RNNs) and Gated Architectures.

When our initial RNN-based prototype produced poor accuracy, I pivoted toward Long Short-Term Memory (LSTM) networks to address the vanishing and exploding gradient issues. With rapid iteration, we successfully built a functional MVP just in time. I led the team as both AI engineer and project lead, structuring the neural network while my teammates created datasets, tested MediaPipe’s holistic solutions, and processed input data. The result was a winning hackathon solution that we were all deeply proud of.
