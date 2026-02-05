# Database Design (Conceptual)

## User
- userId
- name
- email
- passwordHash
- role (learner / creator / admin)

## Quiz
- quizId
- title
- description
- creatorId
- isPublished
- createdAt

## Question
- questionId
- quizId
- questionText
- options (array)
- correctOption
- explanation (optional)
- topic (optional)
- difficulty (optional)

## Attempt
- attemptId
- userId
- quizId
- score
- totalQuestions
- submittedAt

## AttemptAnswer
- attemptId
- questionId
- selectedOption
- isCorrect

## IntegrityLog (Optional)
- attemptId
- eventType
- eventValue
- timestamp
