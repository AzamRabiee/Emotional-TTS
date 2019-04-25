# Emotional-TTS

Demo and sample files for "Emotional End-to-End Neural Speech synthesizer" https://arxiv.org/pdf/1711.05447.pdf, which is
a Korean Emotional End-to-End Neural Speech synthesizer, based on the Tacotron model (Y. Wang et al., “Tacotron: Towards End-to-End Speech Synthesis,” arXiv Prepr. arXiv1703.10135, 2017).  
Code is forked from https://github.com/keithito/tacotron

### Demo
For demo, click http://143.248.97.172:9000/ 

### Emotional TTS.zip
You can find synthesized waves and corresponding attention alignment plots of a sentence in 6 different emotions here. 

### Spectrograms.zip
As an example, Mel spectrograms of a sentence in happy and sad emotions are given here. You may find significant differences in their prosodic aspects. The Mel spectrogram corresponded to the happy signal shows more variations in pitch and it's shorter in time.  

### Tacotron Improvements.zip
The samples in this zip file belong to Section 4 of our paper (Younggun Lee, Azam Rabiee, Soo-Young Lee, "Emotional End-to-End Neural Speech synthesizer", accepted in Machine Learning for Audio Signal Processing (NIPS workshop), 2017)

# Continuous Emotional-TTS
Emotion is not limited to discrete categories of happy, sad, angry, fear, disgust, surprise, and so on. Instead, each emotion category is projected into pleasure-arousal-dominance, known as PAD. The value of each dimension varies from -1 to 1, such that the neutral emotion is in the center with all-zero values. Training an emotional text-to-speech (TTS) synthesizer on the independent dimensions provides the possibility of emotional speech synthesis with unlimited emotion categories. 

### Demo
For demo, click http://143.248.97.172:9010/ 

### Continuous Emotional samples.zip
You can find synthesized waves with various emotions here. 
