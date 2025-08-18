# QuizApp

A simple quiz application built with Vue 3 and Vite.

## Features

- Display a list of quizzes from a local data source.
- Select a quiz to start answering questions.
- Progress through the quiz questions one by one.
- View your score and results at the end of the quiz.

## Technologies Used

- [Vue 3](https://vuejs.org/)
- [Vite](https://vitejs.dev/)
- [Vue Router](https://router.vuejs.org/)

## Project Setup

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/QuizApp.git
    cd QuizApp
    ```

2.  **Install dependencies:**
    ```sh
    npm install
    ```

3.  **Run the development server:**
    ```sh
    npm run dev
    ```
    The application will be available at `http://localhost:5173`.

4.  **Build for production:**
    ```sh
    npm run build
    ```
    This will create a `dist` directory with the production-ready files.

## Project Structure

```
/
├── public/
│   └── favicon.ico
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Card.vue
│   │   ├── Question.vue
│   │   ├── QuizHeader.vue
│   │   └── Result.vue
│   ├── data/
│   │   └── quizes.json
│   ├── router/
│   │   └── index.js
│   ├── views/
│   │   ├── QuizesView.vue
│   │   └── QuizView.vue
│   ├── App.vue
│   └── main.js
├── .gitignore
├── index.html
├── package.json
├── README.md
└── vite.config.js
```