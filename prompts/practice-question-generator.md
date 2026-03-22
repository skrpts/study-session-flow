---
type: prompt
id: practice-question-generator
title: Practice Question Generator
description: "Task prompt for generating exam-style practice questions"
tags: [Tested]
connections:
  - target: note-taking
    type: derived_from
---

## Purpose

Generates practice questions that mirror exam formats for effective revision.

## Prompt

Generate {{input.question_count}} practice questions in the style of {{input.exam_type}}, based on the structured notes and flashcards produced in the previous stages. The module name and topic are carried forward from Stage 1. Include a mix of question types: multiple choice, short answer, and essay questions. For each question, provide a model answer and mark scheme. Ensure questions test different levels of understanding: recall, comprehension, application, and analysis.
