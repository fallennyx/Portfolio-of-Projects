# My Portfolio of Projects

Hello! Welcome to my GitHub repository showcasing some of my projects. 
I am a graduating CS major. Besides that, I am also a member of the ANG. 
This is here to prove I can build things. With scale and capital, Id be a billionare with my ideas.

## Contact Details

- **GitHub:** (https://github.com/fallennyx)
- **LinkedIn:** (https://www.linkedin.com/in/emmanuelakanmu/)
- **Email:**  EDU: eakanmu@buffalo.edu Personal: 1eakanmu@gmail.com
## Languages & Skills

I'm proficient in a variety of languages and technologies, including:

Core stack: JavaScript, Python, C/C++, SQL • React.js, Next.js • Node.js, Flask, PHP • iOS/Swift

AI/ML: NLP, Machine Learning, Data Science • PyTorch, NumPy

Data & pipelines: Airflow • MySQL, MongoDB • Data Analysis, SQL

Cloud & DevOps: AWS, Google Cloud Platform, Docker

Design & product: UI/UX Design, Figma

Systems: Verilog, VHDL

Practices: Data Structures & Algorithms, Agile


# My Top Projects

## PropJigs

Repository: [PropJigs]([https://github.com/CSE370HCI/kinetic](https://github.com/fallennyx/PropJigs))

Description: PropJigs is an open, AI-first wholesale real-estate marketplace that connects wholesalers and cash buyers through standardized AI one-page briefs, a personalized Buy-Box feed, and commitment-gated details. We make underwriting fast, reduce low-quality noise, and surface deals that actually convert.

Problem
* Wholesalers are scattered across many paywalled or fragmented services; buyers waste time digging through unstructured listings.
* Existing marketplaces either gate supply behind high fees or act as principals (conflict of interest).
* New wholesalers lack an easy, low-cost place to list and reach buyers. The market is seeing a surge of new entrants who need a neutral, fast channel.
Solution / Product
* AI Briefs: canonical, machine-readable one-page summaries (ARV, repair estimate, comps, net profit, confidence).
* Open & Neutral Marketplace: free to list and browse → faster supply growth and network effects.
* Buy-Box Feed & Triage Mode: personalized, urgency-weighted feed that replaces search.
* Commitment Button + Reputation: non-monetary holds reveal full address and create accountability — penalties for ghosting.
* Partner-Ready API / White-Label: enterprise feed + webhooks for investor groups and title partners.

Tech Stack:
Frontend:
Framework: React with TypeScript
Routing: Wouter
State Management: TanStack React Query
UI Framework: Tailwind CSS with shadcn/ui component library
Build Tool: Vite
Backend:

Runtime: Node.js with Express.js
API Design: RESTful endpoints
Database: PostgreSQL using Drizzle ORM
Session Management: PostgreSQL storage with express-session
Authentication:

Method: Replit Auth with OpenID Connect integration

## PIC2FOOD 
REPO: https://github.com/fallennyx/Pic2Food/

Description: PIC2FOOD is a mobile-first recipe discovery application that uses AI-powered image recognition to identify ingredients from photos and suggest relevant recipes. The app allows users to take pictures of ingredients, automatically detect what they have available, and receive personalized recipe recommendations through integration with the FatSecret API.

Tech Stack:
Frontend
React + TypeScript with Vite
Wouter for routing
Shadcn/ui + Tailwind CSS for UI
TanStack Query for state/caching
PWA, mobile-first design

Backend:
Node.js + Express (TypeScript, ES modules)
REST API: image recognition, recipe search/details
Vite middleware for dev HMR

Features:
Camera → ingredient recognition
FatSecret API for recipes + nutrition
Tracks shown recipes to prevent repeats
Mobile-optimized recipe browsing

## BetterPerplexity
Repo: https://github.com/fallennyx/BetterPerplexity

Description: Betterperplexity is a React-based search app with a chat-like interface for internet queries using the Tavily API. It performs parallel searches (general + news), generates AI-powered answers with source citations, and supports exporting research as PNG cards or ZIP bundles. The project is incomplete due to API credit and inference costs, but the concept and architecture are in place.

Tech Stack:
Frontend
React 18 + TypeScript with Vite
Wouter for routing
shadcn/ui + Tailwind CSS (Radix UI primitives)
React Query + local state for state management

Backend
Node.js + Express (REST API proxy to Tavily)
Parallel search calls (general/news) + result processing
API endpoints for search + content extraction
Error handling + logging middleware
Database:
Drizzle ORM with PostgreSQL schema/migrations
Mostly in-memory storage for current state

Features:
Chat-like search UI
Tavily API integration (general/news search)
AI-powered answers with citations
Export results as PNG or ZIP bundles
Modern, accessible design system


## Folder Chat
Repo: https://github.com/fallennyx/FolderChat
Description: FolderChat is a React web app that connects Google Drive folders to an AI-powered chat system. Users sign in with Google, link a Drive folder, and can query their documents with AI responses and citations. It uses LlamaCloud for document indexing/processing and a Google service account for Drive access. Not completed due to Google OAuth app verification requirements.
Tech Stack:

Frontend
React 18 + TypeScript with Vite
shadcn/ui + Tailwind CSS (Radix UI primitives)
TanStack Query for state/caching
Google OAuth 2.0 via @react-oauth/google
Wouter for routing
Modular component structure (setup, chat, citations)

Backend:
Node.js 18+ + Express (TypeScript, ESM)
REST API: connect, status, chat, service account info
Centralized error middleware (JSON responses)
Vite middleware for hot reload in dev
Database:
Entities: users, pipelines (folder links), chat messages
In-memory storage fallback for dev/testing
Auth & Access:
Google OAuth 2.0 for user auth
Google service account for Drive API access
Users share folders with service account before indexing
Session-based auth with secure cookies

Features:
AI-powered Q&A over Google Drive docs
Citations in responses
Folder connection + sync via Drive API
Document indexing via LlamaCloud

Optional HuggingFace model integration

## Find a Mechanic

Repository(Private): [Find a Mechnaic](https://github.com/CSE370HCI/kinetic)

Description: Find a mechanic of FAM for short is a service based webpage and app with the goal of becoming a doordash and/or instacart of trades and services. As of right now we’re focusing on the mechanics trade due to it being the largest and having year round work.

This software has 3 core portions. A marketplace webpage for a shop to administer and delegate time, work, and resources internal to customer issues and communicate and do the entire workflow process with customers. The other two portions are an app that has two uses. 1st use is for a worker of the shop to have work delegated to them from the shop webpage that allows them to update on progress of a vehicle and a user facing app that allows them to find a shop of their desired niche by reviews. The user can interact with the shop from start to finish from the app.

As of right now FAM is nearly finished as its most basic core tenets. It still needs more features and some things built into it listed below.

Changes/builds depending on customer feedback
UI improvements (consider using UI library)
Build/expand database (better reporting and analytics)
Add to the calendar
bug/glitch fixing
Securing and consolidation of the code
potentially adding payment system
This is what we’re planning on for the foreseeable future as we attempt to start demoing with various shops and students to test out. As more issues trickle in we believe those will help build a better process.



Tools used:
- AWS
- React Native
- PHP
- MySQL,CSS3
- Expo

Academic Context
This project was developed as part of the curriculum for CSE302 at the University at Buffalo, providing hands-on experience with modern web development practices while implementing human-computer interaction design principles in a practical application. Due to this, Repository is private.






## ELO

Repository: [ELO by Team Kinetic](https://github.com/CSE370HCI/kinetic)

Description: Elo is a comprehensive social networking platform that combines dating app functionality with social media features. It enables users to connect, match with others, communicate, and share content within a community-focused environment.

Features:
- User Authentication - Login, registration, and password reset functionality
- Profile Management - View and edit user profiles
- Matching System - Swipe-based matching interface similar to dating apps
- Messaging - Real-time chat functionality with socket.io integration
- Social Connections - Friends, followers, and following management
- Content Sharing - Post creation and community content feeds
- Groups - Community group creation and management
- Filtering - Content and user filtering capabilities
- Match Management - View and manage your matches

Tools used:
- React.js 
- Socket.io
- REST API(backend communication)
- Progressive Web App (PWA) - Service worker implementation
- Component-based Architecture - Modular UI development

Academic Context
This project was developed as part of the curriculum for CSE370 at the University at Buffalo, providing hands-on experience with modern web development practices while implementing human-computer interaction design principles in a practical application. Due to this, Repository is private.


## Wealth Wise

Repository: [Wealth Wise](https://github.com/cse442-at-ub/fa24-semesterproject-the-academic-weapons)

Description: Wealth Wise is a financial assistant designed to help users analyze and manage their spending. By inputting financial data, users can gain insights into where their money is going and set goals to improve their financial health. Key features include transaction categorization, spending breakdowns, and projections for achieving savings goals. The app includes a user-friendly dashboard with interactive visualizations like pie charts and monthly spending comparisons.

Features:
- Input transactions with details such as name, amount, category, and date.
- View a categorized breakdown of expenses via pie charts.
- Monthly spending comparisons and trend analysis.
- Highlighted insights, such as the highest spending category.
- User settings for managing profiles, including password, username, and email changes.
- Support for recurring transactions and quick input features for convenience.

Tools used:
- React
- PHP


## Twitter Opposite Bot

Repository: [TwitterOppositeBot](https://github.com/fallennyx/TwitterOppositeBot))

Description: The Twitter Opposite Bot is an automated parody-generating Twitter bot that fetches tweets from influencers and posts humorous opposites or parodies. Using advanced natural language processing (NLP), the bot ensures entertaining and creative content generation. It fetches tweets, processes them for parody transformation, and posts the generated content back on Twitter automatically.

Features:
- Fetch tweets from influencers using the Twitter API.
- Generate creative and humorous parodies with NLP capabilities powered by Google Gemini AI API.
- Post the transformed content back to Twitter in real time.
- Seamless automation of the entire process using Tweepy for API integration.

Tools Used:
- Google Gemini AI API for generating parody content
- Tweepy and Twitter API 
- Python for backend automation


## Fits in Advance

Repository: [Fits in Advance](https://github.com/fallennyx/Fits-in-Advance)

Description: Using the weather data of the user-inputted city, our app uses DALL-E to create an image of a recommended outfit. Search results of similar outfits are provided as well. As of APR 2025, will be updating and improving this application due to advancments in AI image generation.

Tools used:
- CSS, HTML, and Javascript for the frontend
- Python and Flask for the backend
- Dall-E, Weather Info, and Serp Shopping Api
- SQLite Database

