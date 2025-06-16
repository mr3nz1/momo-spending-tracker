# 📱 Momo Spending Tracker

A React Native app that parses mobile money (MoMo) SMS messages to track and analyze your spending. Built for users who rely on MoMo services and want real insights into their financial behavior.

## 🚀 Overview

**Momo Spending Tracker** scans SMS messages for MoMo transaction data and breaks it down by category. No more guessing where your money went — this tool gives you a clear view of your spending patterns.

## 🔍 Features

- 📩 **SMS Parsing** – Automatically detects MoMo transaction SMS and extracts key data.
- 📊 **Spending Analytics** – Visual charts showing where your money goes.
- 📅 **Date Filtering** – View expenses by day, week, or month.
- 🔐 **Local-Only Processing** – Your data stays on your device. No server. No sync.

## 🧰 Tech Stack

- **React Native** – Mobile app framework
- **Expo / Bare Workflow** – Dev/Prod flexibility
- **SMS Permission APIs (Android)** – For reading SMS
- **SQLite / AsyncStorage** – Local data persistence

## ⚠️ Limitations

- ❌ iOS not supported – Apple doesn’t allow SMS access.
- ⚠️ Android SMS permission required – App needs explicit user consent.
- 🌍 Optimized for countries where MoMo is widely used.

## 🔮 Roadmap

- 🔔 Budget alerts and notifications
- 📤 Export/backup functionality (CSV, Google Drive)
- 🌐 Localization support
- 🔍 Searchable and filterable transaction history

## 🛠️ Getting Started

```bash
git clone https://github.com/yourusername/momo-spending-tracker.git
cd momo-spending-tracker
npm install
npx expo start
