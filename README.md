# Pharma Factory Questionnaire

This folder contains a static HTML questionnaire applet and a sample CSV file.

## Files

- `index.html` - the questionnaire app
- `questions.sample.csv` - sample question bank for editing by non-technical users

## How it works

- Questions are loaded from a CSV file.
- Each question uses a drop-down with 4 possible scores.
- Score `4` means compliant.
- Questions marked `Yes` in the `critical` column are treated as critical.
- If a critical question is scored below `4`, the app flags it as a danger item.
- Each section has a comments box that is included in the final report.

## CSV columns

- `section`
- `question_id`
- `question`
- `critical`
- `answer_1_label`
- `answer_1_score`
- `answer_2_label`
- `answer_2_score`
- `answer_3_label`
- `answer_3_score`
- `answer_4_label`
- `answer_4_score`

## Usage

1. Open `index.html` in a browser.
2. Load `questions.sample.csv` or your own CSV.
3. Complete the questionnaire and generate the report.
