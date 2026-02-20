# Weatherflow
🌦️ n8n Telegram Weather Bot

A lightweight weather automation workflow built using n8n, Telegram Bot API, and OpenWeatherMap API.

This project allows users to retrieve real-time weather information for any city directly through Telegram.

🚀 Features

📲 Fetch weather using Telegram messages

🌍 Real-time data from OpenWeatherMap API

🌡️ Temperature in Celsius (Metric units)

💧 Humidity details

☁️ Weather condition description

⚡ Fully automated using n8n

🏗️ Architecture Overview

Telegram → n8n Workflow → OpenWeatherMap API → Telegram Response

Workflow Components

Telegram Trigger Node
Listens for incoming user messages (city names).

HTTP Request Node
Sends a GET request to OpenWeatherMap API.

Telegram Send Message Node
Returns formatted weather details to the user.

🛠️ Tech Stack

n8n (Workflow Automation)

Telegram Bot API

OpenWeatherMap API

REST API Integration

📂 How It Works

User sends a city name via Telegram.

The workflow extracts the city name.

n8n sends a request to the OpenWeatherMap API.

The response is formatted.

Weather details are sent back to Telegram.

📋 Sample Output
Weather: clear sky
Temp: 29°C
Humidity: 65%
🔧 Setup Instructions
1️⃣ Prerequisites

n8n (Cloud or Self-hosted)

Telegram Bot Token

OpenWeatherMap API Key

2️⃣ Import Workflow

Open n8n

Go to Workflows

Click Import

Paste the workflow JSON

Save

3️⃣ Configure Credentials

Add Telegram API credentials

Insert your OpenWeatherMap API key in the HTTP Request node

4️⃣ Activate Workflow

Turn on the workflow

Send a city name to your Telegram bot

🔐 Security Notes

API keys are not included in this repository.

Store credentials securely inside n8n.

Do not commit API keys to version control.

📈 Use Cases

Beginner-friendly API automation project

Telegram bot development example

REST API integration demo

Portfolio project for workflow automation

👨‍💻 Author

Built using n8n for workflow-based automation and real-time API integration.
