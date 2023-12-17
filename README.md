This project aims to develop a highly accurate AI model for lip-syncing, precisely aligning the lip movements of characters in a video with the corresponding audio. Utilizing advanced deep learning techniques, the model will accommodate various languages, accents, and speech rates, with the goal of revolutionizing multimedia content creation for a seamless integration of audio and visual elements.

The input files used are:

    Video - https://openinapp.co/5cwva
    Audio - https://openinapp.co/o9vuj

Used Wav2Lip to lipsync using pretrained model downloaded using https://github.com/Rudrabha/Wav2Lip.

Prerequisites:

    Python 3.11.4
    Install necessary packages using pip install -r requirements.txt packages installed are:
    librosa
    numpy
    opencv-contrib-python
    opencv-python
    torch
    torchvision
    tqdm
    numba

python3 inference.py --checkpoint_path checkpoints/wav2lip.pth --face VID-20231217-WA0009.mp4 --audio temp/temp.wav

Lip-syncing videos using the pre-trained models (Inference) : The result is saved in results/result_voice.mp4.
