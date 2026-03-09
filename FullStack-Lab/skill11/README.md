# Experiment 11 - React Fetch API & Axios

## Aim
To build a React application that fetches data from local JSON, a REST API, and a third-party fake API using Fetch and Axios.

## Tech Used
- React 19
- Vite
- React Router DOM
- Axios

## How to Run

```
npm install
npm run dev
```

Then open: http://localhost:5173

## Pages

| Route | Component | Description |
|-------|-----------|-------------|
| / | Dashboard | Navigation links |
| /local-users | LocalUserList | Loads from public/users.json |
| /users-api | UserList | Fetches from jsonplaceholder.typicode.com/users |
| /fake-posts | FakePostList | Fetches from dummyjson.com/posts using Axios |

## Project Structure

```
src/
  App.jsx
  main.jsx
  App.css
  index.css
  components/
    Dashboard.jsx
    LocalUserList.jsx
    UserList.jsx
    FakePostList.jsx
public/
  users.json
```
