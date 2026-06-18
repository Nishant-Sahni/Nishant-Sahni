# 👋 Hello, I'm Nishant Sahni


---

## 🎓 About Me

Computer Science & Engineering undergraduate at **IIT Ropar**, India. Aspiring **web developer** with a great passion for **Full-Stack Development** , building **Automation Workflows** and **high-performance computing**.


---

## 🏆 Projects & Contributions

### 1. FMP: Fleet Management Platform
Stack- ASP.NET + Flutter + PostgreSQL

FMP is a full-stack logistics dispatch system that replaces the ad-hoc, WhatsApp-driven coordination of Indian freight, where jobs go to whoever calls first regardless of fairness or experience, with an automated, role-aware marketplace. It brings database-grade concurrency control and real-time synchronisation to a high-volume coordination problem that today runs almost entirely on informal phone calls.

**Technical Features**

- A single Flutter codebase serves five roles (Sender, Driver, Fleet Owner, Union, SysAdmin) behind role-based routing, backed by a layered ASP.NET Core 8 API over PostgreSQL so the whole marketplace lives in one install.
- A two-tier fairness engine offers union-approved shipments to drivers in seniority order, giving every eligible driver a fair, sequential turn rather than a race to respond.
- Concurrent claims on a shipment are resolved atomically at the database layer so exactly one trip is created, with expired offers cascading to the next driver via a background worker.
- A SignalR hub propagates every state change to all connected clients in real time, keeping senders, drivers, and admins continuously in sync.
- Full operational lifecycle is covered: shipment tracking, GPS and event-logged trips, bulk fleet and vehicle management, and a SysAdmin layer with live metrics, audit logs, and manual dispatch overrides.
- Security and integrity rest on stateless JWT plus Google OAuth and rate-limited email OTP, a UUID-keyed schema with constraints, triggers, and an immutable audit trail, deployed live on Vercel, Render, and Neon.

🔗 **Live:** [fmp-dep.vercel.app](https://fmp-dep.vercel.app/)

### 2. PED (Public Entry Device)

PED is a Next.js progressive web app that digitizes IIT Ropar's campus entry and exit logging, replacing the manual paper register at the gate. It is relevant because it turns an everyday institutional security and accountability problem into structured, auditable, real-time data at scale.

- Built on Next.js 15 (App Router) and React 19, deployed on Vercel as an installable PWA with offline support and push notifications.
- Implements a one-time QR workflow where gate-side codes are written to Firebase Realtime Database, then validated, consumed, and deleted on scan to prevent reuse.
- Models movement as a stateful round-trip in Firestore, with a single record capturing both departure and return to enable live "currently outside" detection.
- Secures access through Google OAuth scoped to the institute domain, role-based routing, and hardened HTTP headers (CSP, X-Frame-Options, nosniff).
- Surfaces an admin analytics dashboard (Recharts) with inside/outside, branch-wise, year-wise, and temporal trend insights derived from entry-number conventions.
- Automates compliance via a scheduled Vercel cron that emails students with incomplete entries and a daily summary to administrators.

### 3. Aarohan 2025

Annual sports fest of IIT Ropar. Role: **Web Development Co-Head**.

- Leading the web team for the fest
- Designed responsive UI/UX and integrated real-time event data via Google Cloud API

🔗 [Website](https://iitrpr.ac.in/aarohan)

### 4. VDAT 2025 (VLSI Design and Test Conference)

- Developed and maintain the conference website
- Implemented event registration and abstracts management

🔗 [GitHub](https://github.com/AyushTyagi2/VDAT) · [Conference](https://vdat.org.in)

### 5. Compression Analysis (Course Project)

- Collaborated on a C-based text and image compression system
- Implemented Huffman Coding, Run-Length Encoding, and LZW with dynamic hash tables
- Built a BMP image compressor and selective RLE encoder for images and text
- Integrated efficient file I/O and validated on sample files, achieving high compression ratios

🔗 [GitHub](https://github.com/Nishant-Sahni/CS201_Project)

### 6. Analysis of Social Networks (Course Project)

- Designed algorithms for leader identification and missing-link prediction in social impression networks
- Applied matrix methods and graph metrics using Python and network analysis libraries

🔗 [GitHub](https://github.com/Nishant-Sahni/Analysis-of-Social-Networks)

---

## 🛠️ Technical Skills

| Domain | Tools & Languages |
| --- | --- |
| **Web & App Development** | Flutter · ASP.NET Core · Streamlit · PostgreSQL · React.js · Next.js · Firebase · Tailwind CSS · Material UI · PWA · HTML/CSS |
| **Cloud & Hosting** | AWS · Docker · Vercel · Snowflake |
| **HPC & Parallel** | OpenMPI · Schedgen · CUDA · HIP · GPU Programming |
| **Automation & Data Engineering** | n8n · Python · SQL · Pandas |
| **Languages** | Python · JavaScript · C · C++ · RISC-V32 |
| **Mathematics** | Game Theory · Probability · Discrete Math · Linear Algebra · Calculus |


---

## 🎖️ Achievements

- **JEE Advanced 2023:** All India Rank **1777**
- **Hackathon Winner:** IIT Ropar Overnight Hackathon (Software Community)
- **Debate Champion:** Medals in inter-college parliamentary debates

---


## 📚 Coursework Highlights

 Operating Systems, Software Engineering, Game Theory, Theory of Computation, Computer
Networks, Databases, Programming Paradigms & Pragmatics, Computer Architecture, Data Structures, Probability &
Statistics, Linear Algebra

---
## 📫 Connect

- 🔗 [LinkedIn](https://www.linkedin.com/in/nishant-sahni-a7b01130a)
- 📧 [nishantsahni04@gmail.com](mailto:nishantsahni04@gmail.com)
- 🐙 [GitHub](https://github.com/Nishant-Sahni)

---

✨ *More projects and links coming soon. Stay tuned for additional showcases of my work in web development, HPC, and digital systems.*
