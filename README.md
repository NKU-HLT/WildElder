# WILDELDER: A CHINESE ELDERLY SPEECH DATASET FROM THE WILD WITH FINE-GRAINED MANUAL ANNOTATIONS
[![Hugging Face Datasets](https://img.shields.io/badge/🤗%20Hugging%20Face-Datasets-yellow.svg)](https://huggingface.co/datasets/Hui519/WildElder)
[![License: CC BY-NC-SA-4.0](https://img.shields.io/badge/License-CC%20BY--SA--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

WildElder is a speech dataset focused on elderly scenarios. It contains raw audio and corresponding text annotations and can be used for ASR, speaker-related tasks, and front-/back-end speech processing research. The data was collected and cleaned from real-world environments to preserve diversity and realistic noise conditions.

## Directory Structure
- audio/
  - old_bozhu_download/.../*.wav: audio files
  - old_bozhu_download/.../*.txt: text annotations
- data_split/ (Kaldi-style lists)
  - dev|test|train/.../wav.scp: entries in the form `utt_id path/to/audio.wav`; paths are relative and start with `WildElder/...`
  - dev|test|train/.../text: entries in the form `utt_id transcription`

## Annotations and File Formats
- Text annotations (.txt)
  - Example (after processing):
    - 勾股定理就是三角形斜边的平方等于两个直角边的平方和，
- wav.scp (relative paths)
  - Example:
    - old_bozhu_download_B_bozhu_1_1_audio_004 WildElder/audio/old_bozhu_download/B_bozhu_1/1/audio_004.wav
- text
  - Example:
    - old_bozhu_download_B_bozhu_1_1_audio_004 勾股定理就是三角形斜边的平方等于两个直角边的平方和，

## Copyright and Data Rights
- Source: The dataset content is extracted/derived from a third-party platform. We do not own or claim the original copyright to the underlying audio or transcripts.
- Rights: All rights to the original content remain with the respective platform and original rightsholders. Any trademarks or copyrighted works referenced are the property of their respective owners.
- Intended use: Provided strictly for academic research and internal testing. Redistribution or commercial use may infringe third-party rights and is not authorized here.

## Takedown Policy
- If you are a rightsholder (or represent one) and believe that any material in WildElder infringes your rights, please contact the maintainers. Upon verified request, we will promptly remove or restrict access to the relevant content.

## License and Citation
- For academic research and internal testing. For commercial use, please contact the maintainers first.
- Citation example: WILDELDER: A CHINESE ELDERLY SPEECH DATASET FROM THE WILD WITH FINE-GRAINED MANUAL ANNOTATIONS, 2025. 
