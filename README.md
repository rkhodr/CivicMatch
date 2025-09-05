# CivicMatch

A political engagement platform that matches constituents with local representatives based on their political views. Built for Boston area politicians.

## Features

- **Interactive Map**: Visual representation of the USA with focus on Boston
- **Political Questionnaire**: 6-question survey to assess political alignment
- **AI-Powered Matching**: Algorithm that matches users with politicians based on their responses
- **Boston Focus**: Curated list of local councilors, senators, and representatives
- **Modern UI**: Beautiful, responsive design with smooth animations

## Tech Stack

- **Frontend**: React with TypeScript
- **Backend**: Node.js with Express
- **Styling**: CSS3 with modern gradients and animations
- **Data**: Curated Boston political data with scoring system

## Quick Start

1. Install dependencies:
```bash
npm run install-all
```

2. Start the development servers:
```bash
npm run dev
```

3. Open your browser to `http://localhost:3000`

## How It Works

1. **Take the Quiz**: Users answer 6 political questions covering:
   - Economy
   - Healthcare
   - Environment
   - Education
   - Housing
   - Public Safety

2. **AI Matching**: The algorithm compares user responses to politician positions using a scoring system

3. **Get Results**: Users see politicians ranked by alignment percentage

## Boston Politicians Included

- Michelle Wu (Mayor)
- Ed Flynn (City Councilor, District 2)
- Frank Baker (City Councilor, District 3)
- Andrea Campbell (Attorney General)
- Lydia Edwards (State Senator)

## Project Structure

```
CivicMatch/
├── client/          # React frontend
├── server/          # Node.js backend
├── package.json     # Root package configuration
└── README.md        # This file
```

## Future Enhancements

- Real-time political data integration
- Expanded geographic coverage
- Voting record analysis
- Social sharing features
- Mobile app development
