# Moodo — Mood-Based To-Do App (Module 02)

Static HTML/CSS foundation for a mood-based to-do application, built for the
Metana Full-Stack Bootcamp. This module covers the **static pages and reusable
components**; functionality is added in Module 03.

## What it does (the idea)

You pick how you're feeling, and the app suggests tasks that fit your mood and
the current weather — alongside your normal to-do list.

## Project structure

```
mood-based-todo-app/
├── index.html                     # Home page (dashboard)
├── README.md
├── Assets/
│   ├── logo.svg
│   └── sun.svg
├── Components/
│   ├── taskComponent.html         # Reusable task card
│   ├── suggestedTaskComponent.html# Mood/weather-based suggestion card
│   ├── taskCreationForm.html      # "Create a task" form
│   ├── moodSelecterForm.html      # Mood selector (button group)
│   └── loginForm.html             # Login page
└── Styles/
    ├── index.css
    ├── login.css
    ├── loginForm.css
    ├── tasksComponent.css
    ├── suggestedTaskComponent.css
    ├── taskCreationForm.css
    └── moodSelecter.css
```

## Pages & components

| File | Description |
|------|-------------|
| `index.html` | Home dashboard: task list, "Add task" + "Set my mood" buttons, and a suggested-tasks panel. |
| `Components/taskComponent.html` | A single task card with title, description, due date, and edit / complete / delete actions. |
| `Components/suggestedTaskComponent.html` | A suggestion card showing why a task was recommended (mood + weather). |
| `Components/taskCreationForm.html` | Form with title, description (optional), and due date fields plus an "Add task" button. |
| `Components/moodSelecterForm.html` | Happy / Neutral / Sad selector built from accessible radio buttons. |
| `Components/loginForm.html` | Login screen with username/email + password fields and a log-in button. |

## Design notes

- **Theme:** warm cream background, coral accent, mood-coded colours
  (happy = yellow, neutral = blue, sad = purple).
- **Fonts:** Fraunces (headings) + DM Sans (body), loaded from Google Fonts.
- **Responsive:** built with CSS Flexbox and Grid. The home page collapses from
  two columns to one on tablets, and buttons/forms go full-width on mobile.
- Each component lives in its own HTML file and can be previewed on its own.

## How to view

Open `index.html` in any browser, or open any file in the `Components/` folder
to preview that component individually. No build step required.

## Screenshots

_Add screenshots or a live demo link here (optional)._
