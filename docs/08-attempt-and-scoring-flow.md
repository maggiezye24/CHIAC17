# Attempt and Scoring Flow

## Attempt Lifecycle
1. Learner starts a quiz attempt
2. System retrieves quiz questions
3. Learner submits answers
4. System evaluates answers
5. Score is calculated and stored

## Answer Storage
- Each selected answer is stored with:
  - Attempt ID
  - Question ID
  - Selected option
  - Correctness status

## Scoring Logic
- Score is calculated by comparing selected answers
  with correct answers stored in the question bank
- Results include:
  - Total score
  - Correct count
  - Wrong count
  - Skipped count

## Result Availability
- Results are immediately available after submission
- Attempt data is accessible via attempt history
