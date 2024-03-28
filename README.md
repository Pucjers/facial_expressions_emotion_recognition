# Facial expressions emotion recognition
### Emotion classification using the RAVDESS video dataset

A detailed description of the dataset can be found above. The description was provided by Zenodo. The dataset can be downloaded [here](https://zenodo.org/record/1188976#.Xpaa3i-caAP).

I used only video data and created a model to predict emotions from facial expressions.

According to the dataset, there are 2 sentences from 24 actors: "Children are talking at the door" and "Dogs are sitting at the door". My main goal in this project is to analyse videos and find emotions in them.

### File naming convention

Each of the 7356 RAVDESS files has a unique filename. The filename consists of a 7-part numerical identifier (e.g., 02-01-06-01-02-01-12.mp4). These identifiers define the stimulus characteristics: 

*Filename identifiers*

Modality (01 = full-AV, 02 = video-only, 03 = audio-only).<br>
Vocal channel (01 = speech, 02 = song).<br>
Emotion (01 = neutral, 02 = calm, 03 = happy, 04 = sad, 05 = angry, 06 = fearful, 07 = disgust, 08 = surprised).<br>
Emotional intensity (01 = normal, 02 = strong). **NOTE**: There is no strong intensity for the 'neutral' emotion.<br>
Statement (01 = "Kids are talking by the door", 02 = "Dogs are sitting by the door").<br>
Repetition (01 = 1st repetition, 02 = 2nd repetition).<br>
Actor (01 to 24. Odd numbered actors are male, even numbered actors are female).<br>

**Video pre-processing**
All videos need to be pre-processed.
1. I converted all the images to grayscale.<br>
2. Then I cropped and resized them to the same size<br>


### Final model view

![завантаження](https://github.com/Pucjers/facial_expressions_emotion_recognition/assets/40600332/07d617a4-9791-43e6-a290-eb6e5e9550a4)

### Model results

![зображення_2024-03-28_164333425](https://github.com/Pucjers/facial_expressions_emotion_recognition/assets/40600332/3e766af4-472d-4de5-b8fb-cbb99041dc05)
