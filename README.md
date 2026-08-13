# KMeansClustering
This is a demo for KMeans clustering.

**Project Structure**

KMeansClustering/  
│  
├── kmeans_app.py  
├── prompt_generator.py  
├── video_generator.py  
├── config.py  
├── requirements.txt  
├── .env  
└── assets/  

This Streamlit app would:  
  
1. Accept lyrics and other inputs from the user.
2. Use an LLM to convert the lyrics into a sequence of cinematic scene prompts.
3. Send those prompts to a text-to-video model or API.
4. Poll until the video is ready.
5. Display or download the generated video.

The overall architecture looks like this:  
User  
   │  
   ▼  
Streamlit UI  
   │  
   ▼  
LLM (Prompt Engineering)  
   │  
   ▼  
Scene Breakdown  
   │  
   ▼  
Video Generation API  
   │  
   ▼  
Generated MP4  
   │  
   ▼  
Display in Streamlit  

