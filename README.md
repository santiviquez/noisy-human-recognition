# Noisy Human Recognition
Recognized non-speech human sounds such as:

Clapping 👏
Footsteps 🦶
Brushing Teeth 🪥
Drinking Sipping 🧃
Laughing 😂
Breathing 🌬️
Crying Baby 😭
Coughing 🤧
Snoring 😴
Sneezing 🤧

## Demo
Test the model at: [link](https://huggingface.co/spaces/santiviquez/noisy_human) (hugging face space)

## Datasets
[ESC-50 dataset](https://github.com/karoldvl/ESC-50/archive/master.zip). Using only non-speech humman sounds.
## Models
### Classical ML Models:
* Random Forest
* SVM
* XGBoost
### CNN-Based Models:
* CNN on Mel spectrogram
* CNN on Mel spectrogram + Deltas
* CNN on Mel spectrogram + Deltas + Augmentations
* CNN on Mel spectrogram + Deltas + Trimmed Audios
* CNN-LSTM
