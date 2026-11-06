# Task 1 Overview Trainer

Choose the best overview for a generated chart. The overview is what examiners look for first.

Part of the [IELTS Study Suite](https://github.com/Apurba94/ielts-study-suite): 100 free study apps for IELTS. This one is for the IELTS Academic test. It works offline, as a Windows program or in the browser.

## Download and run

- **Windows:** download `Task 1 Overview Trainer.exe` from the [latest release](https://github.com/Apurba94/ielts-overview-trainer/releases/latest) and open it. Nothing to install. It opens in its own window and saves your progress in your user folder.
- **Browser:** open it online in the suite's web edition at https://ielts-study-suite.vercel.app/apps/ielts-overview-trainer/ . Progress stays in that browser.
- **From source:** `python launcher.py` (Python 3.10 or later, no packages needed).

## What it does

The overview is the sentence or two that sums up a chart: the main trends or the biggest differences, with no detailed numbers. Without one, a Task 1 answer is unlikely to score well for task achievement. Choose the best overview for generated charts, where the wrong options are too detailed, wrong or too vague.

Sections: Practice, Progress, About.

## How to use it

1. Look at the chart and ask: what are the two biggest things it shows?
2. Choose the overview that says those things without numbers.
3. Write an overview like it in every Task 1 report, after the introduction or at the end.

## Good to know

- All questions, passages, recordings and definitions were written for this suite. None are official IELTS questions. For official practice, use the materials on ielts.org and from the test partners.
- It follows IELTS as delivered on computer in 2026. Formats change, so check ielts.org before your test.
- Listening uses the voices installed on your computer, which sound less natural than real test recordings.
- Feedback on writing and speaking counts what a program can count honestly, such as length and linking words. It is not an IELTS band score. Band conversions for Listening and Reading are approximate.
- Not endorsed by or affiliated with the British Council, IDP or Cambridge University Press & Assessment. IELTS is a registered trademark of its owners.

## For developers

The app is plain HTML and JavaScript in `web/`, run by a small Python launcher that serves it on 127.0.0.1 only and needs a secret token for saving. Tests: `node --test "tests/*.test.js"` (29 tests) and `python -m unittest discover -s tests`. Build the .exe with `python build_exe.py`.

Built with AI assistance (Claude Code). MIT licence. By JANIN A APURBA.
