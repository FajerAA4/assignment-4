# AI Usage Report

## Overview

This document describes how Artificial Intelligence (AI) tools were used responsibly and ethically during the development of this project.

AI was used as a **An assistant**, not as a replacement for understanding or original work.
---

## Tools Used

| Tool | Purpose |
|------|---------|
| ChatGPT (GPT-5) | Code explanation, debugging, documentation, design guidance |

---

## Use Cases

### 1. Code Generation

AI was used to generate **initial drafts** and example logic for:

- Project filtering and sorting logic
- Event handling patterns
- API request handling
- `localStorage` usage
- Basic UI logic structure

All generated code was:
- Reviewed
- Modified
- Simplified
- Tested

before being included in the final version.

---

### 2. Debugging

AI assisted in identifying and resolving:

- Filtering logic errors
- UI state bugs
- Theme persistence issues
- Multiple event listeners firing incorrectly
- Layout problems on small screens

Diagnoses from AI were checked and implemented manually.

---

### 3. Code Review & Optimization

AI was used to:

- Identify unnecessary logic
- Improve function clarity
- Reduce UI glitches
- Improve runtime behavior
- Suggest structural code improvements

---

### 4. Documentation

AI assisted in writing and organizing:

- README.md
- Technical documentation
- AI usage report

All documentation was verified and rewritten.

---

### 5. UI/UX Design

AI provided suggestions related to:

- Color design
- Button styling
- Layout consistency
- Spacing

---

## AI Interaction Log

### Prompt 1
> "My tag button always shows an alert when clicked."

**AI Output:**  
Suggested removing inline JavaScript alerts.

**My Modifications:**
- Removed inline scripting
- Refactored logic into a function
- Improved variable naming

**What I Learned:**
- Why inline JavaScript is discouraged
- Better state handling

---

### Prompt 2
> "The filter options go off-screen on mobile. How do I fix it?"

**AI Output:**  
Recommended changing layout direction.

**My Modifications:**
- Implemented grid layout
- Adjusted spacing
- Fixed overflow issues

**What I Learned:**
- CSS media queries
- Grid vs Flexbox
- Mobile-first layout design

---

### Prompt 3
> "Does reducing image size in CSS reduce file size?"

**AI Output:**  
Explained render size vs file size.

**My Modifications:**
- Converted images to WebP
- Added lazy loading
- Optimized image dimensions

**What I Learned:**
- Browser loading mechanics
- File vs render optimization
- Web image formats

---

### Prompt 4
> "User name still appears after logout."

**AI Output:**  
Advised clearing localStorage.

**My Modifications:**
- Cleared specific values only
- Updated UI immediately
- Restarted session logic

**What I Learned:**
- State synchronization
- Browser storage behavior
- Event chains

---

### Prompt 5
> "Login buttons don't visually match the UI theme."

**AI Output:**  
Suggested translucent button style.

**My Modifications:**
- Styled buttons consistently
- Improved layout spacing
- Refined gradients

**What I Learned:**
- Visual hierarchy
- UI design principles
- Button design

---

### Prompt 6
> "Cursor glitch occurs when filtering."

**AI Output:**  
Identified excessive transitions.

**My Modifications:**
- Removed global transitions
- Reduced transform usage
- Improved field stability

**What I Learned:**
- Render-performance tradeoffs
- Input UX optimization
- Hardware acceleration issues

---

## Benefits

Using AI resulted in:

- Faster debugging
- Cleaner code
- Better documentation
- Improved design decisions
- Faster learning

---

## Challenges

| Challenge | Resolution |
|----------|------------|
| AI suggested outdated syntax | Refactored manually |
| Overcomplicated logic | Simplified |
| Inconsistent CSS values | Tuned manually |

---

## Ethics & Responsibility

AI was used in an ethical manner:

- No plagiarism
- No blind copying
- No misrepresentation
- All code tested
- All output verified

---

## Understanding & Modification

All AI output was:

- Read
- Tested
- Modified
- Rewritten
- Understood

---

## Learning Outcomes

Through AI-assisted development:

- Stronger debugging skills
- Clearer system thinking
- Better UI/UX design
- Ethical AI usage

---

## Conclusion
AI helped guide development and learning but did not create the project for me.  
Final implementation was tested, refined, and is fully understood.