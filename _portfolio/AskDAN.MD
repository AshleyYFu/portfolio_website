---
title: "ASK D.A.N. - A Daily Assistant for Nutrients"
excerpt: "An edge computing, self-hosting webapp for calorie and nutrition tracking powered by Gemini AI."
header:
  teaser: assets/img/DAN1.jpg
   
---

## About
This project originated during my summer internship when I became interested in tracking my nutrition while body-building. Since catered dishes and home made meals (especially if you're like me who throws any food into the pan) often lacked calorie counts or nutritional breakdowns, making it difficult to monitor my diet. Therefore, I envisioned a tool that could analyze food directly from an image.

This project is created for *Qualcomm's ML Hackathon*. The models are designed and optimized for the Snapdragon Xelite chips.

My team and I developed a web application powered by a locally hosted Gemini model running Gemma 3. The system integrates image captioning with a retrieval-augmented generation (RAG) pipeline to extract data from an open-source nutrient database. Users can create accounts, log their meals, and automatically generate nutritional reports that are saved for future reference.

**Frontend**: User interface created using *Streamlit* and connects to the sqlite3 database for user data storage.

**Backend**: Vectors are embedded in a FAISS index and uses CLIP vision model to process image data for querying. Vectors within the index is associated with an unique id to locate them within the database hosted by sqlite3 database for efficient retrieval and access.

## Skills
* Edge computing with open-source AI models
* Web application development and deployment
* Retrieval-augmented generation (RAG) pipeline integration
* Database-backed user account and logging system

# Demo Video
<!-- This video demonstrates the smooth and precise line tracking. 
<video controls src="assets/img/Maze_Solver_Demo.mp4" title="Title" width="400" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></video> -->

# Credits
**Qualcomm** 2025 Summer HaQathon

{% include gallery %}
