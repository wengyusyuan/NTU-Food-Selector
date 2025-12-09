NTU Food Selector 🍜

A smart dining decision App combining AI recommendations and multi-tag filtering mechanisms.
https://69384dfa08336743885accce--ntufoodselector.netlify.app/

Overview

As a student at National Taiwan University (NTU), the daily dilemma of "What should I eat?" is a constant struggle. To solve this pain point, I developed this Single Page Application (SPA) using React. Unlike generic randomizers, this project integrates Google Gemini AI to provide personalized recommendations based on the user's mood, featuring a robust multi-tag filtering system.

Key Features

🤖 AI Inspiration Helper: Integrated with the Gemini API, allowing users to describe their cravings in natural language (e.g., "I just finished exams and want a treat"). The AI analyzes the database to recommend the perfect spot with a witty reason.

🏷️ Smart Multi-tag Filtering: Implemented complex tagging logic where a single restaurant can belong to multiple categories (e.g., both "Taiwanese" and "Hot Pot"), solving the limitations of traditional single-category filtering.

🎲 Anti-Duplicate Algorithm: Built-in history tracking ensures users don't see the same suggestions repeatedly within a short period, offering a more diverse selection experience.

📱 Responsive & Flat Design: Built with Tailwind CSS, featuring a modern Flat Design interface that is perfectly optimized for both mobile and desktop experiences.

📂 Flexible Data Management: Supports CSV import/export with a custom-built parser, enabling non-technical users to easily update the restaurant database.

Tech Stack

Frontend Framework: React 18

Styling: Tailwind CSS

AI Integration: Google Gemini API (Free tier)

Data Handling: Custom CSV Parser, RegEx Classification

Deployment: Netlify

Technical Highlights

Regex Auto-Classification System:
Developed an automated script that parses unstructured "sub-category" text input (e.g., "Japanese Pork Cutlet"). It uses Regular Expressions to automatically categorize items into standardized tags like "Japanese" or "Main Course," significantly reducing manual data entry effort.

Browser Cache Control:
Addressed common SPA caching issues on mobile browsers by implementing version detection (v2.1) and a forced-refresh mechanism, ensuring users always access the most up-to-date data without manual cache clearing.

Serverless Architecture:
Designed a pure frontend architecture leveraging localStorage to securely store user API Keys and preferences, achieving personalized features without the overhead of maintaining a backend server.

Screenshots

(Recommended: Add 2-3 screenshots here, such as the Main View, Filter View, and AI Recommendation Result)

Created by Yu-Hsuan Weng & Gemini 3 pro
Food list curated by JinJin
