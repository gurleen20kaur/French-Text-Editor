# French-Text-Editor

## Overview

- French Text Editor helps users improve their french writing skills
- The application gives users suggestions and corrections based on user input
- This app was made keeping the users interest in mind to help them develop strong l'expression ecrite en Francais

## MVP

- Quill editor
- “Check French” button
- Backend endpoint calls LanguageTool
- Show list of issues in a right sidebar
- Clicking an issue selects that text in Quill
- “Apply suggestion” replaces the text

## Front-End

- React
- Text Editor - Quill.js
- CSS - Tailwind CSS + shadcn/ui

## Back-End

- Node.js + Express
-

## VS Code + extensions:

- ESLint
- Prettier
- Tailwind CSS IntelliSense

## Correction provider API

- LanguageTool (popular, has French; self-hostable; also has cloud)
  Great baseline for grammar/spelling + rule-based suggestions.
- Antidote Web API (excellent French quality, but licensing/enterprise-y)
- LLM approach (OpenAI / etc.)
  Best for style suggestions and explanations, but you must control hallucinations and cost.
