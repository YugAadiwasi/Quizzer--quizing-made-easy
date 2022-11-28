# Quizzer - quizzing made easy

## Table of Contents 📕

- [About the Challenge](#tally-codebrewers-2022)
- [Tools And Technologies](#tools-and-technology)
- [Features](#features-)
  	- [Homepage](#homepage)
  	- [Dashboard](#dashboard)
  	  - [Create Quiz](#create-quiz)
  	  - [Quiz History](#quiz-history)
  	- [Quizzing Window](#quizzing-window)
  	- [Scorecard](#scorecard)
  	- [Statistics](#statistics)
- [Future Work](#future-work)
- [Contributing Guidelines](#contributing-guidelines)
- [Installation or Dev Setup](#setting-up-the-repository-locally)
- [Gallery](#gallery)
- [Database Schema](#database-schema)
#  Tally CodeBrewers-2022
* The Challenge
	* Build a Quiz Organizing Platform
	* Essential features which were expected
	   1. Quiz Admin Register, and Sign In flow 
	   2. Quiz Admin can publish a quiz.
	   3. Quiz taker can attempt a quiz using a shared link. 
	   4. Score of all participants for a quiz to be available to quiz admin at the end of quiz
	* Detailed View of the Problem Statement can be found [here](https://mirror1.tallysolutions.com/Downloads/office/ProblemStatement_CommanderofFullStack.pdf)


## Tools and Technology

The front end is created in **React.js** and **Material UI**. For creating backend, we used **Nodejs**. For the database, we used Google Firebase. We created a very flexible and versatile foundation for our codebase, so that in future its functionality could be easily extended and new agents could be easily added into it.

# Features :

## Homepage
* Login/Signup 
	* Users can login/signup via Google Sign in or email. 

## Dashboard

#### Create Quiz 
   * Quiz Admin can create and schedule multiple quizzes.
   * Quiz Admin vary weightage of each questions.
   * Quiz Admin can add and email participants of the quizzes.
   
####  Quiz History
   * Quiz Admin can see status of all quizzes created till then.
   * Quiz Admin can Add/Delete questions from any quiz.
   * Quiz Admin can reschedule any quiz.
   * Quiz Admin can terminate any quiz.
   * Quiz Admin can add more participants to any non terminated quiz.
   * Quiz Admin can see realtime results of any created quiz. 

## Quizzing Window
  * Quiz Takers can access this window through URL mailed to them.
  * Quiz Takers can only attempt the quiz withing the time slot assigned by the Quiz Admin.
  * Quiz Takers will get realtime summary of their attempt.
  * Quiz Takers can re-attempt any unsubmitted quiz if any network failure occurs.
  * Quiz Takers will get the results instantly after their successfull submission.
  * Quiz Takers responses will be valid only if they were submitted with the allotted time duration.

## Scorecard
  * Quiz Admins can see realtime score of all participants of any quiz. 
  * Quiz Admins can search for score of any participant through participants name.
  * Quiz Admins can sort result on the basis of  score.

## Statistics
  * Quiz Admins can see realtime stats of all created quizzes.
  * Quiz Admins can search for any quiz stat through quiz title.
  * Quiz Admins can sort quiz on the basis of average score, highest score and number of participants.

## Future Work
  * Auto Adding Participants using CSVs
    * Quiz Master will be able to directly add participants instead of manually entering 
everyone.
* Timer per questions
	*	In addition to overall time duration, time per question can also be fixed by Quiz Master
* Prompt users for marked/ unattempted question
	* Before submitting the quiz, participants will get prompted for marked & unanswered questions
* Showing Detailed Statistics 
	* Detailed statistics related to quiz like maximum marks, lowest marks, average marks etc.
* Prompt users for terminated Quizzes.
	* If an quiz is terminated while a participant is attempting quiz, he/she will be prompted that quiz is over
* QuizMasters can share realtime clarifications.  
	* Quiz Masters will be able to share any clarifications regarding quiz or any question that they have
# Gallery

|||
|:-------------------------:|:-------------------------:|
|<img width="1604" alt="login" src="https://github.com/YugAadiwasi/Quizzer--quizing-made-easy/blob/main/images/login.png">  Login Page |  <img width="1604" alt="register" src="https://github.com/YugAadiwasi/Quizzer--quizing-made-easy/blob/main/images/register.png"> Register |
|<img width="1604" alt="Homepage" src="https://raw.githubusercontent.com/MiHarsh/Tally-Quizzer/main/images/home.png"> Homepage|<img width="1604" alt="dashboard" src="https://github.com/YugAadiwasi/Quizzer--quizing-made-easy/blob/main/images/dashboard.png"> Dashboard |
 <img width="1604" alt="create new quiz" src="https://github.com/YugAadiwasi/Quizzer--quizing-made-easy/blob/main/images/create-quiz.png">Create/Edit a Quiz|<img width="1604" alt="view-quiz-History" src="https://github.com/YugAadiwasi/Quizzer--quizing-made-easy/blob/main/images/quiz-history.png"> View Quiz History|
|<img width="1604" alt="View-participants" src="https://github.com/YugAadiwasi/Quizzer--quizing-made-easy/blob/main/images/view-participants.png"> Add/View Participants |  <img width="1604" alt="view statistics" src="https://github.com/YugAadiwasi/Quizzer--quizing-made-easy/blob/main/images/view-stats.png"> Statistics Page|
<img width="1604" alt="view-score-card" src="https://github.com/YugAadiwasi/Quizzer--quizing-made-easy/blob/main/images/score-card.png"> View Score Card| <img width="1604" alt="mail test link" src="https://raw.githubusercontent.com/MiHarsh/Tally-Quizzer/main/images/quizmail.png"> Mail Test Link|
<img width="1604" alt="view-instructions-page" src="https://github.com/YugAadiwasi/Quizzer--quizing-made-easy/blob/main/images/instructions-page.png"> Instructions Page| <img width="1604" alt="instant score release" src="https://github.com/YugAadiwasi/Quizzer--quizing-made-easy/blob/main/images/instant-score-release.png"> Instant Score Release|
<img width="1604" alt="quizzing-window" src="https://github.com/YugAadiwasi/Quizzer--quizing-made-easy/blob/main/images/quizzing-window.png"> Quizzing Window| 
