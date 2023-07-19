README.md

# Real-Time Voice Cloning with Hugging Face Models


## Overview

This repository provides an easy-to-use real-time voice cloning model based on pre-trained Hugging Face models. Voice cloning, also known as voice synthesis, allows users to generate synthetic speech that sounds like a specific person. The implementation is designed to be user-friendly, making it suitable for both beginners and experienced users to leverage the power of Hugging Face's state-of-the-art models.

## Features

- **Hugging Face Integration**: The code seamlessly integrates with Hugging Face's model hub, enabling users to leverage their pre-trained models for voice cloning tasks.
- **Real-Time Synthesis**: The voice cloning process is efficient and real-time, providing immediate results with minimal processing time.
- **Customizable Voice Cloning**: Users can input their desired text or provide an audio file for voice cloning. The model reproduces the unique vocal characteristics of the target speaker.

## Requirements

To use the real-time voice cloning model, you need the following dependencies:

- Python 3.5 or higher
- torch
- numpy
- scipy
- librosa
- other dependencies specified in the requirements.txt file (refer the drive link provided in Pre-Trained Models.txt)

## Installation

1. Clone the repository to your local machine:

```
!git lfs install
!git clone https://huggingface.co/spaces/keithhon/Real-Time-Voice-Cloning
```

2. Install the required Python packages:

```
!pip install -r Real-Time-Voice-Cloning/requirements.txt
```

3. Download the pre-trained models:

Download the pre-trained encoder, synthesizer, vocoder models and other reference files from this link (https://drive.google.com/drive/folders/1aqLOib5EYj63SROsdddEevDDdozjAqSO?usp=sharing)

```
saved_models/encoder.pt
saved_models/synthesizer.pt
saved_models/vocoder.pt
```

## Usage

To perform voice cloning with the real-time voice cloning model, follow these steps:

1. Open the provided Jupyter Notebook:

```
jupyter notebook voice_cloner.ipynb
```

2. In the Jupyter Notebook, input your desired text or specify the path to an audio file for voice cloning.
3. Run the cells in the Jupyter Notebook to initiate the voice cloning process.
4. The generated synthetic speech will be saved in the specified output file path.



