# 🎙️ Voice-to-SQL Analyst

### Multilingual Voice-Based Data Analytics using Gnani Prisma v3.0

[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/Akash-S2004/Voice-to-SQL-Analyst)

## 📌 Project Overview

Voice-to-SQL Analyst is a multilingual voice-powered analytics application that allows users to ask questions about business data using natural speech instead of writing SQL queries manually.

The application uses **Gnani Prisma v3.0** for speech-to-text conversion and transforms recognized questions into SQL queries to retrieve and visualize business insights.

The goal is to make data analytics more accessible to small business owners, students, and non-technical users.

## ❗ Problem Statement

Many small business owners maintain sales records but find it difficult to analyze their data using spreadsheets or SQL.

Language barriers and limited technical knowledge make accessing business insights challenging.

## 💡 Proposed Solution

Voice-to-SQL Analyst provides a simple voice-based interface where users can:

- Ask questions using their voice.
- Interact in Tamil, English, Hindi, and Hinglish.
- Convert spoken questions into SQL queries.
- View query results in tables.
- Understand business insights through charts.

## ⚙️ Key Features

- **Multilingual Speech Recognition:** Uses Gnani Prisma v3.0.
- **Voice Input:** Records spoken questions through the browser.
- **Editable Transcription:** Allows users to review and edit recognized text.
- **Text-to-SQL:** Converts natural-language questions into SQL.
- **SQL Safety:** Restricts execution to read-only SELECT queries.
- **Data Visualization:** Displays results through tables and charts.
- **Demo Database:** Includes approximately 900 synthetic sales orders.

## 🔄 Application Workflow

1. User speaks a business-related question.
2. Browser records audio and converts it into WAV format.
3. Audio is sent to Gnani Prisma v3.0.
4. Speech is converted into text.
5. The recognized question is converted into an SQL query.
6. The query is executed against the demo database.
7. Results are displayed as tables and charts.

## 🧠 Technology Stack

| Component | Technology |
|---|---|
| Programming Language | Python |
| Speech-to-Text | Gnani Prisma v3.0 |
| API Integration | REST API |
| Database | SQLite |
| Query Language | SQL |
| Interface | Browser-based application |
| Visualization | Charts and tables |

## 🛡️ Security Features

- Read-only SQL query execution.
- Blocks INSERT, UPDATE, DELETE, DROP, and other write operations.
- Restricts access to system tables.
- Uses SQLite query-only mode.
- Limits query results to a maximum of 200 rows.

## 🧪 Testing

- 32 automated offline tests completed.
- Mocked network calls used for offline testing.
- Tested Tamil and English/Hinglish speech recognition.
- Tested SQL query safety and data retrieval.

## ⚠️ Current Limitations

- Uses synthetic demo sales data rather than real business records.
- LLM-based SQL generation may experience service timeouts.
- Keyword-based fallback supports a limited set of common questions.
- Speech recognition may occasionally require manual transcript correction.

## 🚀 Future Improvements

- Improve natural-language-to-SQL reliability.
- Add support for more Indian languages.
- Integrate Gnani Timbre text-to-speech.
- Support real business databases.
- Expand analytical questions and visualizations.

## 🎥 Project Demonstration

[Watch the Voice-to-SQL Analyst Demo](https://lnkd.in/p/gWWFfHsJ)

## 👨‍💻 Developer

**Akash S**

MCA Student | Aspiring Data Analyst | AI Enthusiast

- GitHub: [Akash-S2004](https://github.com/Akash-S2004)
- Project Repository: [Voice-to-SQL-Analyst](https://github.com/Akash-S2004/Voice-to-SQL-Analyst)

## 📄 Project Information

This project was independently designed, developed, and tested as part of the Great Indian AI Internship Challenge.

**Built with Python and Gnani Prisma v3.0.**
