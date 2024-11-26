# AFfectSense
## Multimodal Emotion Recognition Application

![affectsense](https://github.com/ManrajDhatt/affect_sense/blob/main/Screenshot%202024-11-23%20212725.png)

Emotion recognition is essential for building intelligent systems that interact naturally and adaptively with users.
Applications in fields like healthcare, customer service, and personal 
virtual assistants benefit from accurately detecting emotions, as this helps 
create more human-centered technology. AffectSense enhances emotion recognition by adopting a multimodal approach, recognizing that emotions are expressed through both facial expressions and vocal tones.

AffectSense combines two Convolutional Neural Network (CNN) models—on
e for Facial Emotion Recognition (FER) using the FER2013 dataset and anothe
r for Speech Emotion Recognition (SER) trained on RAVDESS, TESS, and SAVEE datasets. This allows AffectSense to analyze a broad range of emotions, capturing a more nuanced emotional profile than traditional single-modality models.

The web application, built with Flask and AJAX, provides users with real
-time emotion recognition. The interface displays a video stream where the 
primary detected emotion is overlaid on the screen, with a bar chart reflecting the probability of each emotion and an emoji representing the primary emotion, making the application interactive and engaging.

By combining facial and vocal cues, AffectSense performs robustly across 
various environments, even where one modality alone might be insufficient. This multimodal fusion ensures AffectSense can adapt effectively in diverse situations, making it a promising tool for more accurate, context-aware emotion recognition.
