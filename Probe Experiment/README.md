# The effect of dynamic facial expressions on attentional bias in socially anxious individuals

# Background
This study investigates how socially anxious individuals allocate attention to emotional facial expressions using a dot-probe paradigm. The research addresses contradictory findings in the literature: cognitive models predict selective attention to negative (i.e., angry) facial expressions, whereas some clinical observations suggest avoidance of such cues.

Participants in this study will be presented with pairs of facial stimuli showing bi-directional emotional transitions between neutral and angry expressions. Transitions from neutral to angry may signal the emergence of a threat, while angry to neutral transitions may signal the disappearance of a threat. They will then fill out a 24-item questionnaire about their social anxiety levels.

By measuring reaction times to probes, the study infers attentional biases to threat and avoidance behavior and how it correlates to social anxiety levels.

# General Methods
Participants will view two face stimuli simultaneously, with opposite facial expression transition direction (one is angry-to-neutral, the other is neutral-to-angry). A probe (dot) will appear behind one of the videos, and reaction time according to facial expression transition will be recorded. Participants will later fill out a LSAS questionnaire for researchers to evaluate social anxiety levels. They will also be given the opportunity to disclose any mental health diagnoses. Conditions are randomized and balanced. Certain emotional transition faces and probe will appear randomly on the left or right side, but each location will be shown an equal number of times. Experimentally, there is only one manipulated independent variable (congruency), but the analysis design will be 2x2 (congruent/incongruent and high social anxiety/low social anxiety).

# Cool Features! 
This experiment contains practice trials and break trials! 

# Files
- "circle.png" is the probe
- "stim" is the file of facial expression stimuli. It contains mp4 videos approximately 500ms in length. They follow the labelling convention "[actor #]_[side of neutral-to-angry emotional transition].mp4" (ex. "1_L.mp4" means that the video contains actor 1, with the neutral-to-angry emotional transition on the left side)
- "probe_experiemnt.html" is the code

# How to Use 
1. Clone the repository using the git clone OR download the experiment code ("probe_experiment.html")
2. Download the probe and "stim" folder
3. Explanations for running/modifying the experiment can be found in the html code :) If you would like to use different stimuli, you will need to manually create the videos
4. After the experiment is run, it will automatically be downloaded as a csv file ("probe_experiment_data.csv")

Please note: You will need a Wifi connection to run the experiment, as it requires importing from jsPsych!

# Data
The experiment will collect the following pieces of data from each participant:

- Video pair ID
- Reaction time
- Probe congruency (where the probe appears relative to the emotion transition)
- Response accuracy
- LSAS fear, avoidance, and total scores
- Diagnosed mental conditions (optional for participants to answer)

# References
Questionnaire: Liebowitz, Michael R. Liebowitz Social Phobia Scale. Modern Problems of Pharmacopsychiatry 22 (1987): 143-171.
Faces stimuli: Lyons, M., Kamachi, M., & Gyoba, J. (1997). The Japanese Female Facial Expression (JAFFE) Dataset [Data set]. Zenodo. https://doi.org/10.5281/zenodo.14974867

# Contact Information
For more information, please email zhoum95@mcmaster.ca 
