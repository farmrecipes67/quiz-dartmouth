# 🎓 Dartmouth Insider Quiz

![Dartmouth Campus](https://drive.google.com/uc?export=view&id=1aXIT44DrCCUjXTGdn9HncwELqeWgKSDv)

## About This Quiz

Think you know Dartmouth? This insider quiz tests your knowledge of campus traditions, history, famous alumni, hidden gems, and little-known facts that only true insiders would know.

**10 questions • 5 choices each • How well do you really know Dartmouth?**

## How to Use

### Questions
Check out [`questions.js`](./questions.js) for the full quiz with all 10 questions and their multiple-choice options.

### Answers
The answer key with explanations is in [`answers.js`](./answers.js) — no peeking until you're done! 👀

## Quick Start

```javascript
const { questions } = require('./questions');
const { answers } = require('./answers');

// Display a question
console.log(questions[0].question);
Object.entries(questions[0].choices).forEach(([key, val]) => {
  console.log(`  ${key}: ${val}`);
});

// Check answer
console.log(`Correct: ${answers[0].correct} - ${answers[0].explanation}`);
```

## Sample Question

> **On campus maps and lore, what does BEMA actually stand for?**
> - **A.** Big Empty Meeting Area
> - **B.** Baker East Meeting Annex
> - **C.** Beta Epsilon Meeting Atrium
> - **D.** Big Elm Music Amphitheater
> - **E.** Berry Experimental Media Area

<details>
<summary>🔍 Click to reveal answer</summary>

**A** — BEMA is insider shorthand for Big Empty Meeting Area in College Park.

</details>

## Quiz Topics Covered

- 🏛️ Campus traditions & rituals
- 📜 University history & founding stories
- 🌟 Famous alumni & their connections
- 🗺️ Hidden spots & insider knowledge
- 🎯 Little-known facts & surprising trivia

---

<div align="center">

*Generated with 💜 by [Papersaurus](https://github.com/farmrecipes67) 🦕*

*Quiz content created using AI • Campus image generated with AI*

</div>

<!-- Open Graph Tags for Social Sharing -->
<!-- og:title: Dartmouth Insider Quiz -->
<!-- og:description: Think you know Dartmouth? Take this 10-question insider quiz covering campus traditions, history, famous alumni, and little-known facts! -->
<!-- og:image: https://drive.google.com/uc?export=view&id=1aXIT44DrCCUjXTGdn9HncwELqeWgKSDv -->
<!-- og:type: website -->
