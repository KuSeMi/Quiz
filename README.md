# QuizApp

A simple quiz application built with Vue 3 and Vite.

## Live Demo

You can try out the live application [here](https://kusemi.github.io/Quiz/).

## Features

- Display a list of quizzes from a local data source.
- Select a quiz to start answering questions.
- Progress through the quiz questions one by one.
- View your score and results at the end of the quiz.

## Technologies Used

- [Vue 3](https://vuejs.org/) (^3.5.18)
- [Vite](https://vitejs.dev/) (^7.0.6)
- [Vue Router](https://router.vuejs.org/) (^4.5.1)
- [GSAP](https://gsap.com/) (^3.13.0) for animations.

## Project Setup

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/KuSeMi/Quiz.git
    cd Quiz
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