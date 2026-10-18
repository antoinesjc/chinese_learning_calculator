# Mandarin Zest learning calculator

Live: https://antoinesjc.github.io/chinese_learning_calculator/chinese_learning_calculator.html
Used on: https://www.mandarinzest.com/chinese-learning-calculator

- Two modes: "How long will it take?" (date) and "Reach it by a date" (hours per week needed).
- Seven questions: level now (incl. "grew up hearing it at home"), goal, speaking only vs reading & writing,
  mother tongue + other languages, hours per week, study method, consistency. Result updates instantly.
- Model numbers (hours per level, language and method factors) are at the top of the script: LEVELS, TONGUE, EXTRA, METHOD.
- Share button makes a 1080×1350 picture. Shop button uses the HSK tag of the next level.
- Emails go to the "Start here" Google Sheet with source `calculator | <goal and date>`.
- Full-page embed: `height:max(2200px, calc(4950px - 240vw))` + `scrolling="no"` (no inner scroll). A 100vh embed also works (scrolls inside, phone result bar).
