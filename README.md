# Pharma Factory Questionnaire

This folder contains a static HTML questionnaire applet and a sample CSV file.

## Files

- `index.html` - the questionnaire app
- `questions.sample.csv` - sample question bank for editing by non-technical users

## How it works

- Questions are loaded from a CSV file.
- Each question uses one continuous display number from `9.1` through `9.38`.
- Each question uses a score-only drop-down with scores `1` through `4` and `Not Applicable`.
- `Not Applicable` responses are excluded from the average and score totals.
- The selected score reveals the wording in the `Audit scoring guide`.
- Each question has its own `Comments and findings` field, included in the final report.

## CSV columns

- `section`
- `question_id`
- `question`
- `critical` (retained for compatibility, not used)
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
