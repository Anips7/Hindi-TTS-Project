# Hindi Text-to-Speech (TTS) Project

This project implements a Hindi Text-to-Speech system using a Tacotron2-inspired deep learning model.

## Project Overview
- Input: Hindi text
- Output: Mel-spectrogram representing speech
- Framework: PyTorch
- Platform: Kaggle (GPU enabled)

## Features
- Hindi text normalization
- Character-level vocabulary
- Mel-spectrogram generation
- GPU-based training
- Output visualization

## Dataset
Hindi TTS dataset from Kaggle:
https://www.kaggle.com/datasets/loopassembly/hindi-tts

## Model
- Architecture: Tacotron2-inspired
- Parameters: ~2.5M
- Training: 3 epochs on GPU

## Note
Audio waveform generation (vocoder) is not included.
This project focuses on text-to-speech feature generation.
