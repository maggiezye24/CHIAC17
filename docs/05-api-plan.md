# API Plan (Initial Draft)

## Authentication
- POST /api/auth/register
- POST /api/auth/login

## Quiz Management
- POST /api/quizzes
- GET /api/quizzes
- GET /api/quizzes/:quizId

## Question Management
- POST /api/quizzes/:quizId/questions
- GET /api/quizzes/:quizId/questions

## Quiz Attempt
- POST /api/attempts/start
- POST /api/attempts/submit

## Attempt History
- GET /api/attempts/user
- GET /api/attempts/:attemptId

## Analytics (Extended)
- GET /api/analytics/learner/summary
- GET /api/analytics/quiz/:quizId
