# 🔗 URL Shortener with Analytics

## 📜 Overview
This is a full-stack URL shortener application that lets you:
- Create shortened links with optional custom shortcodes and expiry time.
- Track usage statistics, including the number of visits, referrers, geolocation, and timestamps.
- View a dashboard of all created short URLs and their click statistics.

The project consists of:
- **Backend**: REST API (Node.js + Express)
- **Frontend**: React + Material UI for user-friendly interactions.

---

## ✨ Features
✅ Shorten long URLs with optional expiry time and custom shortcodes.  
✅ Server-side validation and automatic shortcodes.  
✅ Detailed usage statistics (visit timestamps, referrers, geolocation).  
✅ Responsive UI built with Material UI.  
✅ Client-side validation and easy sharing of links.

---

## 🛠️ Tech Stack
**Backend**:
- Node.js, Express.js
- nanoid for short codes
- In-memory store (can switch to a database easily)

**Frontend**:
- React
- Material UI
- Axios for API calls

---

## 🚀 Getting Started

### 📂 Backend
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/url-shortener.git
   cd url-shortener/backend
