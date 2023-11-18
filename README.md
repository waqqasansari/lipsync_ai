# Project Name: Lip Sync

## Overview

The objective of this assignment is to demonstrate your skills in creating an AI model that is proficient in
lip-syncing i.e. synchronizing an audio file with a video file. Your task is to ensure the model accurately
matches the lip movements of the characters in the given video file with the corresponding audio file

## Features

- **Wave2Lip:** Utilize Wave2Lip for accurate lip region extraction from the input video.

- **GfpGAN:** GfpGAN for enhancing the video created by wave2lip.

### Inputs
- [audio](https://drive.google.com/file/d/1Xt66mzCa0Q7r6IfIeUzMAm3xVAIT9VT0/view?usp=sharing)
- [video](https://drive.google.com/file/d/19M2rnbaCbr5lcDE8rCcq501s92PZL4kF/view?usp=sharing)
- [Still pic](https://drive.google.com/file/d/1B2PgcSZPUfogeg2px9cB3PXJDhzLgEcX/view?usp=sharing)

### Outputs
- [video](https://drive.google.com/file/d/1ZeLl-2hbdyTU5nqSS4R_tXe3ZDYCEU-t/view?usp=sharing)
- [Still pic](https://drive.google.com/file/d/1JcrcpvzpKTFsSwp4CHqGArOzCndxLYzp/view?usp=sharing)

### How to Use

#### Using Google Colab

1. Colab notebook is provided in this repo.
2. Run the first code block labeled "clone the repositories in their respective folders." This will take 1-2 minutes.
3. Run the second code block for all necessary installation This will take 1-2 minutes.
3. Upload a video file and audio file to the `content/inputs` folder in Colab.
4. Run the third cell, you can choose the model "wave2lip_gan" or "wave2lip"
5. Once finished, run the code block labeled "Enhance the video with GFPGAN" to increase the quality of the face.
6. Run the last cell that will put the audio on the enhanced video
6. Download your file from `contents/outputs`, likely named `output_video.mp4`.

# Acknowledgment
[Wav2Lip](https://github.com/Rudrabha/Wav2Lip/tree/master)

[Wav2Lip-GFPGAN](https://github.com/ajay-sainy/Wav2Lip-GFPGAN)
