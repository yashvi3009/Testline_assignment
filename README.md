# Testline_assignment
Quiz Analysis Project 

## Overview
This project analyzes student performance data to provide actionable insights and personalized recommendations for improvement. By exploring the schema and identifying patterns in student performance across topics, difficulty levels, and response accuracy, the system highlights weak areas, strengths, and performance trends for individual users. The insights and recommendations aim to enhance learning outcomes through targeted focus on specific areas.

## Features
- Fetch data from multiple APIs (`JSONKeeper` and `JsonServe`).
- Store API responses in local JSON files for reuse.
- Convert JSON data to pandas DataFrames for analysis.
- Perform insights on quiz submissions:
  - Schema validation for datasets.
  - Summary statistics (mean, max, count, etc.).
  - Unique quizzes and users.
  - Analysis of submissions per quiz.

---

## Dataset Sources
### APIs Used:
1. **Current Quiz Submission 1**: [JSONKeeper API](https://www.jsonkeeper.com/b/LLQT)
2. **Current Quiz Submission 2**: [JsonServe API](https://api.jsonserve.com/rJvd7g)
3. **Historical Quiz Data**: [JsonServe API](https://api.jsonserve.com/XgAgFJ)

Each dataset includes information such as quiz IDs, scores, accuracy, speed, total questions, and timestamps of quiz attempts.

---

## Prerequisites
### Libraries
- Python 3.x
- `requests`
- `json`
- `pandas`

### Installation
1. Clone the repository: 
2. Install required packaged: pip install -r requirements.txt
