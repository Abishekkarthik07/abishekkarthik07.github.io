---
layout: single
title: "StoryFromVideo-AI"
permalink: /projects/storyfromvideo-ai/
author_profile: true
---

## StoryFromVideo-AI

Generating Structured Narratives From Short Videos

StoryFromVideo-AI (also called Vid2Story Generator) is a project I built to explore how far open-source models can go in understanding video content and turning it into coherent written stories. I wanted to create a small, self-contained tool that could take a video, break it down into audio and visual components, understand both, and then construct a readable narrative from the combined information.

## Motivation

I wanted to experiment with building an “AI storyteller” that didn’t rely on paid APIs and didn’t need any cloud services. Large organizations often demonstrate impressive multimodal models, but I wanted to see what could be accomplished on regular hardware using open-source technologies like Whisper and BLIP.

## What the System Does

StoryFromVideo-AI takes a short video and processes it in several stages:

1. Extract audio from the video (OpenCV)
2. Transcribe speech using Whisper
3. Extract representative frames and caption them with BLIP
4. Combine audio transcription and captions into a structured summary
5. Generate a story in a chosen genre and provide downloadable text

## Technologies Used

- Python
- Streamlit
- Whisper (audio transcription)
- BLIP (image captioning)
- OpenCV (frame extraction)

## What I Learned

- Multimodal pipelines (audio + visual → text)
- Frame extraction and basic video processing
- Running open-source models efficiently

<p style="margin-top:1rem;"><a href="https://github.com/Abishekkarthik07/StoryFromVideo-AI" style="text-decoration:none;"><strong>[View code]</strong></a></p>

<p style="margin-top:1rem;"><a href="/projects/" style="text-decoration:none;color:#1a73e8;">← Back to Projects</a></p>
