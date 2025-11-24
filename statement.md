
Problem Statement- We have to Develop a Python program that implements a command-line-based quiz game. The program should:
                      Store Quiz Data: Define a collection of quiz questions, each with corresponding multiple-choice options and a single correct answer of its own
                       Present Questions: Display each question and its options to the user sequentially, appearing distinctly
                         Accept User Input: Prompt the user to enter their chosen/ thought answer.
                         Evaluate Answers: Compare the user's response  against the correct answer for each question.
                        Provide Feedback: Inform the user immediately whether their response is correct or incorrect.Manages Time
                        Track Score: Maintain a running score based on the number of correct answers, therby keeping a track of the game.
                        Display Final Results: At the end of the quiz, present the user's total score and the percentage of correct answers.
                        the user is rewarded prize money based on the number of correct answers.
Scope Of The Project-The scope of a project for a quiz game program in Python can be defined by considering its core functionalities and potential enhancements. These add on to the 
accesibility and scalability of it;
           Core Functionalities:
                     Question and Answer Management:
                                                      Storing questions and their corresponding multiple-choice options.(Possible Solutions)
                                                       Storing the correct answer for each question.(Reference Answer Booklet)
                                                       Loading questions from a data source (e.g., a Python list, dictionary, or an external file like CSV or JSON).(Source Of Questions)
                         User Interface:
                                                       Displaying questions and options clearly to the user.(Which will help us to get clear response)
                                                        Prompting the user for their answer input.(Taking Response from user)
                         Game Logic:
                                                        Checking if the user's answer is correct or incorrect.
                                                        Keeping track of the user's score.(Initilization Of Counter Variable for score as for calculation of final reward)
                                                        Providing immediate feedback to the user after each answer.(If The answer is correct , the counter adds to the no of correct questions)
                                                        and prize money gets on increasing
                                                        Otherwise when we encounter incorrect answer the program is terminated , and as per the number of correct questions the user is
                                                        rewarded
                                                        Handling game flow (e.g., moving to the next question, ending the quiz).The counter keeps the track of the game and based on the 
                                                        correct/incorrect condition the game progresses thereby
                                                        Score Display:Presenting the final score to the user at the end of the quiz.(The result is based on the responses that were recieved
                                                         from the user"s end)

               Potential Enhancements (Expanding the Scope):
                                       Multiple Quiz Topics: Allowing users to choose from different categories of quizzes.
                                        User Profiles and High Scores: Implementing a system to store user names and track high scores.
                                        Timer Functionality: Adding a time limit for answering each question or the entire quiz.
                                         Lifelines/Hints: Incorporating features like "50:50" or "Ask the Audience" for assistance.
                                         Graphical User Interface (GUI): Developing a more visually appealing interface using libraries like Tkinter, PyQt, or Kivy instead
                                         of a command-line interface.
                                         Question Randomization: Shuffling the order of questions for a varied experience.
                                        Detailed Feedback: Providing explanations for correct answers or reasons for incorrect answers.
                                        Persistence: Saving quiz data and user scores to files for later retrieval.(Comparing scores and compilation of results)
                                        Admin Panel: Creating a separate interface for an administrator to add, edit, or delete questions.(This is developer"s options and are hidden from the 
                                      the   knowledge of user, ensuring transparency and credibility)
Target Users-
                       Age Group/Knowledge Level: Determine if the quiz is for children, students, or adults, and adjust question difficulty accordingly.
                       As per this the level of questions is set
                      Subject Matter: Select topics relevant to the target users (e.g., history for history buffs, programming for aspiring coders). As any irrelevant topic may lead 
                      to creation of non-sense questions and disputes.
High Level Features-
                     A Python quiz game program can incorporate various high-level features to enhance user experience and functionality. These features include:
                               Question and Answer Management: The program can store questions, multiple-choice options (if applicable), and correct answers.
                               This data can be stored within the script itself using data structures like lists or dictionaries, or external files like JSON or CSV 
                               for easier modification and expansion.
                              User Interface (UI): For text-based quizzes, the UI involves presenting questions and options clearly to the user and accepting input for answers.The interface
                              as being friendly makes the program more impactful
                              For graphical user interfaces (GUIs), libraries like Tkinter or Pygame can be used to create interactive elements such as buttons, labels, and input fields.
                              Quiz Flow Control: The program manages the progression of the quiz, presenting questions one by one, moving to the next question after an answer is provided
                              and determining the end of the quiz.
                              Answer Validation and Scoring: It checks if the user's answer is correct against the stored correct answer.
                              A scoring system tracks the number of correct answers, providing real-time or end-of-quiz feedback on performance.
                              Randomization: Questions can be presented in a random order to ensure a varied experience with each playthrough.
                              This can involve shuffling a list of question indices.Ending the boring line by line step by step questions answers similar to exams
                              Feedback Mechanism: The program provides immediate feedback after each answer (e.g., "Correct!" or "Wrong answer, the correct answer was...") and a summary
                              of the final score at the end of the quiz.It makes the program more attractive
                              High Score Tracking/Leaderboard: For added engagement, the program can store and display high scores, potentially saving them to 
                              a file for persistence across sessions.It 
                              Customization Options: Advanced features could include allowing users to select quiz categories, difficulty levels, or the number of questions.
                              Error Handling: Robust error handling can be implemented to manage invalid user inputs, ensuring the program does not crash unexpectedly.Whenever an incorrect
                              response comes , the program counter of correct question is displayed , and the equivalent prize money is given to the user.



         
