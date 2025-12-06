// ...existing code...
# Todo App (React + Vite)

A simple Todo application built with React and Vite. It demonstrates basic state management, component composition, and styling with CSS + Bootstrap.

## Features
- Add todo items with a due date.
- Delete todo items.
- Empty-state welcome message.
- Uses Bootstrap for basic styling.

## Quick start

1. Install dependencies:
```sh
npm install
```

2. Run development server:
```sh
npm run dev
```

3. Open the app in your browser (Vite will show the URL, usually http://localhost:5173).

4. Build for production:
```sh
npm run build
```

## Important files & components
- Entry point: [src/main.jsx](src/main.jsx) — uses [`App`](src/App.jsx).
- Main app: [`App`](src/App.jsx) — [src/App.jsx](src/App.jsx)
- Components (in [src/components](src/components)):
  - [`AddTodo`](src/components/AddTodo.jsx) — input form
  - [`AppName`](src/components/AppName.jsx) — header
  - [`TodoItems`](src/components/TodoItems.jsx) — list container
  - [`TodoItem`](src/components/TodoItem.jsx) — individual item
  - [`WelcomeMessage`](src/components/WelcomeMessage.jsx) — shown when list is empty
- Styles:
  - [src/App.css](src/App.css)
  - component CSS modules in [src/components](src/components)

## How the app works (brief)
- `App` holds the todo list state and passes handlers to child components.
- `AddTodo` calls the `onNewItem` prop to add an item.
- `TodoItems` receives `todoItems` and `onDeleteClick` to render and remove items.
(See code in [`App`](src/App.jsx) and the component files linked above.)

## Notes
- Uses Bootstrap CSS imported in [src/main.jsx](src/main.jsx).
- This repo was scaffolded with Vite and includes ESLint config.

## Contact / Contribute
Open issues or send PRs. Keep changes small and focused.

// ...existing code...
