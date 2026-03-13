====================================================
  TutorConnect — Local Network Platform
  Version: 1.0
====================================================

summary
─────────────
TutorConnect is a local network tutor booking platform.
Students nearby can find tutors, book sessions, and ask
study questions. Tutors earn side income. Parents can
monitor their child's sessions. Monisha S has full admin
control over everything.


HOW TO ACCESS FROM OTHER DEVICES (Same WiFi)
─────────────────────────────────────────────
- All devices must be on the SAME WiFi network
- Open a browser on their phone/laptop
- Go to: http://YOUR-IP-ADDRESS:3000
  (Your IP is shown in the terminal when server starts)
- Works on any device: phone, tablet, laptop


PAGES
─────
/            → Browse tutors, search, book sessions
/dashboard   → Students track their bookings & question.


PRICING STRUCTURE
─────────────────
Budget tutors (school/basic):   ₹50  – ₹100/hr
Mid-range (board exams):        ₹150 – ₹500/hr
Premium (JEE/NEET/FAANG):       ₹500 – ₹1000/hr


ADMIN CAPABILITIES :
────────────────────────────────────
✓ View and manage ALL bookings (accept/decline/add notes)
✓ Reply to student questions
✓ Add, edit, suspend, or remove tutors
✓ View and manage all students
✓ Moderate reviews
✓ Log and resolve support issues
✓ Change platform settings (commission, toggles)
✓ Change admin password


DATA STORAGE
────────────
All data is stored in: data/db.json
This file is updated automatically when you use the app.
Back up this file regularly to keep your data safe.


PROJECT STRUCTURE
─────────────────
tutorconnect/
├── server.js              ← Main server (Node.js + Express)
├── package.json           ← Project config & dependencies
├── data/
│   └── db.json            ← All platform data (tutors, bookings, etc.)
├── public/
│   ├── css/style.css      ← All styling
│   ├── js/main.js         ← Shared JS utilities
│   └── pages/
│       ├── home.html      ← Browse tutors (student-facing)
│       ├── dashboard.html ← Student session tracker
│       └── admin.html     ← Admin panel (Monisha S only)
├── START_WINDOWS.bat      ← Start server on Windows
└── START_MAC_LINUX.sh     ← Start server on Mac/Linux


TECH STACK
──────────
Backend:  Node.js + Express.js
Frontend: HTML5, CSS3, Vanilla JavaScript
Database: JSON file (db.json) — no database server needed
Network:  Runs on port 3000, accessible on local WiFi

====================================================
   by Monisha S 
====================================================
