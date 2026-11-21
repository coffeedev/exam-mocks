# exam-mocks

Self-contained practice exam apps for certification prep. Each mock lives in its own folder and runs as a single HTML file in the browser, with no installation, server or internet connection needed.

> All questions are original practice material written for study. They are not real exam content and are not affiliated with or endorsed by any exam provider.

## Available mocks

| Exam | Folder | Questions | Open |
| --- | --- | --- | --- |
| CCAO-F (Claude Certified Associate – Foundations) | [`ccao-f/`](ccao-f/) | 420 (7 sets of 60) | [`ccao-f/CCAO-F-Mock-Exam.html`](ccao-f/CCAO-F-Mock-Exam.html) |

## How to use a mock

1. Clone or download this repository.
2. Open the mock's folder and double-click its `.html` file. It opens in any modern browser (Chrome, Edge, Firefox, Safari).
3. Pick a mode on the start page and begin.

Progress is saved in your browser's local storage, so it stays on that computer and in that browser only.

---

## CCAO-F mock exam

**Folder:** [`ccao-f/`](ccao-f/)

A practice app for the CCAO-F exam, aimed at business users of Claude. It follows the exam format of 60 questions in 120 minutes, scored from 100 to 1,000 with 720 to pass.

### Files

| File | What it is |
| --- | --- |
| [`CCAO-F-Mock-Exam.html`](ccao-f/CCAO-F-Mock-Exam.html) | The full app in one file. Open it in a browser. |
| [`questions.json`](ccao-f/questions.json) | All 420 questions with options, answers, explanations and domain tags, for printing or importing into other tools. |
| [`README.txt`](ccao-f/README.txt) | Short offline usage notes. |

### Modes

- **7 fixed sets** of 60 questions, each matching the exam blueprint and including about 10 hard questions.
- **Hard mock**, drawn from the pool of harder questions.
- **Random mock** of 60 questions.
- **Quick quiz** of 20 questions.
- **Practice by domain**, to focus on one area at a time.

Every mode gives instant feedback. Choose your answer, press **Check answer** to see whether it's right and why, and the answer then locks. Exam modes finish with **Submit exam** for the final score.

### Domains covered

Each 60-question set follows the blueprint weights below.

| Domain | Weight | Questions per set | In the bank |
| --- | --- | --- | --- |
| Prompting & Task Execution | 14% | 8 | 56 |
| Output Evaluation & Validation | 21% | 13 | 91 |
| Product & Model Selection | 12% | 7 | 49 |
| Workflow Integration & Solution Design | 16% | 10 | 70 |
| Configuration & Knowledge Management | 12% | 7 | 49 |
| Governance, Risk & Responsible Use | 15% | 9 | 63 |
| Troubleshooting & Optimization | 10% | 6 | 42 |

### Timer and saved progress

- The 120-minute timer has a **Pause** button (or press **P**). The question is hidden while paused.
- Progress saves as you go. Close the page mid-test and reopen it to resume where you left off, with the timer paused.
- A finished test keeps its last result, with right and wrong answers, until you reset it from **Saved tests** on the start page or with **Reset & retake** on the results page.

### Notes

- Scaled scores are an estimate (100 + 900 × correct ÷ questions), because the real conversion isn't published.
- Offline, the page uses your system fonts instead of web fonts. Everything else works the same.

---

## Adding a new mock

1. Create a folder named after the exam code in lowercase, for example `abc-x/`.
2. Put the self-contained `.html` app in it, plus a `questions.json` and a short `README.txt` if useful.
3. Add a row to the **Available mocks** table above.
4. Add a section for the mock below the CCAO-F one, using the same headings: Folder, Files, Modes, Domains covered, Timer and saved progress, Notes.

## License

See [LICENSE](LICENSE).
