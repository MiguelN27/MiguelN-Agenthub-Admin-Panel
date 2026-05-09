# AI Agent rental platform

## Project overview
Agenthub is building a SaaS platform where companies can rent AI agents - pre-configured intelligent assistants that can be equiped with different skills (capabilites such as browsing the web, reading documents, or managin calendars) and deployed for specific business tasks

## Features
- Using HTML and TailwindCSS via CDN only.
- Sidebar navigation to the following sections:
   - Dashboard
   - User mnagement
   - Agent Management
   - Skills
   - Agent contracts
   - Error Log
- Dark modde toggle in the navbar
   - Utilizing TailwindCSS's `dark:` utility. 

## Data Models

```ts
interface User {
    name: string;
    email: string;
    plan: "Basic" | "Pro" | "Unlisted";
    status: "active" | "unactive";
}
```

## Goals 
- A responsive layout using TailwindCSS delivered via CDN

## Anti-Goals 
- Things that you want to avoid to your project be successful.