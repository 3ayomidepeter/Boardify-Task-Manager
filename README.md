# Boardify Task Manager

Boardify Task Manager is a full-featured, collaborative task management application inspired by Kanban-style workflows. It enables individuals and teams to easily organize, track, and manage tasks across multiple boards and lists.

## Features

- **Kanban Boards:** Organize tasks into boards and lists for clear workflow management.
- **Task Management:** Create, update, assign, and comment on tasks.
- **Due Dates & Labels:** Set due dates, priorities, categories, or custom labels.
- **User Collaboration:** Assign tasks to team members, track progress, and communicate within tasks.
- **Drag and Drop:** Seamlessly move tasks between lists or boards with an intuitive drag-and-drop interface.
- **Notifications:** Get real-time updates for task changes, assignments, and deadlines.
- **Activity Feed:** View recent activity on boards and tasks for transparency.

## Screenshots

![Board Screenshot](./docs/screenshots/board.png)
![Task Detail Screenshot](./docs/screenshots/task-detail.png)

## Getting Started

### Prerequisites

- Node.js (v16 or newer)
- npm or yarn
- MongoDB/PostgreSQL (if using a database backend)
- [Optional] Docker for containerized development

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/3ayomidepeter/Boardify-Task-Manager.git
   cd Boardify-Task-Manager
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```
   or
   ```sh
   yarn install
   ```

3. **Configure environment variables:**
   - Copy `.env.example` to `.env` and update values as needed.

4. **Run the application:**
   ```sh
   npm start
   ```
   or
   ```sh
   yarn start
   ```

   The app will be available at `http://localhost:3000`.

### With Docker

```sh
docker compose up
```

## Usage

- Sign up or log in.
- Create a board for your project or workflow.
- Add lists (columns) representing stages (e.g., To Do, In Progress, Done).
- Create tasks, assign them, set due dates, and drag-and-drop between lists.

## Project Structure

```
/src
   /components
   /pages
   /api
   /utils
/tests
/public
```

- `components/`: Reusable UI components
- `pages/`: Application routes/pages
- `api/`: API route handlers or backend services
- `utils/`: Utility/helper functions
- `tests/`: Unit and integration tests

## Environment Variables

List the necessary environment variables in a `.env.example` file, e.g.:
```
DATABASE_URL=mongodb://localhost:27017/boardify
JWT_SECRET=your_jwt_secret_here
PORT=3000
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create your branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).



---

*Happy organizing! 🚀*
