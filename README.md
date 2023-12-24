# Multilingual-Phoneme-Recognition
This is the project I did of the course Speech Recognition D. I have completed character-level Automatic Speech Recognition (ASR) and phoneme-level ASR experiments for Czech to Czech, Czech to Finnish, and Czech to Norwegian, encompassing the entire process from data preprocessing, model training to performance evaluation.

The notebooks use "facebook/wav2vec2-lv-60-espeak-cv-ft" in the parameters of 'model = Wav2Vec2ForCTC.from_pretrained()' instead of "facebook/wav2vec2-xls-r-300m" for the pheneme replacing character, compared with the tutorial (https://huggingface.co/blog/fine-tune-xlsr-wav2vec2).

following the mentorship from https://github.com/raghebalghezi/MultilingPhonemeRecognition.git

Professor: Mikko Kurimo;
Tutor: Ragheb Al-Ghezi;
Team partner: Bijoy Mehedi Hasan, de la Brassinne Maxence

