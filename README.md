# 🕵️‍♂️ API Scraping Simulation (Facebook‑Style) with Protection Mechanism
This project simulates personal‑data scraping through a web interface, similar to the attacks experienced by platforms like Facebook.
Its goal is to demonstrate how easily an unprotected API can be exploited, while also showing the impact of simple countermeasures such as rate limiting.

---

## 🎯 Educational Objectives
- Simulate a mass‑scraping attack on a public API.
- Demonstrate the effect of protection mechanisms (e.g., rate limiting per second).
- Understand the risks of improper API configuration.
- Raise awareness of API security and the importance of proper safeguards.

## 🛠️ Technologies Used

- HTML5 / CSS3
- Vanilla JavaScript
- Tailwind CSS (CDN version)

## ⚙️ Features
### 🔎 Scraping Simulation

- Automatic generation of random user profiles
  → name, email, phone number, etc.
- Dynamic insertion of scraped data into an HTML table.
- Event logging with timestamps (scraping actions, attempts, blocks…).
  
### 🛡️ Protection Mechanism (Rate Limiting)

- Option to enable or disable scraping protection.
- When enabled:
- Blocks more than 5 requests per second.
- Logs blocked requests.
- Automatic reset of internal counters whenever the protection is toggled.
