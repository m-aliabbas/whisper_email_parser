# Email Address Extractor from Whisper Transcripts
## Brief Introduction
This repository hosts a solution designed to tackle the challenge of transcribing email addresses accurately from audio files. The core issue arises when using Whisper, an automatic speech recognition system, which transcribes email addresses into plain text without distinguishing them as unique entities. Our tool, encapsulated in a Jupyter notebook titled `email_correction.ipynb`, serves as a wrapper that enhances Whisper's output by accurately extracting and formatting email addresses from the transcripts.
## Features

Accurate Email Extraction: Improves Whisper transcripts by accurately identifying and extracting email addresses.
Seamless Integration: Designed to work as a post-processing step for Whisper transcripts.
Easy to Use: Provided as a Jupyter notebook for ease of use and adaptability.

## How It Works

The tool analyzes Whisper-generated transcripts and applies a combination of regular expressions and heuristic methods to identify potential email addresses that are transcribed as plain text. It then formats these identified strings as email addresses, improving the accuracy and usability of the transcription.

## Usage
1. Run the Jupyter notebook.
2. Follow the instructions within the notebook to input your Whisper transcripts.
3. The notebook will process the transcripts and output the text with email addresses accurately extracted and formatted.

## Credit
Muhammad Ali Ababs (Sr. ML Engr / Team Lead Idrak Ai Ltd ) | Muhammad Musawir Baig (ML Engr)
