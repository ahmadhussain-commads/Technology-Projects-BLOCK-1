# 🧪 Task 4 — Network Latency & Bandwidth

### 1️⃣ On the server machine:
```bash
iperf3 -s
```
<img width="3024" height="4032" alt="WhatsApp Image 2026-10-24 at 7 59 18 PM" src="https://github.com/user-attachments/assets/3775e4d5-bca3-45d1-a7bb-56de980b220a" />

### 2️⃣ On the Raspberry Pi:
```bash
iperf3 -c <server-ip>
ping <server-ip> -c 30
```
<img width="4032" height="3024" alt="WhatsApp Image 2026-10-24 at 7 59 19 PM (1)" src="https://github.com/user-attachments/assets/2a7217e1-0c49-49b3-9f3f-9cfbc123589d" />

### 3️⃣ Record:
- Bandwidth
- Latency (min/avg/max)
- Packet loss

📁 Save:
- `results/iperf.txt`
- `results/ping.txt`
