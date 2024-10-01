Setup the Project by Creating a new Next JS project.
we will be using useState hook to manage the quiz state, including the current question, selected answer, and quiz results.
We will utilize Bootstrap to style our Quiz App.
Create a new QuestionSet.js file under Data folder where we will define the questions along with options and answers.
We will be creating different components for code readability and reusability. here we will be creating components such as Quiz to render the different questions and ScoreCard to display the result analysis.
Quiz app will start with taking user’s name once we click on start quiz button App component will render the Quiz component which is responsible to display the questions one by one.
After submitting the test ScoreCard component will be rendered which will display the result analysis including score, correct answers, wrong answers, percentage and status.
