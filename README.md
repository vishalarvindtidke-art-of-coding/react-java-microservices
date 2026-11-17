
![Screenshot_8](https://github.com/LuisSalas94/Full-Stack-React-Spring-Boot-Student-Management-System/assets/57297709/1a8c8595-ed25-4731-bc93-f248f48aebda)

# Student Management System 📚

A Full-stack web application built using React and Spring Boot for managing student records efficiently. The Student Management System allows users to add, update, and delete student information, along with their respective departments. This system ensures seamless communication between the frontend and backend, providing a user-friendly interface to manage student details.


## Tech Stack 🖥

**Client:** React, Bootstrap, React Router, Axios, Toast Notifications Library

**Server:** Spring Boot, Spring JPA, Spring Web, MySQL


## Key Features 🎇

- Add, update, and delete student records with their first name, last name, email, and department.
- View a list of students with department information.
- Manage departments by adding and updating their names and descriptions.
- Integration of React for the frontend, ensuring dynamic user interfaces.
- Backend powered by Spring Boot, providing RESTful APIs for data manipulation.
- Utilizes Axios for making asynchronous HTTP requests between the frontend and backend.
- Implements React Router for client-side routing, ensuring a smooth user experience.
- Toast notifications for informing users about successful and failed actions.
- Utilizes custom hooks for encapsulating and reusing logic across components.


## Screenshots 🎞
![Screenshot_1](https://github.com/LuisSalas94/Full-Stack-React-Spring-Boot-Student-Management-System/assets/57297709/49a269d1-1f95-4199-bbf4-f315fec957d5)
![Screenshot_2](https://github.com/LuisSalas94/Full-Stack-React-Spring-Boot-Student-Management-System/assets/57297709/6eae9e41-a16f-43fe-b748-fdb63d74e850)
![Screenshot_3](https://github.com/LuisSalas94/Full-Stack-React-Spring-Boot-Student-Management-System/assets/57297709/30c8b70e-f0a0-445f-ae72-788a7a23e8a8)
![Screenshot_4](https://github.com/LuisSalas94/Full-Stack-React-Spring-Boot-Student-Management-System/assets/57297709/1f4c3ac1-cfab-45c0-9b46-b849de22c249)
![Screenshot_5](https://github.com/LuisSalas94/Full-Stack-React-Spring-Boot-Student-Management-System/assets/57297709/2cd0d823-f084-4388-865a-4287693b5937)
![Screenshot_7](https://github.com/LuisSalas94/Full-Stack-React-Spring-Boot-Student-Management-System/assets/57297709/3913298e-b0ce-469a-9683-17872f8e6d22)


## Instructions 🕶
Requires Java 17, Node.js/npm, and a MySQL server with the `e-com` database. The backend defaults to `Mac-mini.local:3306` and username `root`; override these with `DB_URL` and `DB_USERNAME` if needed. Set `DB_PASSWORD` in your shell without committing it to the repository.

Run the backend from one terminal (on macOS zsh, enter the database password when prompted):

```bash
cd backend
read -s "DB_PASSWORD?MySQL password: "
export DB_PASSWORD
sh ./mvnw spring-boot:run
```

Run the frontend from another terminal:

```bash
cd frontend
npm install --registry=https://registry.npmjs.org
npm run dev
```

Open the URL Vite prints (usually http://localhost:3000). Ensure the MySQL server is listening on port `3306` and accepts connections from this machine.

## Contributing 🤝

Contributions, issues, and feature requests are welcome!
Feel free to check the [issues page](../../issues/).


## Show your support

Give a ⭐️ if you like this project!

## License 📝

This project is [MIT](./MIT.md) licensed.  

