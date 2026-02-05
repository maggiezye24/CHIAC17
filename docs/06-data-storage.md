# Data Storage and Persistence

## Overview
The platform uses a centralized database to store all persistent data
required for quiz creation, quiz attempts, scoring, and analytics.

## Data Categories
The following categories of data are stored:

1. User Data
   - Account details
   - Role information

2. Quiz Data
   - Quiz metadata
   - Quiz status (draft/published)

3. Question Data
   - Question text
   - Options
   - Correct answer
   - Explanation (optional)

4. Attempt Data
   - User attempts
   - Selected answers
   - Scores and timestamps

## Storage Responsibility
- Backend layer handles all database operations
- Frontend does not store persistent assessment data
