# Weather Data Pipeline

A **Trello-inspired task management application** built with modern web technologies, allowing users to create, organize, and manage tasks on customizable boards. Designed to demonstrate full-stack development skills, responsive design, and secure user authentication.

---

## 🌐 Features

- **Boards & Tasks**: Create multiple boards and add tasks to lists within boards.
- **Responsive Design**: Built with **Tailwind CSS** for mobile-first and responsive layouts.
- **Authentication**: Secure user authentication and management using **Clerk**.
- **Interactive UI**: Drag-and-drop task reordering, smooth transitions, and intuitive layout.
- **Real-time Updates**: Changes to boards and tasks are reflected immediately for the user.

---

## ⚙️ Tech Stack

- **Frontend**: Next.js, React, TypeScript, Tailwind CSS
- **Backend**: Node.js, API routes via Next.js, database integration
- **Database**: PostgreSQL / MySQL (your setup)
- **Authentication**: Clerk
- **Version Control**: Git & GitHub

---

## 🚀 Installation

1. **Clone the repository**
```
git clone https://github.com/yourusername/trello-clone.git
```

```
cd trello-clone
```
2. **Install dependencies**

```
npm install
# or
yarn install
```
3. **Configure environment variable. Create a .env.local file in the root with your configuration:**

```
DATABASE_URL=your_database_url
CLERK_FRONTEND_API=your_clerk_frontend_api
CLERK_API_KEY=your_clerk_api_key
```

4.**Run the development server**

```
npm run dev
# or
yarn dev
```
5.**Open http://localhost:3000 to view the project**
