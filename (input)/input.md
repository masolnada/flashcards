# path: cards/mathematics/algebra/function_models.md

---

Q: Quina expressió defineix el model de funció "Lineal" a la imatge?
A: $P = mr + n$
---
# path: cards/software/commands/reminders.md

---

Q: How do you set a simple reminder for a specific time today?
A: Use the `/remind` command followed by the time. Example: `/remind 6:40`.
---
# path: cards/meta/command/help.md

---

Q: What is the main purpose of this tool?
A: To generate atomic Q&A flashcards from input text and a list of topics.
---
# path: cards/meta/command/help.md

Q: How can I prevent the generator from creating cards for concepts I already have?
A: Provide the existing cards for each topic. The generator will not create duplicates.
---
# path: cards/meta/command/help.md

Q: How can I emphasize certain concepts in the input text to ensure flashcards are created for them?
A: Write or highlight the important text in red. The generator will prioritize creating cards for these concepts.
---
# path: cards/meta/command/help.md

Q: What is the output format for the generated flashcards?
A: A single JSON array, where each object represents a topic and contains the `filePath`, `deckName`, and a string of new `cards`.
---
# path: cards/meta/command/help.md

Q: What is the "atomic" rule for flashcards?
A: Each card should cover only one single, discrete concept.
---
# path: cards/meta/command/help.md

Q: What is the required format for an individual flashcard in the output?
A: Each card must start with `---`, followed by a blank line, then `Q: ...` and `A: ...` on new lines.