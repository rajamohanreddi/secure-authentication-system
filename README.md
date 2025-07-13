# secure-authentication-system

1️⃣ API Performance Monitor
📌 Description A Flask-based system that periodically monitors the health and performance of any given API. Data is stored in SQLite and visualized via Grafana dashboards.

🧪 Technologies Used

Python (Flask, Requests)

SQLite

Grafana

🎯 Key Features

Monitors API response times, status codes, and error rates

Stores metrics in SQLite for analysis

Provides REST endpoints to trigger monitoring and retrieve logs

Grafana dashboards visualize performance trends and anomalies

📈 Outcome DevOps engineers can detect latency spikes, error bursts, and trends over time. Enables proactive maintenance and SLA monitoring.

2️⃣ Real-Time Stock Market Dashboard
📌 Description An interactive dashboard that fetches and displays live stock market data using Streamlit. Offers intraday analysis with candlestick charts and key financial indicators.

🧪 Technologies Used

Python (Streamlit, Pandas, Plotly)

Alpha Vantage API or Yahoo Finance

Requests

🎯 Key Features

Real-time data fetching and auto-refresh capability

Candlestick chart visualization using Plotly

Displays current price, % change, volume, and open/close metrics

Extensible to multiple tickers or timeframes

📈 Outcome Useful for financial analysts, traders, or portfolio managers to monitor live prices and trends for decision-making.

3️⃣ Secure Authentication System
📌 Description A robust login and registration flow with encrypted password storage and JWT-based session control. Built on Flask and PostgreSQL with best practices in security.

🧪 Technologies Used

Python (Flask, PyJWT, bcrypt)

PostgreSQL

.env for secret management

🎯 Key Features

Passwords hashed using bcrypt before storage

JWTs for stateless authentication and session expiry

Protects routes with token verification

PostgreSQL used for persistence and user identity

📈 Outcome Provides secure access control for any web application, ready to scale with role-based access or multi-factor authentication.
