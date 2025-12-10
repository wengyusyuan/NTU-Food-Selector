# NTU Food Selector 🍜

A smart dining decision app combining **AI recommendations** and **multi-tag filtering** to help you decide what to eat around NTU.

Live demo: https://693979cd9ef4039b6c392ce7--ntufoodselector.netlify.app/

## Overview

As a student at National Taiwan University (NTU), choosing what to eat every day can be a constant dilemma. To solve this, I developed this Single Page Application (SPA) using **React**, focused on quickly surfacing suitable dining options based on your preferences, tags, and AI suggestions.

## Key Features

- 🤖 **AI Inspiration Helper**  
  Integrated with the **Gemini API**, allowing users to describe their cravings in natural language (e.g., "I just finished exams and want a treat"). The AI analyzes the database and offers personalized suggestion ideas.

- 🏷️ **Smart Multi-tag Filtering**  
  Implemented complex tagging logic where a single restaurant can belong to multiple categories (for example, both **"Taiwanese"** and **"Hot Pot"**), overcoming the limitations of traditional single-category systems.

- 🎲 **Anti-Duplicate Algorithm**  
  Built-in history tracking ensures users don't see the same suggestions repeatedly within a short period, providing a more diverse selection experience.

- 📱 **Responsive & Flat Design**  
  Built with **Tailwind CSS**, featuring a modern Flat Design interface optimized for both mobile and desktop.

- 📂 **Flexible Data Management**  
  Supports **CSV import/export** with a custom parser, enabling non-technical users to easily update the restaurant database.

## Tech Stack

- Frontend Framework: **React 18**  
- Styling: **Tailwind CSS**  
- AI Integration: **Google Gemini API (Free tier)**  
- Data Handling: **Custom CSV Parser**, **RegEx Classification**  
- Deployment: **Netlify**

## Technical Highlights

- **Regex Auto-Classification System**  
  An automated script parses unstructured "sub-category" text input (e.g., "Japanese Pork Cutlet") and uses regular expressions to categorize items into standardized tags.

- **Browser Cache Control**  
  Addressed common SPA caching issues on mobile browsers by implementing version detection (**v2.0**) and a forced-refresh mechanism, ensuring users always access the most up-to-date data without manual cache clearing.

- **Serverless Architecture**  
  Designed as a pure frontend app that leverages **localStorage** to securely store user API keys and preferences, delivering personalized features without maintaining a backend server.


---

Created by **Yu-Syuan Weng(翁譽瑄)** & **Gemini 3 Pro**  
Food list curated by **JinJin**
