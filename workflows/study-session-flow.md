---
type: workflow
id: study-session-flow
title: Study Session Flow
description: "Structured study session: notes, flashcards, and practice questions"
tags: [Tested]
connections:
  - target: note-taking
    type: uses
  - target: take-notes
    type: uses
  - target: flashcard-creator
    type: uses
  - target: practice-question-generator
    type: uses
---

## Overview

This workflow structures a study session from raw material through to active recall practice, producing notes, flashcards, and practice questions.

## Pipeline Stages

### Stage 1: Note-Taking

Invoke the **note-taking** skill to transform lecture content and readings into structured, retrievable notes using the Cornell method.

### Stage 2: Flashcard Generation

Invoke the **flashcard-creator** prompt to create flashcards from the structured notes, focusing on key concepts and definitions.

### Stage 3: Practice Questions

Invoke the **practice-question-generator** prompt to generate exam-style questions that test understanding of the material.

## Output

A complete study session package containing:

- Structured notes with key concepts highlighted
- Flashcards for active recall practice
- Practice questions with model answers
