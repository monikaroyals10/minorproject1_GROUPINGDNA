# minorproject1_GROUPINGDNA
# 📊 GroupDNA – WhatsApp Chat Analyzer

## 🚀 Project Overview

GroupDNA is a Python-based analytics project that analyzes a WhatsApp chat export and generates detailed insights about the group's messaging behavior. It reads the exported chat file, extracts useful information, performs statistical analysis, builds a NumPy-based activity heatmap, identifies communication patterns, and assigns personality archetypes to every participant.

This project was developed as part of **The Unlox Academy Week 1 Minor Project** using only Python fundamentals and NumPy.

---

# 🎯 Objectives

The main objective of this project is to convert a raw WhatsApp chat export into a meaningful analytics report.

The project answers questions like:

- Who sends the most messages?
- Who is the least active?
- Which day was the busiest?
- Which hour has maximum activity?
- What words are most frequently used?
- Who replies the fastest?
- Who stays silent for the longest time?
- Who is the Night Owl?
- Who is the Ghost?
- Who is the Storyteller?

---

# 🛠 Technologies Used

- Python 3
- NumPy
- datetime
- collections
- string

No external libraries such as pandas or matplotlib are used.

---

# 📂 Dataset

Dataset Used:hostel_bois.txt
Dataset Type:

- WhatsApp Android Chat Export
- UTF-8 Text File

Contains:

- 6 Participants
- Around 3174 Messages
- 60 Days of Chat Data

Participants:

- Rahul
- Priya
- Aman
- Karan
- Neha
- Vikas

---

# 📌 Features Implemented

## Feature 1 – Chat Parser

The parser reads the WhatsApp chat line by line and extracts

- Timestamp
- Sender
- Message

It also handles

- System messages
- Media omitted messages
- Deleted messages
- Empty lines

---

## Feature 2 – Group Overview

Displays

- Total Messages
- Total Participants
- Date Range
- Total Days
- Messages per Person
- Percentage Contribution

---

## Feature 3 – Activity Analysis

Calculates

- Most Active Day
- Most Active Hour
- Most Active Member
- Least Active Member
- Daily Message Count

---

## Feature 4 – NumPy Activity Heatmap

Creates a rows and columns
Each cell stores the number of messages sent by a participant during that hour.

The project also displays

- Numeric Heatmap
- Text Heatmap using Unicode Blocks

---

## Feature 5 – Top Words

Finds

- Top 10 most used words

Ignores

- Stop words
- Media omitted
- Deleted messages

Displays a horizontal frequency bar.

---

## Feature 6 – Response Analysis

Calculates

- Average Response Time
- Fastest Replier
- Slowest Replier

Also calculates

- Longest Silent Streak

---

## Feature 7 – Personality Archetypes

Each participant is assigned a personality based on activity.

Possible archetypes include

- The Spammer
- The Night Owl
- The Ghost
- The Storyteller
- The Meme Dealer
- The Regular

---

## Feature 8 – Final Report

Displays a formatted analytics report including

- Group Statistics
- Activity Summary
- Top Words
- Personality Types
- Peak Activity
- Fastest Replier

---

# 🎁 Bonus Features

✔ Media Ranking

✔ Deleted Message Ranking

✔ Most Active Hour Per Person

✔ Report Export (.txt)

---


