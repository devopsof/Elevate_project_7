# Task 7 – Monitoring with Netdata

Steps:
1. Run Netdata in Docker:
   docker run -d --name=netdata -p 19999:19999 netdata/netdata

2. Open http://localhost:19999 in a browser to view real-time system metrics.

3. Take screenshots of dashboard and charts, save them in screenshots/ folder.

Repository Structure:
.
├── screenshots/
│   ├── dashboard.png
│   └── cpu.png
└── README.md

Outcome:
- Monitored CPU, memory, disk, network, and containers in real time.
- Dashboard accessible at port 19999.
