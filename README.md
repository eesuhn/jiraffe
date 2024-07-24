## Jiraffe

<img src="./preview.png" alt="screenshot1" width="700" /> <br>

<b>Jiraffe</b> is a task management tool that allows users to create projects and assign tasks to members <br>

<i>Now live on Vercel!</I> <br>
<b>https://jiraffe.vercel.app/</b> <br>

### Features

- Track tasks in a project
- Assign members to tasks

### Built With

[![React](https://img.shields.io/badge/React-23272f?style=for-the-badge&logo=react)](https://react.dev/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-f8fafc?style=for-the-badge&logo=tailwindcss)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-ffd028?style=for-the-badge&logo=Vite)](https://vitejs.dev/)
[![Express](https://img.shields.io/badge/Express-010409?style=for-the-badge&logo=express)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-001e2b?style=for-the-badge&logo=mongodb)](https://www.mongodb.com/)

### Running it locally...

1. Install dependencies in `backend/`
	```bash
	cd backend/
	npm i --force
	```

2. In a new terminal, navigate to `frontend/` and install dependencies
	```bash
	cd frontend/
	npm i --force
	```

3. Rename `sample.env` to `.env` for both `backend/` and `frontend/`

4. In `backend/.env`, set the following environment variables:
	```properties
	MONGODB_URI=
	JWT_SECRET=
	```

5. Start the backend server
	```bash
	cd backend/
	npm run start
	```

6. In a new terminal, start the frontend server
	```bash
	cd frontend/
	npm run dev
	```

### Contributors

- [ChiefWoods](https://github.com/ChiefWoods)
- [Karweiii](https://github.com/Karweiii)
- [eesuhn](https://github.com/eesuhn)
- [CWeyK](https://github.com/CWeyK)
