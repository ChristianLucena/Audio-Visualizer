# Audio Visualizer

## Repository
<https://github.com/ChristianLucena/Audio-Visualizer.git>

## Description
This project aims to turn varied audio formats into artisic visual representations by mapping pixels to the sounds within the audio file. This aims to mimic the experience those with synesthesia or chromesthesia have to sound and contributes to the art world by making this a shareable perception.

## Features
Multi-Format Audio Processing
	- Programmed to accept and decode formats like MP3, WAV, and FLAC.
Frequency Analysis
	- break down audio files into varied frequencies to be used later in the visualizer
Dynamic Pixel Mapping
	- Linking specific frequency ranges to visual elements and pixels that will appear on screen.
User Interaction
    - Users will be able to pause, play, and skim through different parts of the visualizer to see its changes through the run time.

## Challenges
Logic for file reading/ conversion
  - Uploaded files need to be read by the program in the same way to have the desired outcome
Mapping visuals to Audio frequencies
  - Since this is an active visual program real-time mapping is required as it is running. This also needs to be done without causing lag.
Varying visual so the outcome does not become stale
  - I want the desired outcome to be unique each time and relate to the frequencies of the files uploaded. Doing this may be difficult when having to write variations within the code.

## Outcomes
Ideal Outcome:
- A polished application where users can drag-and-drop any audio file to generate highly responsive, intricate pixel-art environments with customizable color palettes and visual themes.

Minimal Viable Outcome:
- A basic script that loads a standard WAV file and accurately drives a simple grid of pixels or shapes to bounce and change color in sync with the track's volume peaks.

## Milestones
Week 1
  1. Set up the GitHub repository and configure the development environment with audio/graphics libraries.
  2. Write a script to successfully load and play back MP3 and WAV files.

Week 2
  1. Successfully extract volume and frequency data from a live audio stream.
  2. Create a basic 2D graphics window that can draw simple shapes or pixel grids.

Week 3 (Final)
  1. Map the audio frequency numbers directly to pixel colors, positions, and sizes.
  2. Test multiple audio files, bug-fix sync issues, and finalize documentation.