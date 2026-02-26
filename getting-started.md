+++
title = "Getting Started"
+++

## What format does hashcards use for frontmatter?

TOML, delimited by `+++` blocks (not YAML `---`).

## What algorithm does hashcards use for scheduling?

FSRS — Free Spaced Repetition Scheduler.

## What command starts the hashcards web interface?

`hashcards drill [directory]`

## How do you add a new deck?

Create a `.md` file with `+++` TOML frontmatter and `## Question / Answer` pairs.

## What does spaced repetition mean?

Cards you struggle with appear more often; cards you know well appear less often, optimising long-term retention.
