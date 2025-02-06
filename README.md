 Integrating NLP and Computer Vision for Gesture Recognition and Sentiment Analysis

In this project, I combined *Computer Vision with *Natural Language Processing (NLP) to create a system that recognizes hand gestures (Like/Dislike) and determines sentiment based on these gestures.  

How Does the Project Work?
1.  Using Mediapipe for Hand Tracking 🖐  
   - The camera is activated, and the user’s hand is analyzed using *MediaPipe Hands to detect finger positions.  
   - The system checks whether the thumb is up (👍 Like) or down (👎 Dislike).  

2.  Sentiment Analysis Using an NLP Model from Hugging Face 🧠  
   - When a 👍 gesture is detected, the phrase "I love this!" is sent to a DistilBERT model for sentiment analysis, which is likely to classify it as Positive.  
   - When a 👎 gesture is detected, the phrase "I hate this!" is analyzed and typically classified as Negative.  
   - The result is displayed on the screen with a confidence score.  

Potential Applications 📌 
- Can be developed as part of *touchless interaction systems.  
- Useful for analyzing emotional responses to visual content.  
- Can be integrated into chatbots or interactive AI to understand user sentiment more effectively.  

Final Outcome 🎯
When the code runs, the system detects hand gestures, classifies them, and then applies a sentiment analysis model to determine whether the gesture represents a positive or negative emotion. This approach demonstrates how NLP and Computer Vision can be combined to create more interactive and intelligent applications!  



🚀 Do you have other ideas on how to expand this project? Share your thoughts in the comments!
