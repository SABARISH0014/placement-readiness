# Deloitte USI Technical Challenge

## Overview

This project implements a JSON-driven Dynamic Form Generator using Next.js.

The UI is generated entirely from a schema.json configuration.

Features include:

- Dynamic field rendering
- Nested questionnaires
- Conditional fields
- Validation engine
- Responsive interface

---

## Tech Stack

- Next.js
- React
- JavaScript
- CSS

---

## Folder Structure

code/
components/
hooks/
utils/
data/

---

## Features

✔ JSON Driven UI

✔ Nested Forms

✔ Validation Rules

✔ Conditional Rendering

✔ Responsive Design

---

## Example Validation

Age must be greater than 18.

Company Name appears only when "Employed" is checked.

---

## Architecture

schema.json

↓

DynamicForm

↓

FieldRenderer

↓

Validation Engine

↓

Conditional Engine

↓

Submit Handler

---

## Big-O Analysis

Rendering : O(n)

Validation : O(n)

Conditional Rendering : O(n)

Memory : O(n)

---

## Improvements

- Async validation
- API integration
- Multi-step forms
- Drag-and-drop schema builder

---

## Running

npm install

npm run dev
