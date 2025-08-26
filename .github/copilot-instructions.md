# Copilot Instructions for AI Coding Agents

## Project Overview
This is a single-file JavaScript/HTML project (`java.html`) containing various small code snippets and exercises. The code is primarily focused on basic arithmetic, time calculations, and simple conditional logic, often with Mongolian comments and variable names.

## Architecture & Data Flow
- All logic is contained within `<script>` tags in `java.html`.
- There are no external dependencies, build tools, or frameworks.
- The project is not modularized; all code is written inline and is either commented out or directly executed in the browser.

## Developer Workflows
- **Run/Debug:** Open `java.html` in a web browser to execute and debug code. Use the browser console for output.
- **Edit:** Directly modify the `<script>` section in `java.html`.
- **No build/test commands** are present or required.

## Project-Specific Conventions
- Variable names and comments may be in Mongolian; preserve this convention when adding new code.
- Code snippets are often written as small, self-contained exercises. Follow this pattern for new additions.
- Use clear, descriptive variable names and inline comments to explain logic, especially for educational purposes.
- Prefer simple, readable JavaScript without advanced ES6+ features unless necessary.

## Integration Points
- No external libraries, APIs, or cross-file communication.
- All logic is local to the browser environment.

## Examples of Patterns
- Time conversion:
  ```js
  let box3 = 3612;
  let hour = (box3 - (box3 % 3600)) / 3600;
  let minute = ((box3 % 3600) - (box3 % 60)) / 60;
  let second = box3 % 60;
  console.log(hour, minute, second);
  ```
- Conditional checks:
  ```js
  let number = 25;
  if (number % 5 == 0) {
    console.log("Тоо 5-д хуваагддаг");
  } else {
    console.log("Тоо 5-д хуваагддаггүй");
  }
  ```

## Key File
- `java.html`: Contains all code and should be the focus for any changes or additions.

---

If any conventions or workflows are unclear, please ask for clarification or provide examples from the codebase to improve these instructions.
