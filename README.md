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
1. Clone the repository: https://github.com/yashvi3009/Testline_assignment
2. Install required packaged: pip install pandas numpy matplotlib scikit-learn requests

### Demo Video Link : https://drive.google.com/file/d/18sCMeeohvL1NgwX_wuKz4YI5Ifr33eHj/view?usp=sharing

### Approach 
The analysis of the quiz datasets highlights key performance metrics, user behavior patterns, and opportunities for platform improvement. First, the **average accuracy** across all submissions is 80%, reflecting that users are generally performing well. The **average speed per question**, recorded at 100 seconds, provides insight into the time users take to process and respond accurately. However, the **average quiz completion time**, noted as 44 seconds, seems inconsistent with the per-question speed, possibly indicating the dataset includes shorter quizzes or users not completing all questions. 

Interestingly, the dataset includes only one unique quiz, suggesting a lack of variety in quiz content, which could lead to reduced user engagement over time. Expanding the range of topics and difficulty levels could address this issue and appeal to a broader audience. Performance categorization shows all users falling into the beginner level, which raises concerns about the quiz difficulty not being adaptive or tailored to diverse user competencies. This suggests that implementing a more dynamic system to classify users into beginner, intermediate, and advanced levels based on their performance could foster growth and learning. 

The inclusion of a **leaderboard** and **badging system** adds a gamification element to the platform, where users are ranked based on cumulative scores and awarded badges such as gold, silver, or bronze for their achievements. For example, the top performer scored 32 points, which may indicate either the maximum achievable score for the quiz or the limited participation of users at advanced levels. This gamification strategy can be further enhanced by increasing score visibility and introducing rewards or challenges. 

Finally, personalized quiz recommendations could significantly enhance user engagement. For example, high-performing users could be directed toward advanced quizzes to maintain interest and challenge, while beginner users could be provided simpler quizzes to build confidence. This personalized approach, combined with expanding quiz diversity and improving difficulty scaling, has the potential to optimize user retention and the overall learning experience.

### Conclusion
In summary, the dataset analysis reveals that while users generally perform well, there are significant opportunities to improve platform engagement and learning outcomes. The lack of quiz variety, inconsistent time metrics, and the absence of difficulty scaling indicate areas for enhancement. By expanding quiz topics, introducing adaptive difficulty levels, and leveraging gamification with personalized recommendations, the platform can foster a more engaging and rewarding user experience, ultimately driving retention and performance improvement.
