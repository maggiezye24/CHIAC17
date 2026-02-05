# Question Bank Design

## Purpose
The Question Bank stores all questions created by quiz creators.
Each question belongs to a specific quiz and can be reused for analytics.

## Question Structure
Each question includes:
- Question text
- Multiple answer options
- Exactly one correct option
- Optional explanation for solution review
- Optional topic tag
- Optional difficulty level

## Question Organization
- Questions are grouped under quizzes
- Questions are uniquely identifiable
- Each question can be referenced during attempts

## Usage
- Quiz creation module inserts questions into the question bank
- Quiz attempt module fetches questions from the question bank
- Analytics module reads question metadata for performance analysis
