# QuizApp
Full Stack Web Application - Online Quiz Application using MVC Architecture 

Aim:

   To develop a full stack web application for conducting On-line quiz using MVC architecture. The application should facilitate the normal and admin users to access it.  To the normal user, instructions, questions with options and the score needs to be provided as the following snapshots. Admin user can view the registered users and their scores. 

Design the following:

•	Schema of the necessary MongoDB collections. One of which is shown below

• Create Questions collection in MongoDB as follows to store the information about the students and Questions with choices.

____________________________________________________________________
Question |	Choice_A |	Choice_B |	Choice_C |	Choice_D |	Answer |
____________________________________________________________________


•	Design the application with the necessary endpoints, controllers, collections, and components as a sequence diagram

Do the following operations:

•	Authenticate the user and provide necessary messages

•	Keep a timer for the Quiz

•	Sending appropriate GET http requests from front end, to the endpoint in the node server.

•	Perform necessary operations in the Mongo Collection at the endpoints

•	Create a suitable interface in ReactJS to display the results

quiz:- The questions is added and stored by the admin for the users to play the game.

quizAdmin:- Admin’s login credential.

quizUsers:- User’s login credentials(created by signing up in the app).

quizResults:- User’s results are stored for the admin to view the results of the users who all have played and their score.

In the React App,

•	MainRouter.js communicates with the database and server.js

•	Server.js communicates between MainRouter and the Frontend(App.js)

•	MainModel.js is to connect to the database and the collections inside it.

•	MainController.js validates the login info for User.

•	ResultsPage.js retrieves the results from the quizResults collection and displays it to the admin.

•	App.js is the frontend responsible for showing the UI along with the CSS designs done.

User can,

•	Signup for playing the game

•	Login to play the game(if already signed up)

•	View questions and answer the questions by selecting a choice

•	Switch to the next question

•	See the results of the test taken

Admin can,

•	Login to the admin dashboard

•	Add questions to the game by giving the question and the choices along with the right answer

•	See user results with the username and score in a tabular form

![1](https://github.com/JAANUSSRI/QuizApp/assets/95457059/3da974db-4831-402f-a6a2-be5cfca5fec9)
![2](https://github.com/JAANUSSRI/QuizApp/assets/95457059/975eea0f-5b77-466a-baf1-9c25cda3166e)

![Picture1](https://github.com/JAANUSSRI/QuizApp/assets/95457059/c7e1a1cc-42c7-445c-849d-a3cd064c2395)

ADMIN:

![Picture2](https://github.com/JAANUSSRI/QuizApp/assets/95457059/b433a99b-398f-472b-9efd-3446c6a84c51)
![Picture3](https://github.com/JAANUSSRI/QuizApp/assets/95457059/444e9d9f-90e4-45b9-9e27-ab69b2dca5bc)

Add Question by Admin:

![Picture4](https://github.com/JAANUSSRI/QuizApp/assets/95457059/eaa66240-3870-4f10-a34b-5f2abe81716f)

View Results by Admin:

![Picture5](https://github.com/JAANUSSRI/QuizApp/assets/95457059/cf436d29-1c6e-445b-859e-073e1c460867)

User: 

![Picture6](https://github.com/JAANUSSRI/QuizApp/assets/95457059/f2c60082-74b0-4f95-891c-27d806cf5638)

User Login/Signup:

![Picture7](https://github.com/JAANUSSRI/QuizApp/assets/95457059/bc175f85-d50f-467a-a780-09548b07bafd)
![Picture8](https://github.com/JAANUSSRI/QuizApp/assets/95457059/8ba1762c-17b5-439e-8548-6025ebdc4dff)
![Picture9](https://github.com/JAANUSSRI/QuizApp/assets/95457059/8a6cb5c5-3fa1-43ec-86e3-ec7cd5808d1d)

Right choice:

![Picture10](https://github.com/JAANUSSRI/QuizApp/assets/95457059/0920aae3-b65c-43f9-8227-663a8b45483d)

Wrong Choice: 

![Picture11](https://github.com/JAANUSSRI/QuizApp/assets/95457059/f421cadd-df63-4deb-922d-247c3204736e)
![Picture12](https://github.com/JAANUSSRI/QuizApp/assets/95457059/34437fc5-52e0-4ee7-90ed-b56fa4eb3ad4)


Learning Outcomes:

1)	Full Stack Development: Master building web applications from scratch using ReactJS for frontend and Node.js with Express.js for backend.
2)	MVC Architecture: Understand and implement the Model-View-Controller architecture for organized code structure.
3)	User Authentication: Develop secure login/signup systems for admin and users, ensuring data privacy and access control.
4)	RESTful API Development: Create RESTful API endpoints for user authentication, quiz management, and score updates.
5)	Asynchronous Programming: Learn async/await and Promises for efficient handling of non-blocking operations.
6)	React Component Lifecycle: Utilize useState and useEffect hooks for managing state and side effects in React functional components.
7)	Timer Integration: Incorporate timers to enhance user experience and introduce time-bound challenges.
8)	Error Handling: Implement robust error handling mechanisms at frontend and backend for graceful error management.
9)	CSS Styling: Apply CSS styles effectively for visually appealing UI with responsive layouts and custom button styling.
