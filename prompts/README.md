# Prompt Library

This document records all prompts that was used to create Amazing Bank's Digitial Banking System

## Business Requirements

### 01. Create the Core-Banking System requirement overview

```plaintext
Read the content from requirements/README.md
Write a requirement overview for Core Banking System in requirements/core-banking/README.md
- include a Overview of a typical core banking system for a digitial bank
- include a architecture description and diagram for the core banking system
- inlcude a scenario list in a table format
```

output: [](../requirements/core-banking/README.md)

ref: [cline task](./cline_task_exports/cline_task_mar-11-2025_6-15-33-am.md)

### 02. PRD document generation

reference:
- https://www.productplan.com/glossary/product-requirements-document/

> replace <doc_path> with action prd_xxx.md filename, e.g. requirements/core-banking/prd_account_creation.md

```plantext
write a Product Requirement Document (PRD)for Account Creating sceanrio in <doc_path>
read the following docs for reference
requirements/core-banking/README.md
requirements/README.md

Make sure your PRD include the following sections

- Objective/Goal: Explain why are you building this and what do you hope to accomplish.

- Features: For each feature, you should include a description, goal and use case at a minimum. Additional details may be helpful or necessary depending on the complexity of the feature, such as out-of-scope items.

- UX Flow & Design Notes: Most organizations complete the UX design of features after the PRD has been reviewed and accepted. However, there may be some general guidance required at this stage to ensure the release objectives are met. This is not the place for pixel-perfect mockups or wireframes that map out every possible scenario; instead, it can be used to describe the overall user workflow. Use UML diagram where possible to illsutrate the user workflow, use porper mermaid format.

- System & Environment Requirements: Which end-user environments will be supported (such as browsers, operating systems, memory, and processing power, etc.).

- Assumptions, Constraints & Dependencies: List out what is expected of users, any limits for the implementation to be aware of and any outside elements required for the final solution to be functional.

```

output: [](../requirements/core-banking/prd_account_creation.md)

ref: [cline task](./cline_task_exports/cline_task_mar-11-2025_6-55-42-am.md)

## Frontend

### 01. Create the website

Enter this prompt in https://blot.new 

```plaintext
create a web application using Vite + React + Tailwind
this is a website for a bank called The Amazing Bank
use modern and profesional look and feel
add necessary sections for a typicial banking website
```

## Bankend


