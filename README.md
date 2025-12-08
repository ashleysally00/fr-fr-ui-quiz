# fr-fr-ui-quiz

A lightweight Vanilla JS quiz app for learning **Standard French technology and UI terminology** used in UX writing, software localization, and general computing.

The quiz helps distinguish correct French terms from common distractors, anglicisms, and misleading literal translations.

## Live Demo

**[Launch the App](https://ashleysally00.github.io/fr-fr-ui-quiz/)**

**Reference Table:**  
[View French UX Terminology Reference Table](https://ashleysally00.github.io/fr-fr-ui-quiz/french-terms.html)

## Features

* Distinguishes between proper French UI terminology and misleading anglicisms.
* Covers essential categories:
  * UI buttons and actions (Save, Submit, Cancel)
  * Hardware terms
  * Internet and software vocabulary
* Zero dependencies — runs entirely in the browser.
* Immediate feedback after every question.

## Technical Overview

* **Architecture:** Zero-dependency Single Page Application (SPA)
* **Stack:** HTML5, CSS3, Vanilla JavaScript
* **State Management:** Tracks score and question progression
* **Performance:** Instant load; no build tools required

## How It Works

Each quiz question is generated through:

* **Shuffling:** Random selection from the internal terminology dataset
* **Randomized distractors:** Prevents guessing based on position
* **Context hints:** Reinforces correct usage and meaning
* **Local state:** Handles score and progression

## Usage

Clone or download the repository:

```bash
git clone https://github.com/ashleysally00/fr-fr-ui-quiz.git
```

Open the project and launch the quiz:

```bash
# macOS
open index.html

# Windows
start index.html
```

Or simply drag `index.html` into your browser.

## Reference Table

A static reference page containing the French UX terminology used in the quiz.

This page is for review only and is not part of the interactive quiz.

[View French UX Terminology Reference Table](https://ashleysally00.github.io/fr-fr-ui-quiz/french-terms.html)

## License

This project is open source and available under the MIT License.
