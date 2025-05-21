Visual vs Voice – An AI-Powered Platform 
Visual vs Voice is a full-stack, next-gen AI web application that allows users to generate images using voice prompt as well as text prompts and engaging animated videos from text using advanced AI models. Built using modern web technologies like Next.js, Tailwind CSS, and Python integrations, V3 Visual Vs Voice seamlessly combines AI-powered story generation, image creation, voiceovers, and animation into one cohesive platform. 

  [Watch Demo.mp4 on Google Drive]
[Demo Video Link](https://drive.google.com/file/d/1JFDlH2plcEfJ3RpHahIXKTziQox4D88l/view?usp=drive_link)

Note: The video was too large for GitHub, so it's hosted on Google Drive.
Features 
Input Options 	 
•	- Text-to-Speech 
•	- Speech-to-Text 
•	- Text-to-Image 
•	- Text-to-Animation Video  
 
Complete AI Storytelling Pipeline 
1.	Story Generation (Gemini API) 
2.	Voiceover Creation (Eleven Labs API) 
3.	Image Generation per Scene (Monster API) 
4.	Image Animation (AI Video API) 
5.	Final Video Compilation (FFmpeg) 
 
UI & Experience 
•	- Inspired by Leonardo AI, Haiper AI, and Kling AI 
•	- Modern UI with Dark Mode and Light Mode, animated interactions, and gradient UI elements • - Colorful, child-friendly but creative and professional design 
 
Authentication 
•	- Simple username/password login (no email) 
•	- Secure sessions with cookie-based authentication 
 
Tech Stack 
Frontend 
•	- Next.js (App Router, React Server Components) 
•	- Tailwind CSS  
•	- Framer Motion for animations 
Backend 
•	- Next.js API Routes 
•	- MongoDB Atlas (user data, stories, assets) 
•	- Python AI Scripts integrated via backend 
•	- FFmpeg for video merging 
   
AI Integrations 
Feature API Used 
Story Generation 	Gemini 
Voiceover 	              Eleven Labs 
Image Generation 	Monster API 
Animation 	               AI Video API 
Video Compilation 	FFmpeg (local) 
 
Run the Development Server
 npm run dev 
Run Python Backend (for AI Scripts) python app.py (inside /backend or /ai-scripts folder) 
Project Structure 
 
Visual vs Voice/ 
├── app/components           # Next.js App Router pages 
├── styles/                              # TailwindCSS and custom styles 
├── lib/                                    # Utility functions 
├── public/                             # Static assets 
├── scripts/                             # Python scripts for AI tasks 
├── ffmpeg/                            # FFmpeg video processing 
├── database/                        # MongoDB models and config 
├── .env.local                       # Environment variables 
├── .env                                # Environment variables 
└── README.md 
 
Contact 
Authors: Anam Saleem 
Email: anamsaleemqureshii@gmail.com        
        
 
 

