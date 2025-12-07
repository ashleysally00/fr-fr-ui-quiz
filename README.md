# fr-fr-ui-quiz

A lightweight Vanilla JS quiz app for learning Standard French tech terminology used in UI/UX, software localization, web design, and general computing.

The quiz helps distinguish correct French terms from common distractors, anglicisms, and misleading translations.

## Live Demo
Try it here:
**[https://ashleysally00.github.io/fr-fr-ui-quiz/](https://ashleysally00.github.io/fr-fr-ui-quiz/)**

## Technical Overview
* **Architecture:** Zero-dependency Single Page Application (SPA).
* **Stack:** HTML5, CSS3, Vanilla JavaScript (ES6+).
* **State Management:** Local state for score and question progression.
* **Styling:** CSS variables + responsive layout.
* **Performance:** Instant load, no bundlers or frameworks.

## How It Works
The app shuffles a curated dataset and dynamically generates the quiz UI. Features include:
* Randomizing distractors per question.
* Immediate visual feedback (CSS class toggles).
* Explanation shown after each answer.
* Score tracking.
* Category labels (Hardware, UI Buttons, Internet, Dev, etc.).

## Usage
1. Clone the repo or download the files.
2. Open `index.html` in your browser to run the quiz locally.
3. To customize the content, edit the `database` array directly in the `<script>` section.

## Notes on Localization
This dataset follows **Standard French** for technology (France + international), avoiding:
* **Franglais** (e.g., *"logger"*, *"digital"*).
* **Misleading literal translations** (e.g., *"sauver"* for Save).
* **Slang or regional usage** unless appropriate.
