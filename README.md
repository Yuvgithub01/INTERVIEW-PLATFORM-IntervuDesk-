<div align="center">

# 🚀 IntervuDesk

### Real-Time Technical Interview & Coding Assessment Platform

Conduct coding interviews with collaborative coding, live video communication, interview scheduling, and candidate evaluation — all in one platform.

---

![Next.js](https://img.shields.io/badge/Next.js-14-black)
![React](https://img.shields.io/badge/React-18-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![Clerk](https://img.shields.io/badge/Auth-Clerk-purple)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-green)
![Convex](https://img.shields.io/badge/Realtime-Convex-orange)
![Stream](https://img.shields.io/badge/Video-Stream-red)
![TailwindCSS](https://img.shields.io/badge/UI-TailwindCSS-cyan)

---

### 🎯 Built to Simulate Real Software Engineering Interviews

</div>

---

## 🌟 Project Overview

IntervuDesk is a modern technical interview platform designed to streamline coding interviews through an integrated environment that combines:

✔️ Live Video Interviews

✔️ Collaborative Coding Sessions

✔️ Real-Time Code Synchronization

✔️ Interview Scheduling

✔️ Recording Management

✔️ Candidate Assessment

✔️ Secure Authentication

✔️ Modern Dashboard Experience

The platform recreates the real-world technical interview process used by leading technology companies.

---

## 📸 Platform Highlights

| Feature | Description |
|----------|------------|
| 🎥 Live Interviews | HD video interviews using Stream SDK |
| 💻 Collaborative Coding | Real-time shared coding environment |
| 🔐 Secure Authentication | Clerk-based authentication and authorization |
| 📅 Interview Scheduling | Create and manage interview sessions |
| 🎬 Recording System | Store and review interview recordings |
| 👨‍💼 Interviewer Dashboard | Manage interviews and candidates |
| 👨‍💻 Candidate Dashboard | Access interviews and coding challenges |
| ⚡ Real-Time Updates | Convex-powered synchronization |

---

# 🏗️ System Architecture

```text
┌────────────────────────────────────────────┐
│                  Frontend                  │
│         Next.js + React + TypeScript       │
└────────────────────────────────────────────┘
                     │
                     ▼
┌────────────────────────────────────────────┐
│              Authentication                │
│                   Clerk                    │
└────────────────────────────────────────────┘
                     │
                     ▼
┌────────────────────────────────────────────┐
│             Business Logic Layer           │
│     Interview • Coding • Scheduling        │
└────────────────────────────────────────────┘
                     │
      ┌──────────────┼──────────────┐
      ▼              ▼              ▼

  Stream SDK      Convex DB      MongoDB

(Video Calls)   (Realtime Data)  (Storage)

      ▼              ▼              ▼

┌────────────────────────────────────────────┐
│              User Experience               │
│ Interviewers • Candidates • Admins         │
└────────────────────────────────────────────┘
```

---

# ✨ Core Functionalities

## 🔐 Authentication Module

- User Registration
- User Login
- Session Management
- Route Protection
- Role-Based Access Control
- Secure Authentication via Clerk

---

## 🎥 Video Interview Module

- HD Video Calls
- Audio Communication
- Participant Management
- Screen Sharing
- Interview Rooms
- Live Meeting Controls

---

## 💻 Collaborative Coding Module

- Monaco Editor Integration
- VS Code-like Experience
- Syntax Highlighting
- Multiple Programming Languages
- Real-Time Code Synchronization
- Live Collaboration

---

## 📅 Interview Scheduling Module

- Schedule Interviews
- Manage Upcoming Sessions
- Track Completed Interviews
- Generate Meeting Links
- Candidate Invitations

---

## 🎬 Recording Management Module

- Automatic Recording
- Recording Storage
- Interview Playback
- Performance Review
- Historical Records

---

## 📊 Dashboard Module

### Interviewer Dashboard

- Manage Interviews
- Review Recordings
- Monitor Candidates
- Create Sessions

### Candidate Dashboard

- Join Interviews
- Access Coding Challenges
- Track Interview Status
- Review Upcoming Sessions

---

# 🛠️ Technology Stack

<table>
<tr>
<td><b>Frontend</b></td>
<td>Next.js 14, React 18, TypeScript</td>
</tr>

<tr>
<td><b>Authentication</b></td>
<td>Clerk</td>
</tr>

<tr>
<td><b>Database</b></td>
<td>MongoDB, Mongoose, Convex</td>
</tr>

<tr>
<td><b>Video Communication</b></td>
<td>Stream Video SDK</td>
</tr>

<tr>
<td><b>Code Editor</b></td>
<td>Monaco Editor</td>
</tr>

<tr>
<td><b>Styling</b></td>
<td>Tailwind CSS, ShadCN UI, Radix UI</td>
</tr>

<tr>
<td><b>Language</b></td>
<td>TypeScript</td>
</tr>
</table>

---

# 📂 Project Structure

```bash
IntervuDesk
│
├── src
│   ├── app
│   ├── components
│   ├── actions
│   ├── hooks
│   ├── constants
│   ├── lib
│   └── models
│
├── convex
├── public
├── package.json
└── README.md
```

---

# 🎯 Key Achievements

✅ Secure Authentication System

✅ Role-Based Access Control

✅ Real-Time Video Communication

✅ Collaborative Coding Environment

✅ Interview Scheduling System

✅ Recording Management

✅ Modern Responsive UI

✅ Real-Time Synchronization

✅ Full-Stack Architecture

✅ Production-Ready Design

---

# 🚀 Future Enhancements

- AI Interview Evaluation
- Automated Feedback Reports
- Coding Performance Analytics
- Resume Analysis
- AI Question Generator
- Multi-Round Interview Workflow
- Recruiter Dashboard
- Organization Management

---

# 👨‍💻 Author

### Yuvraj Kumar

Full Stack Developer | Technical Interview Platform

Built with ❤️ using Next.js, TypeScript, Clerk, Convex, MongoDB, Stream SDK, Monaco Editor and Tailwind CSS.
