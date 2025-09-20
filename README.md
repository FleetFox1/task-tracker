# TaskTracker

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 20.2.1.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
# Task Tracker: Modular Project Playground

## Vision
A productivity app that lets you track, organize, and optimize all your projects like building with LEGO bricks. Stack, merge, and arrange projects and tasks visually. AI-generated roadmaps and Google Calendar integration help you work smarter, not harder.

## Features
- **Project Tracking:** Create, edit, and organize multiple projects. Each project has a progress bar and task list.
- **AI Roadmaps:** Automatically generate step-by-step roadmaps for each project using AI.
- **Project Merging:** Combine projects, merging their tasks and progress.
- **Google Calendar Sync:** Connect your calendar to schedule optimized work sessions for each project.
- **Modular UI:** Drag, stack, and arrange projects and tasks like LEGO bricks. Flexible, visual organization.


## Tech Stack & Best Practices
- **Angular 17+** (standalone components, signals, computed, inject)
- **TypeScript** (strict types, type inference, no any)
- **State Management:** Signals for local/component state, computed for derived state
- **Reactive Forms** for all user input
- **Change Detection:** OnPush for all components
- **Native Control Flow:** @if, @for, @switch in templates
- **Services:** Single responsibility, providedIn: 'root', inject() for DI
- **AI Integration:** Service/API for roadmap generation
- **Google Calendar Integration:** OAuth, scheduling logic

### Resume & Learning Highlights
- **PostgreSQL + Auth0:** Powerful, industry-standard combo for full-stack apps. Shows expertise in relational data and secure authentication.
- **Supabase:** Modern, open-source, trending. Demonstrates cloud database and real-time skills.

## Getting Started
1. Clone the repo
2. Install dependencies: `npm install`
3. Run the app: `npm start`

## Roadmap
- [ ] Project CRUD
- [ ] Progress bar component
- [ ] AI roadmap service
- [ ] Project merge feature
- [ ] Google Calendar sync
- [ ] Modular drag-and-drop UI

---

Ready to build brick by brick!
