---
type: prompt
id: flashcard-creator
title: Flashcard Creator
description: "Task prompt for generating study flashcards from notes"
tags: [Production]
connections:
  - target: note-taking
    type: derived_from
---

## Purpose

Creates flashcards from study notes for active recall practice.

## Prompt

Create {{count}} flashcards from the following study material. Each flashcard should have a clear question on the front and a concise answer on the back. Include a mix of: definition cards, concept explanation cards, and application cards. Order them from fundamental concepts to more advanced topics. Format each card as:

**Front:** [question]
**Back:** [answer]
