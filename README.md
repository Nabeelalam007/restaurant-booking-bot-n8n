Restaurant Booking Bot

A Telegram-based restaurant table booking bot built using n8n, Telegram Bot API, and Google Sheets.

Features
🍽️ Book a table
📅 Select booking date
🕐 Select booking time
✅ Confirm booking
❌ Cancel booking
🔍 Check latest booking
📊 Store booking information in Google Sheets
🤖 Automated Telegram responses
Workflow

Telegram → n8n → Google Sheets

The bot receives Telegram messages and button selections through an HTTPS webhook. n8n processes the booking information and stores confirmed bookings in Google Sheets.

Technologies
n8n
Telegram Bot API
Google Sheets
ngrok
JavaScript
Project File

Restaurant_Booking_Bot.json contains the exported n8n workflow.

Current Status

The core booking workflow is functional, including booking, confirmation, Google Sheets storage, and checking the latest booking.
