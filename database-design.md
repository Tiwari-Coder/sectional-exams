# Database Design

## exams
- id
- name
- total_sections
- duration

## sections
- id
- exam_id
- section_name
- time_limit

## questions
- id
- section_id
- question
- options
- correct_option

## user_answers
- id
- exam_id
- section_id
- question_id
- selected_option

## results
- id
- exam_id
- total_marks
- status

