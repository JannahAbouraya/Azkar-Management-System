# Azkar Management System (AMS) 🕋📿

An architectural and database-focused management system engineered to organize, track, and serve daily Islamic Adhkar (supplications) and prophetic prayers. This system features a dedicated graphical user interface integrated with a robust relational database back-end.

## 🚀 System Objectives
* **Categorization:** Systematically map various forms of supplications (e.g., Morning, Evening, Post-Prayer, Travel, and Sleep).
* **Tracking & Progress:** Provide users with a way to log read recitations and view chronological progress counters.
* **Notification System:** Handle scheduling parameters to dynamically deliver reminders at optimized times of the day.

---

## 🛠️ Tech Stack & Architecture
* **Frontend User Interface:** Oracle Forms Developer (using `.fmb` designs)
* **Database Engine:** Oracle SQL Developer / Microsoft SQL Server
* **Design Methodology:** Relational Database Schema Design with Normalized Structures (1NF, 2NF, 3NF).
* **Components:** Custom SQL scripts, Table Relations, Views, and Optimized Queries for rapid data fetching.

---

## 📋 Core Specifications

### 🔹 Database Schema & Relations
The backend relies on structured entities to safely hold and map multi-lingual texts, counters, and execution rules:
1. **User Profiles Table:** Stores unique user preferences, language choices, and completion streaks.
2. **Azkar Catalog Table:** Categorizes each supplication by type, Arabic text, phonetic transliteration, translation, and standard repetition counts (e.g., 3x, 33x, 100x).
3. **Recitation History Logs:** Tracks historical metrics to construct user performance dashboards.

### 🔹 Non-Functional Metrics
* **Data Integrity:** Implements strict Foreign Key constraints ensuring references across category logs always stay in sync.
* **Localization Support:** Optimized character encoding (UTF-8/Unicode) to accurately preserve complex Arabic diacritics and text layouts.

---

## 📂 Repository Layout
```text
📂 Azkar-Management-System
 ├── 📂 Database          # SQL schemas, tables initialization scripts, and relationships
 ├── 📂 Documentation     # System Design Specs, Use Case documents, and Requirements
 ├── 📂 Forms             # Oracle Forms source files (.fmb) and compiled components (.fmx)
 └── 📄 README.md         # Profile landing page

```

## 👥 Contributors 
* Jannah Mohamed Abdallah
* Fayrouz Sameh Salah
* Rania Mohammed Hammad
* Reda Ahmed Mohamed
* Sarah Hassan
* Fatma Mohamed
* Haidi Mohamed
* Mennat Allah Tamer
```
