
## SoloReview: The Chief Architect in Your Editor 

**Syntax is trivial. Concepts are eternal.**

SoloReview is a VS Code extension designed to break the cycle of "Tutorial Hell." While standard AI tools (like Copilot or ChatGPT) focus on giving you the answer as fast as possible, SoloReview acts as a **Senior Mentor** that forces you to think. It uses the Socratic method to ensure you master the underlying architectural concepts before you ever see a line of refactored code.

### The Problem

Most AI coding assistants are **"Code Generators."** They solve the immediate bug but leave the developer’s knowledge unchanged. This leads to a "copy-paste" workflow where the developer understands the syntax but misses the **mental models** (like Encapsulation, Idempotency, and Coupling) required to reach a Senior level.

### The Solution: SoloReview

SoloReview transforms your editor into a mentorship session. It doesn't just "fix" your code; it critiques your implementation choices and guides you toward architectural mastery through a deliberate, multi-stage feedback loop.

#### Core Features

 **The Socratic Review:** When you ask for a review, the AI identifies a conceptual flaw (e.g., Tight Coupling or State Leakage) and asks a "Why" question instead of providing the fix.
 **The 3-Strike Rule:** You get three attempts to explain your logic. If you struggle, the "Chief Architect" provides a **Conceptual Breakthrough**-an analogy-based explanation followed by the elegant solution.
 **Real-World Context Mapping:** Every solution includes a "In the Wild" section, explaining how this concept applies to production features like Authentication, Payment Gateways, or Real-time Sync.
 **Concept-First Mentorship:** The AI is strictly prompted to use Senior-level vocabulary to build your "Architectural Intuition."

### Tech Stack & Architecture

This project is built with professional-grade standards to demonstrate mastery of the VS Code Extension ecosystem.

**Language:** TypeScript (Strict Mode)
**Runtime:** Node.js
**APIs:** VS Code Extension API (vscode.comments, vscode.workspaceState)
**AI Engine:** OpenAI GPT-4o / GPT-4 Turbo
**Pattern:** Service-Provider Architecture (Decoupling UI from AI Logic)

#### Folder Structure

src/
├── core/              # The "Brain": AI Clients, Prompt Strategies, and History Management.
├── providers/         # The "Hands": VS Code UI integration (Comment Threads).
├── services/          # The "Glue": Orchestration of the mentorship workflow.
├── types/             # The "Rules": Type safety and interface definitions.
└── extension.ts       # The "Entry Point": Extension lifecycle management.

### Installation and Setup

#### Prerequisites

[https://VSCode]
[https://Node.js] v18 or higher
An OpenAI API Key

#### Getting Started

1. Clone the repository:
git clone [https://github.com/suleimani1/soloreview.git]
2. Install dependencies:
npm install
3. Open the project in VS Code and press F5 to start the **Extension Development Host**.
4. In the new window, go to **Settings** (Cmd/Ctrl + ,) and search for SoloReview.
5. Enter your **OpenAI API Key**.

#### How to Use

1. Highlight a block of code you want to master.
2. Right-click and select **"SoloReview: Ask Chief Architect for Review".**
3. Engage with the Senior Dev in the comment thread in your margin.

### Engineering Concepts Covered

By using SoloReview, you will master:
**Synchronization vs. State:** Handling side effects in modern UI frameworks.
**Memory Management:** Identifying and preventing state leaks.
**Composition over Inheritance:** Building flexible, reusable systems.
**Idempotency:** Designing reliable API and function calls.
**Separation of Concerns:** Decoupling business logic from presentation.

### License

This project is licensed under the **MIT License** - see the LICENSE file for details.

### Author

**SELEMANI RAMADHANI** 
Email: <jumaamshakamai@gmail.com>
Repository : <https://github.com/suleimani1/soloreview.git>

#### Senior Developer's Note

> "This project was built to solve my own frustration with AI-assisted learning. It proves that the 
        > best way to learn to build a system is to build a tool that understands systems."
