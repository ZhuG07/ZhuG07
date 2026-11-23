# Gordon Zhu

Second-year Computer Science and Statistics student at the University of Toronto, in the co-op program.

## Experience

### Docentra
*Co-Founder and Software Developer, 2026 to present*

- Built an AI medical scribe that turns clinical audio into structured notes using OpenAI Whisper and a local Mistral model, cutting physician note time from about 10 minutes to under 60 seconds.
- Developed the full-stack platform on FastAPI and SQLite, with separate doctor and patient portals, real-time audio capture and version tracking for notes.
- Kept all inference on the device so no patient data leaves the machine, and used CUDA acceleration to make transcription about five times faster than on a CPU.
- Ran requirements sessions with three physicians to shape the note structure and fit the tool into their workflow.

### FTC Robotics
*Programming Lead, 2022 to 2024*

- Led a team of four developers writing autonomous and driver-controlled robot software. The team qualified for the FTC Ontario Provincial Championship three years in a row.
- Built trajectory planning with RoadRunner, plus PID control and odometry, reaching a 95%+ success rate on pre-planned autonomous routes ([code](https://github.com/sta-titansrobotics/19446-IntoTheDeep)).
- Trained custom object detection models with TensorFlow and OpenCV for real-time detection and alignment.

### MAACA Summer Camp
*Robotics Instructor, Summer 2023*

- Taught hands-on robotics and programming with LEGO EV3 to more than 50 students, adapting lessons to each group's age and experience.

## Projects

### [ChessHacks Engine](https://github.com/ZhuG07/ChessHacks)
*Python, PyTorch, FastAPI*

A chess engine started at the ChessHacks hackathon with a team of three. A residual network with policy, evaluation and game-result heads, trained on 1.4 million Stockfish-labelled positions and fine-tuned with self-play, drives a batched alpha-beta search. A browser app lets you play against it and shows what it is thinking. Anchoring the network's evaluation to material took its score against a strength-limited Stockfish from 8% to 40%.

### [HematoTech](https://github.com/ZhuG07/Blood-Cell-Chemistry-CPT)
*Python, FastAI, Hugging Face*

Image classification models that identify blood diseases from blood smear images with over 90% accuracy, deployed as a [public demo on Hugging Face](https://huggingface.co/spaces/AustinL/HematoTech).

### [ClearSign](https://github.com/ZhuG07/ClearSign)
*React, Express, LLM APIs*

Paste in a lease, a job offer or a terms of service and get a plain-English summary, colour-coded highlights on the original text for risks, obligations, rights and deadlines, and an overall risk level tailored to whether you are a tenant, employee, consumer or student. Built at a hackathon.


