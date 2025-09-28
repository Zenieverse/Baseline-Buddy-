# Baseline-Buddy
Baseline Buddy — Real-Time Web Feature Compatibility Assistant. Web developers hesitate to adopt modern web features due to uncertainty about cross-browser support. They waste time jumping between MDN, caniuse.com, and blog posts. Baseline solves this by providing a single source of truth about when features are universally supported. 

https://poe.com/BaselineBuddy


Baseline Buddy is a developer-first toolkit that integrates Baseline web feature data directly into IDEs, linters, and CI pipelines.
Features & Functionality:
IDE Extensions: Inline feedback on web features (hover tooltips + squiggly underlines).
Linting Rules: ESLint/Stylelint plugin that flags unsupported features.
CI/CD Guardrails: GitHub Action to ensure production readiness before deploy.
Analytics Dashboard: Summarizes unsupported/experimental features in a project.
CLI Tool: Run baseline-check to audit repos locally or in pipelines.
Technologies Used:
Baseline data: web-features npm package + Web Platform Dashboard.
IDE Integration: VS Code API (TypeScript).
Linting: ESLint plugin (Node.js).
CI/CD: GitHub Actions (YAML + Node scripts).
Dashboard: React + Vite + Tailwind.
Backend: Node.js (optionally serverless for analytics).

What does your project do?
Baseline Buddy integrates Baseline feature data directly into developer workflows, providing real-time insights in IDEs, automated linting, and CI/CD guardrails to ensure safe adoption of modern web features.
What technologies did you use?
TypeScript, Node.js, React, ESLint, VS Code Extension API, GitHub Actions, and the Baseline web-features package.
What problem does it solve?
It removes uncertainty about browser support, reduces wasted time cross-checking docs, and ensures production code is safe by default.
How is it innovative?
Baseline Buddy is the first tool to combine IDE feedback, linting, CI/CD, and dashboards powered by Baseline’s universal support data, bridging the gap between documentation and actual developer tooling.
How is it scalable?
It’s modular: teams can adopt only the IDE plugin, or extend into CI/CD. The data source (Baseline) is updated globally, so the tool automatically benefits all developers as Baseline grows.

