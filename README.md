# 🎥 ClipQuiz

📚 **ClipQuiz – Interactive Video Learning Platform**  
ClipQuiz turns passive video lessons into an interactive learning experience by embedding questions directly into videos to test users' understanding in real time. Built using the **MEAN stack** (MongoDB, Express.js, Angular, Node.js), the platform enables admins to manage lesson content and quizzes while providing learners with a smooth and engaging interface.

---

## 🚀 Key Features

- Admins can upload lesson videos and assign questions from a reusable question bank  
- Manual trigger-time setting for each question to control exactly when it appears during video playback  
- Supports both single-select and multi-select questions  
- Validations to ensure:
  - No duplicate trigger times  
  - Trigger time within video duration  
  - Lessons appear only if at least one question is assigned  
- Videos pause automatically at each question; users must respond to continue playback  
- Restricts new attempts until previous ones are completed to maintain learning flow  
- 💾 **Automatic attempt recovery**: If the session is interrupted due to network issues or browser closure, users can resume the quiz from where they left off — no progress lost.

![Screenshot 2025-07-08 065231](https://github.com/user-attachments/assets/0cf35200-c895-441b-9bdb-7ed3e69a8b94)

![Screenshot 2025-07-08 065252](https://github.com/user-attachments/assets/02d733f0-eba3-487c-94db-0f1277e0bcb3)

![Screenshot 2025-07-08 065325](https://github.com/user-attachments/assets/cf49c0d0-3f8b-4e3a-9893-c774e12297f7)

![Screenshot 2025-07-08 065344](https://github.com/user-attachments/assets/36b57893-49ad-4bb1-a354-5ed561fba88f)

![Screenshot 2025-07-08 065735](https://github.com/user-attachments/assets/a2227f3f-2cdc-487c-989f-06283bbb4808)

![Screenshot 2025-07-08 065755](https://github.com/user-attachments/assets/3babdf7e-130b-4cae-aaf2-ff76f9a903f6)

![Screenshot 2025-07-08 065818](https://github.com/user-attachments/assets/de8fb08c-55dd-4299-8a33-1363004e115e)

![Screenshot 2025-07-08 065824](https://github.com/user-attachments/assets/9107fa31-2fd1-4e2e-9336-778bec3f859c)

![Screenshot 2025-07-08 065158](https://github.com/user-attachments/assets/dff83c8f-390f-4a3a-9f71-b7d29e08c15e)

---

## 📊 Analytics Dashboard

### 👨‍💼 For Admins:
- Monitor active/inactive users and their last login time  
- View lesson-specific leaderboards based on:
  - First attempt performance  
  - Best attempt out of multiple submissions  
- Analyze per-question performance across users, including:
  - Accuracy  
  - Time taken  
  - Partial scoring

![Screenshot 2025-07-08 065425](https://github.com/user-attachments/assets/cada8989-8308-435d-828e-965d8f4ca5f9)

![Screenshot 2025-07-08 065437](https://github.com/user-attachments/assets/125ea315-10cc-47b8-b41e-231632e4ad11)

![Screenshot 2025-07-08 065448](https://github.com/user-attachments/assets/6daef58f-4d31-4c6b-9396-92491ae79e0d)

![Screenshot 2025-07-08 065507](https://github.com/user-attachments/assets/7769d206-304b-4f93-acbf-435d49e8895d)

![Screenshot 2025-07-08 065542](https://github.com/user-attachments/assets/7d3ce5b4-8ac4-4cde-8a68-c2389cc1b6d4)

### 🧑‍🎓 For Users:
- View detailed feedback for each quiz attempt:
  - Submitted answers, correct options, and evaluation status (✅ Correct / ❌ Incorrect / ⚠️ Partially Correct)  
  - Time taken for each question and overall attempt  
- Track performance over time through multiple attempts and total scores

![Screenshot 2025-07-08 065846](https://github.com/user-attachments/assets/bc4eb793-5237-4da9-9af7-1410a11567cf)

![Screenshot 2025-07-08 070121](https://github.com/user-attachments/assets/b9ba67c3-c15c-4e8c-a627-16ca37f4327c)

![Screenshot 2025-07-08 065933](https://github.com/user-attachments/assets/1c8427ec-6cfb-4ea8-bae4-2a843aad0965)


---

## 🗂️ Schema Design

![Screenshot 2025-07-08 071623](https://github.com/user-attachments/assets/1163babc-c06b-4b89-aa97-e02e3d1c2573)

![Screenshot 2025-07-08 071656](https://github.com/user-attachments/assets/2e589db1-451c-4d43-9fa4-4313c8fee25d)

![Screenshot 2025-07-08 071445](https://github.com/user-attachments/assets/30bf2867-9ece-4ea5-96e3-952fed416970)

![Screenshot 2025-07-08 071554](https://github.com/user-attachments/assets/2a660127-54ce-4d95-b67f-ba7e76db3b1d)




