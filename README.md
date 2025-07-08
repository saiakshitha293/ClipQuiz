# ClipQuiz
📚 ClipQuiz – Interactive Video Learning Platform
ClipQuiz turns passive video lessons into an interactive learning experience by embedding questions directly into videos to test users' understanding in real time. Built using the MEAN stack (MongoDB, Express.js, Angular, Node.js), the platform enables admins to manage lesson content and quizzes while providing learners with a smooth and engaging interface.


🚀 Key Features
• Admins can upload lesson videos and assign questions from a reusable question bank
• Manual trigger-time setting for each question to control exactly when it appears during video playback
• Supports both single-select and multi-select questions
• Validations to ensure:
  • No duplicate trigger times
  • Trigger time within video duration
  • Lessons appear only if at least one question is assigned
• Videos pause automatically at each question; users must respond to continue playback
• Restricts new attempts until previous ones are completed to maintain learning flow
• 💾 Automatic attempt recovery: If the session is interrupted due to network issues or browser closure, users can resume the quiz from where they left off—no progress lost.

📊 Analytics Dashboard
👨‍💼 For Admins:
• Monitor active/inactive users and their last login time
• View lesson-specific leaderboards based on:
  • First attempt performance
  • Best attempt out of multiple submissions
• Analyze per-question performance across users, including accuracy, time taken, and partial scoring.

🧑‍🎓 For Users:
• View detailed feedback for each quiz attempt:
  • Submitted answers, correct options, and evaluation status (✅ Correct / ❌ Incorrect / ⚠️ Partially Correct)
  • Time taken for each question and overall attempt
• Track performance over time through multiple attempts and total scores

  
