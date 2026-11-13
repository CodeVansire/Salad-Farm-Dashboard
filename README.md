# Salad-Farm-Dashboard
Real-time public dashboard for monitoring multi-PC Salad mining fleets. Tracks live power draw, earnings, electricity costs, and net profit with 24-hour charts.
# 🚀 Salad Fleet Dashboard

A real-time, public-facing web dashboard designed to monitor and track a multi-PC Salad mining fleet. Built with **HTML**, **Chart.js**, and **Supabase** for lightweight, serverless hosting on GitHub Pages.

## ✨ Features
- **Live Fleet Tracking:** View real-time power consumption (watts) and cumulative earnings across all connected mining rigs.
- **Profit Calculations:** Input your local electricity rate ($/kWh) to instantly calculate net profit and hourly profit margins.
- **24-Hour Rolling Charts:** Dual persistent charts tracking Earnings and Profit over 30-minute interval slots using browser local storage.
- **Mobile Friendly:** Fully responsive layout optimized for mobile screens (easily added as a home screen shortcut app).
- **Python Telemetry Script:** Automated background reporter script (`reporter.py`) to stream GPU metrics (`nvidia-smi`) straight to Supabase.

## 🛠️ Tech Stack
- **Frontend:** HTML5, CSS3, Chart.js (CDN)
- **Backend & Database:** Supabase (PostgreSQL REST API)
- **Telemetry:** Python (`requests`, `subprocess`)
