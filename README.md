# 🛡️ Real-Time Honeypot Monitoring System

## 📌 Project Overview

The **Real-Time Honeypot Monitoring System** is a cybersecurity project designed to simulate attacker activity, capture malicious actions, and visualize security events through a centralized monitoring dashboard.

The project uses a **Cowrie SSH Honeypot** to mimic a vulnerable Linux server, allowing security administrators to observe attacker behavior without exposing actual production systems.

All captured events are collected, stored, and visualized using modern observability tools, providing real-time insights into suspicious activities.

---

## 🎯 Objectives

* Detect and monitor unauthorized access attempts.
* Capture attacker commands and login attempts.
* Analyze attacker behavior in a controlled environment.
* Visualize security events through a dashboard.
* Demonstrate practical cybersecurity monitoring techniques.

---

## 🏗️ Architecture

```text
Attacker VM (Ubuntu)
192.168.0.2
        │
        ▼
Cowrie SSH Honeypot
192.168.0.4:2222
        │
        ▼
Grafana Alloy
        │
        ▼
Loki Log Storage
        │
        ▼
Grafana Dashboard
```

---

## 🖥️ Infrastructure

### Virtual Machines

| VM             | IP Address  | Purpose                            |
| -------------- | ----------- | ---------------------------------- |
| Attacker VM    | 192.168.0.2 | Simulate attacker activity         |
| Real Server VM | 192.168.0.3 | Production-like web server         |
| Honeypot VM    | 192.168.0.4 | Cowrie Honeypot + Monitoring Stack |

---

## 🔧 Technologies Used

* Ubuntu Server
* Cowrie Honeypot
* Grafana Alloy
* Loki
* Grafana
* Nginx
* SSH

---

## 🚀 Features

### SSH Honeypot

* Simulated SSH server
* Captures login attempts
* Records attacker commands
* Logs attacker sessions

### Real-Time Monitoring

* Centralized log collection
* Security event visualization
* Login attempt tracking
* Attack timeline analysis

### Decoy Web Server

* Professional banking-style website
* Hosted on port 8080
* Access logging enabled
* Demonstrates web-based deception techniques

---

## 📊 Dashboard Capabilities

The Grafana dashboard provides:

* Real-time security event monitoring
* Login attempt statistics
* Attack activity timeline
* Live attack logs
* Security event visualization

---

## 🔍 Demonstration Workflow

1. Attacker connects to the honeypot using SSH.
2. Cowrie records all actions.
3. Alloy collects generated logs.
4. Loki stores security events.
5. Grafana visualizes attacker activity in real time.

---

## 🛡️ Security Learning Outcomes

This project demonstrates:

* Honeypot deployment
* Threat monitoring
* Log aggregation
* Security visualization
* Attack analysis
* Defensive cybersecurity practices

---

## 📸 Screenshots

Add screenshots here:

* Infrastucture
  <img width="1024" height="593" alt="image" src="https://github.com/user-attachments/assets/bbcd5f1e-9a78-49d0-8714-0a674ebdf07d" />

* Real Server Web Page
  <img width="1915" height="1005" alt="image" src="https://github.com/user-attachments/assets/f6d2d037-f917-4db3-847d-616c9296426d" />

* Fake SSH Server
  <img width="1915" height="928" alt="image" src="https://github.com/user-attachments/assets/6088c98b-07e0-4361-a2a2-f98363ae8f03" />

* Grafana Dashboard
  <img width="1920" height="1000" alt="image" src="https://github.com/user-attachments/assets/9efbf4d0-9b07-41ea-b3e0-569f933b8e44" />
  <img width="1908" height="628" alt="image" src="https://github.com/user-attachments/assets/58d92833-8b48-49ba-a5ec-f91a2dc216af" />

  

---

## 👩‍💻 Author

**Chand Parveen**

B.Tech Computer Science Engineering

Cybersecurity & DevOps Enthusiast

---

## 📄 License

This project is developed for educational and learning purposes.
