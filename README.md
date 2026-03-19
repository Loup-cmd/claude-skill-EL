# Claude Skills — Literary Text Analysis

A collection of skills for Claude designed to improve its performance on structured literary analysis tasks, with a focus on the French academic tradition.

---

## Available Skills

### analyse-lineaire

A skill that enables Claude to produce complete, well-structured linear analyses (analyses linéaires) of literary texts, following the standards of the French lycée and baccalauréat curriculum.

**What it does**

When this skill is active, Claude will:

- Segment any literary passage into coherent movements
- Write a full introduction covering context, passage presentation, a guiding question (problématique), and an outline of movements
- Analyze each section in chronological order, systematically linking literary devices to their effects and to the broader argument
- Write a conclusion that answers the guiding question and opens onto a wider literary perspective
- Handle genre-specific conventions for poetry, prose fiction, drama, and argumentative texts
- Draw from a curated reference of over 30 literary devices with definitions and examples from canonical French texts

**When to use it**

This skill triggers whenever you ask Claude to perform a linear analysis, a close reading, a textual commentary, or any line-by-line or verse-by-verse examination of a literary passage. It also activates when you share an excerpt and ask for detailed analysis, even if you do not explicitly use the term "analyse linéaire".

**Skill contents**

- `SKILL.md` — Core instructions: structure, phrasing guidelines, genre-specific rules
- `references/procedes.md` — Full reference of literary devices organized by category: figures of speech, sound devices, syntax, lexical fields, registers, point of view, versification, and verb tenses

---

## Installation

### Option 1 — Install the packaged .skill file

Download the `analyse-lineaire.skill` file from the releases section of this repository and import it directly into Claude via Settings > Skills > Add a skill.

### Option 2 — Point Claude to this repository

In Claude.ai, go to Settings > Skills > Add a skill and paste the URL of this repository or the direct path to the skill folder.

---

## Repository Structure

```
/
├── README.md
└── analyse-lineaire/
    ├── SKILL.md
    └── references/
        └── procedes.md
```

---

## Requirements

- A Claude.ai account with access to the Skills feature (Pro, Team, or Enterprise plan)
- No additional dependencies or API keys required

---

## Contributing

Contributions are welcome. If you want to improve the reference file, add support for additional genres, or propose a new skill for a different type of literary exercise (such as dissertation, commentaire composé, or contraction de texte), feel free to open an issue or submit a pull request.

Please keep all skill instructions and reference content in the language they are written in. The analysis methodology is rooted in the French academic tradition and should remain consistent with it.

---

## License

This project is released under the MIT License. You are free to use, modify, and redistribute it, including for educational purposes.
