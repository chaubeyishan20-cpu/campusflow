# Hackathon (CampusFlow) — Frontend

React + TypeScript frontend for the **CampusFlow** hackathon project: an all-in-one campus companion for students and event organizers.

> This repo is part of the original hackathon submission. The current, maintained version lives in the local **CampusFlow** project.

## Features

- Event discovery & registration
- Crowd-sourced heat map monitoring (`Heatmap.js`, `CrowdMonitor`)
- One-tap **panic/emergency** button (`PanicButton`, `EmergencyContext`)
- QR-based event check-in (`QRScanner`)
- Event payments (`Payment`)
- Polls, admin control panel, and a demo dashboard

## Getting Started

```bash
npm install
npm start        # -> http://localhost:3000
```

Copy `.env.example` to `.env` and set your Supabase URL / anon key.

## Stack

Create React App · TypeScript · Supabase · React Context · Chart.js-style heatmap

---
Built for a campus hackathon by [@chaubeyishan20-cpu](https://github.com/chaubeyishan20-cpu).