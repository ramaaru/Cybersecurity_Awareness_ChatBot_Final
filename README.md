# Cybersecurity_Awareness_ChatBot_Final
A comprehensive WPF-based cybersecurity awareness chatbot with conversation management, statistics, search, and reporting capabilities.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Features in Detail](#features-in-detail)
- [Testing](#testing)

## Overview

The **Cyber Security Awareness Bot v3.0** is an interactive desktop application designed to educate users about cybersecurity best practices. It features a conversational AI interface that responds to user queries about various security topics, remembers user preferences, detects risk levels, and maintains a complete conversation history.

### Key Highlights
- Voice greeting on startup
- Intelligent chatbot with memory
- Comprehensive statistics dashboard
- Advanced search capabilities
- Report generation and export
- JSON-based data persistence
---

## Features

### Core Chatbot

| Feature | Description |
|---------|-------------|
| Keyword Responses | Responds to cybersecurity topics like passwords, phishing, privacy, scams |
| Memory System | Remembers user name, favourite topics, and conversation history |
| Sentiment Detection | Detects emotions (worried, frustrated, curious) and responds appropriately |
| Follow-up Support | Handles "tell me more" and "another tip" requests |
| Risk Detection | Identifies High, Medium, or Low risk levels in user queries |

### Conversation Management

| Feature | Description |
|---------|-------------|
| JSON Storage | Automatically saves all conversations to Data/conversations.json |
| Advanced Search | Search by ID, keyword, topic, date, or risk level |
| Delete by ID | Remove individual conversations |
| Clear All | Delete entire conversation history |

### Statistics Dashboard

| Metric | Description |
|--------|-------------|
| Total Conversations | Overall conversation count |
| Topic Breakdown | Password, Privacy, Phishing, Scam counts |
| High Risk Count | Number of high-risk conversations |
| Most Asked Topic | Most frequently discussed topic |
| Favourite Topic | User's preferred topic |
| Visual Charts | ASCII bar charts for topic distribution |

### Reporting and Export

| Feature | Description |
|---------|-------------|
| Generate Report | Creates detailed conversation summary |
| Export Report | Saves report as text file |
| History Export | Exports complete history to file |

### User Experience

| Feature | Description |
|---------|-------------|
| Voice Greeting | Plays welcome audio on startup |
| Daily Tips | Random cybersecurity tips |
| Dark Theme | Professional, eye-friendly interface |
| Responsive | Adapts to different window sizes |

---
## Technologies Used

| Technology | Version | Purpose |
|------------|---------|---------|
| .NET Framework | 8.0 | Application framework |
| WPF | 8.0 | User interface |
| C# | 12.0 | Programming language |
| System.Speech | 10.0.5 | Text-to-speech |
| System.Windows.Extensions | 10.0.5 | Sound playback |
| JSON | - | Data persistence |
| MSTest | 17.8.0 | Unit testing |

---

## Installation

### Prerequisites
- Windows 10 or later
- .NET 8.0 SDK or later
- Visual Studio 2022 or later (recommended)
