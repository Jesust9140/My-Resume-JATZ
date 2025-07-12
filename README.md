# Jesus T. Portfolio - MERN Stack

A modern portfolio website built with the MERN stack (MongoDB, Express, React, Node.js) featuring a clean design and responsive layout.

## Features

- **React Frontend**: Modern React components with hooks
- **Express Backend**: RESTful API serving portfolio data
- **Dark Mode**: Toggle between light and dark themes
- **Responsive Design**: Works on all device sizes
- **Tailwind CSS**: Beautiful styling with utility classes
- **Tab Navigation**: Switch between Work, Education, and Skills

## Tech Stack

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB (optional)
- **Development**: Concurrently for running both servers

## Project Structure

```
My-Resume-JATZ/
├── backend/
│   ├── server.js          # Express server
│   ├── package.json       # Backend dependencies
│   └── .env              # Environment variables
├── frontend/
│   ├── src/
│   │   ├── components/    # React components
│   │   ├── App.js        # Main App component
│   │   └── index.css     # Tailwind CSS imports
│   ├── public/
│   │   └── images/       # Static images
│   └── package.json      # Frontend dependencies
└── package.json          # Root package.json
```

## Installation

1. **Install all dependencies**:

   ```bash
   npm run install-all
   ```

2. **Set up environment variables** (optional):
   ```bash
   # backend/.env
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/portfolio
   NODE_ENV=development
   ```

## Running the Application

1. **Development mode** (runs both frontend and backend):

   ```bash
   npm run dev
   ```

2. **Run backend only**:

   ```bash
   npm run server
   ```

3. **Run frontend only**:
   ```bash
   npm run client
   ```

## API Endpoints

- `GET /api/portfolio` - Get basic portfolio info
- `GET /api/experience` - Get work experience
- `GET /api/education` - Get education history
- `GET /api/projects` - Get project list
- `GET /api/skills` - Get skills list

## Deployment

1. **Build the frontend**:

   ```bash
   npm run build
   ```

2. **Deploy backend** to your preferred hosting service (Heroku, Netlify, etc.)

3. **Deploy frontend** build folder to static hosting

## Customization

- Update the data in `backend/server.js` to reflect your own information
- Modify the React components in `frontend/src/components/`
- Customize styling by editing Tailwind classes
- Add new API endpoints for additional features

## Features to Add

- Contact form with email functionality
- Blog section
- Authentication for admin features
- MongoDB integration for dynamic content
- Image optimization
- SEO improvements

## Contact

- **Email**: jesust9140@gmail.com
- **LinkedIn**: [Jesust9140](https://www.linkedin.com/in/Jesust9140)
- **GitHub**: [Jesust9140](https://github.com/Jesust9140)



 RECOMMENDED CERT ORDER
1. AZ-204 – Azure Developer Associate
💡 Foundation: Cloud-native app development + deploy MERN stack on Azure

Learn App Services, Functions, CosmosDB, CI/CD, etc.

Helps with real-world deployment & API security
🕒 4–6 weeks (start here)

2. eJPT v2 – Junior Penetration Tester (Red Team)
💡 Learn how hackers think: Recon, exploit, privilege escalate

Reinforces network, OS, and app vulnerabilities

Builds your mindset for secure coding and defensive testing later
🕒 3–5 weeks (right after AZ-204)

3. Blue Team Level 1 (BTL1)
💡 Defensive security: Logging, SIEM (Splunk), detection, incident response

Complements eJPT by teaching you how to detect what you hacked

Preps you for real-world security analyst or DevSecOps tasks
🕒 4–6 weeks

4. SC-200 – Microsoft Security Operations Analyst (Optional but 🔥)
💡 Azure Defender + Sentinel: Threat detection in the cloud

If you're going deeper in cloud security + Blue Teaming
🕒 3–4 weeks (optional — take after BTL1 if you're headed toward SOC roles)

