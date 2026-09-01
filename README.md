# WriteWise - English Writing Analyzer

WriteWise is a command-line tool that analyzes English writing and provides feedback on vocabulary, sentence structure, repetition, and academic word usage.

It is designed to help students improve their academic writing by giving quick insights into their writing style and areas for improvement.

## Features

- Count total words
- Count sentences
- Calculate average sentence length
- Detect repeated words
- Analyze academic vocabulary usage
- Generate writing feedback
- Calculate an overall writing score
- Save writing reports automatically

## How It Works

WriteWise analyzes your text using several checks:

### Vocabulary Analysis
- Compares your writing against an academic vocabulary list
- Calculates the percentage of academic words used
- Shows which academic words appeared in your writing

### Sentence Analysis
- Counts sentences
- Calculates average sentence length
- Gives feedback about sentence complexity

### Repetition Detection
- Finds frequently repeated words
- Ignores common words such as articles and conjunctions
- Suggests using synonyms when necessary

### Writing Score

The program gives a score out of 100 based on:

- Academic vocabulary usage
- Sentence structure
- Word variety

## Installation

Clone this repository:

```bash
git clone https://github.com/hamidazad-cmd/writewise.git
```

Move into the project folder:

```bash
cd writewise
```

Make sure you have Python installed:

```bash
python --version
```

## Usage

Run the program:

```bash
python writewise.py
```

Paste your writing when prompted.

Example:

```
WriteWise - English Writing Analyzer
----------------------------------------
Paste your writing:

Online platforms have significantly changed education.
Technology provides students with new opportunities for learning.

REPORT
----------------------------------------
Words: 15
Sentences: 2
Average sentence length: 7.5 words
```

## Files

```
WriteWise/
│
├── writewise.py              # Main program
├── academic_words.txt        # Academic vocabulary database
├── reports.json              # Saved analysis reports
└── README.md
```

## Example Report

```
REPORT
----------------------------------------
Words: 120
Sentences: 8
Average sentence length: 15 words

Repeated words:
- technology: 4 times

Academic Vocabulary:
Academic words used: 12
Academic vocabulary percentage: 10%

Writing Score: 85/100

Feedback:
- ✓ Good use of academic vocabulary.
- ✓ Your sentences show good complexity.
- ⚠ You repeat 'technology' often. Try using synonyms.
```

## Future Improvements

Possible improvements for future versions:

- Add grammar error detection
- Detect sentence variety
- Add more advanced vocabulary analysis
- Create a graphical user interface (GUI)
- Add readability scores
- Compare writing progress over time
- Export reports as PDF

## Limitations

WriteWise is a simple writing analyzer designed for learning and basic feedback.

The analysis is not 100% accurate because it uses rule-based methods rather than advanced language models. For example:

- Academic vocabulary detection depends on the provided word list.
- Repeated word detection may miss some cases or flag words that are acceptable in context.
- The writing score is an estimation, not an official measurement of writing quality.
- The feedback is intended as guidance, not a replacement for a teacher or professional writing evaluation.

Future versions may include more advanced natural language processing techniques to improve accuracy.

## Technologies Used

- Python
- Regular Expressions (`re`)
- JSON
- Collections (`Counter`)
- File Handling

## Purpose

WriteWise was created as a personal project to practice Python programming while building a useful tool for improving English academic writing skills.

## License

This project is open-source and available for learning and improvement.
