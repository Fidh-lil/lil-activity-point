# Pointly - Activity Points Management System

A front-end React application for students to track co-curricular, extra-curricular, technical, professional, social and leadership activities.

## Features

- Student login using sample credentials from `src/data/students.json`
- Dashboard with total, target and remaining activity points
- Activity list with category filters and approval status
- Add activity form with local state and review status
- Category browser and student profile summary
- JSON files used as the sample data source
- React Router navigation and GitHub Pages-ready routing

## Run locally

```bash
npm install
npm run dev
```

Demo login: `22CSE1047` / `student123`

## Build and deploy

1. Create a GitHub repository and push this project.
2. Run `npm run deploy` to publish the `dist` folder through the `gh-pages` package.
3. In GitHub repository settings, choose the `gh-pages` branch as the Pages source.

The app uses `HashRouter`, so navigation also works when a GitHub Pages project site is hosted under a repository path.
