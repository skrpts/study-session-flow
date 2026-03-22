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

Create {{input.card_count}} flashcards from the structured notes produced in the previous stage. The module name and topic are carried forward from Stage 1. Each flashcard should have a clear question on the front and a concise answer on the back. Include a mix of: definition cards, concept explanation cards, and application cards. Order them from fundamental concepts to more advanced topics. Format each card as:

**Front:** [question]
**Back:** [answer]
