# Study Buddy: A Socratic AI Tutor
When studying, it would be nice to have a helper who can help you understand how to think about the problems you are confronting; however, a personal teaching assistant isn’t always by your side - until now. 

Rather than merely offering answers, SocraticTA actively guides students through **thoughtful dialogue**, encouraging **exploration of concepts** and enabling them to **think critically through their own efforts**. Inspired by Plato’s Socratic method and informed by extensive research into classical texts and modern teacher resources, we designed our model to emulate proven questioning techniques. This environment empowers students to achieve deeper conceptual mastery and confidence, allowing them to provide more targeted and effective support.

### Take a look at our 3 minute pitch video!
https://github.com/user-attachments/assets/33271349-664c-4929-ab7c-d9bf5f0f4dca

## Features
- An LLM assistant who will never simply give you answers to your questions, but instead guide you to find the answers yourself.
- A detailed context window that will feed the AI with all relevant context to your situation. Also includes PDF parsing for course materials.
- A self mastery tracker that outlines 5 generated essential questions the user must answer to understand the solution to their problem.
- Popup buttons for generating summaries and hints for the conversation.

## Tech Stack
Frontend: The user interface is built with **React**, using **Vite** for a fast development experience. The design is handled with **Bootstrap** and **React-Bootstrap**, while navigation is managed by **React Router Dom**.

Backend: The server is a **Node.js** application powered by **Express.js**. It includes **Express-Session** for user authentication and **Bcrypt** for secure password hashing. The server can also handle file uploads using **Multer**.

AI & Document Processing: The application integrates with **Google's Generative AI API services**. It uses **Tesseract.js** for Optical Character Recognition (OCR) and **PDF.js** to process PDF documents, allowing it to extract information from various file types.

## Setup
npm install;  
npm run dev;  
open local host link

## Credits
Jacob Liang - Junior at Northwestern University

Grant Miranda - Senior at Northwestern University

Xiantong Zhao - Masters at Northwestern University

Hongyuan Xu - Masters at Northwestern University
