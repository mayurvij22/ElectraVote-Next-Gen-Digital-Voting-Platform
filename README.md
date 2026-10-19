<div align="center">

# 🗳️ ElectraVote: Digital Polling Platform

**Create polls, cast one vote per poll and watch the results update. Built with the MERN stack and Redux.**

![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Redux](https://img.shields.io/badge/Redux%20Toolkit-764ABC?logo=redux&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![CI](https://img.shields.io/badge/CI-GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)

### [🌐 Live demo](https://poll-app-delta.vercel.app)

</div>

---

## ✨ Features

- **Sign up and log in** with JWT authentication
- **Create polls** with multiple options, and **delete** your own polls
- **Vote** on any poll, **one vote per user per poll** (enforced on the server)
- **Change your mind**: remove your vote and vote again
- **Results** shown as circular and horizontal progress bars
- Browse all polls on the homepage, or open a single poll at `/polls/:pollId`
- Global state with **Redux Toolkit**, and toast notifications
- GitHub Actions workflow for Node.js CI

## 📡 API (`/api/v1`)

| Method | Endpoint | Description |
|:---:|---|---|
| `POST` | `/user/signup` · `/user/login` | Authentication |
| `GET` | `/polls/fetchAllPolls` | List all polls |
| `POST` | `/polls/fetchRequiredPoll` | Get a single poll |
| `POST` | `/polls/createPoll` | Create a poll |
| `DELETE` | `/polls/deletePoll` | Delete a poll |
| `POST` | `/polls/castVote` | Vote on an option |
| `DELETE` | `/polls/removeVote` | Remove your vote |

## 🚀 Run locally

```bash
git clone https://github.com/mayurvij22/ElectraVote-Next-Gen-Digital-Voting-Platform.git
cd ElectraVote-Next-Gen-Digital-Voting-Platform
```

`server/.env`:

```env
PORT=4000
DB_URL=your_mongodb_uri
JWT_SECRET=a-long-random-string
```

Frontend `.env` (repo root):

```env
REACT_APP_SERVER_BASE_URL=http://localhost:4000   # the app appends /api/v1
```

```bash
cd server && npm install && npm run dev
cd .. && npm install && npm start      # http://localhost:3000
```

## 🛠️ Tech stack

| Layer | Technology |
|---|---|
| Frontend | React (CRA), Redux Toolkit, React Router, Axios, react-hot-toast |
| Backend | Node.js, Express, Mongoose, JWT, cookie-parser, Socket.io |
| Database | MongoDB |
| CI and hosting | GitHub Actions, Vercel |

---

<div align="center">

Made by **[Mayur Patil](https://github.com/mayurvij22)**

</div>
