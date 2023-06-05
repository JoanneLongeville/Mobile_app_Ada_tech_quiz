# Ada Tech Quizz - a technical quizz Android app for software engineers in the making!

Made with [Marie](https://github.com/MarieKosDuc) and [Jérémy](https://github.com/jeremyzynger) during a four-week sprint [group](https://github.com/adatechschool/projet_collectif_mobile-ada-tech-quizz) [project](https://github.com/adatechschool/-projet_collectif_mobile-ada-tech-quizz-back) at [Ada Tech School](https://adatechschool.fr/), May 2023.

## Project overview

Our guidelines were to create a mobile app, for Android or iOS, with a back-end in Golang.

We chose to create and Android app in Java. Why not Kotlin ? Because it was a student project during our studies, and we saw an opportunity to begin learning Java with a concrete and easy to manipulate graphical result.

## Project review and challenges

We began with a two-week sprint dedicated to creating the front-end part of our app, first using an Open Classrooms tutorial, and then creating our code step by step on our own. By the end of this first iteration, we had a first working MVP: an app in which one could answer technical questions, selecting an answer and seeing if it's the right one, and displaying the total score at the end of the session. For this first sprint, we hardcoded the questions inside the Java code.

We then dedicated one week to creating a back-end API in Golang, combined with a PostgreSQL database storing the questions/answers and the users' data. 
This third week proved to be a challenge since none of us had prior knowledge of Golang, and we struggled with the documentation (especially concerning the workspace organization and GOPATH - we never managed to import local packages, and thus renounced to split our code into packages for better human readability).

During the fourth and last week, we reconciled our back-end and front-end, discovering API calls in Java. We chose to use the Volley library, but struggled to correct the multiple app crashes, due to Android Studio's lack of a user-friendly logging-console. We improved drastically our knowledge of the IntelliJ debugger and finally presented a fully working version by the end of the week.

## Final version

Our final app allows the user to:
- create an account
- log in
- answer series of 10 technical questions
- get their last score, best score, and total score (total points earned since account creation, total questions answered)
- play again to earn more points!

## Screenshot

Log in screen

![Log_in](https://github.com/JoanneLongeville/Mobile_app_Ada_tech_quiz/assets/103690254/c31f3ad2-9839-4b91-be18-e7ecbd7b287a)

Sign up screen

![Sign_up](https://github.com/JoanneLongeville/Mobile_app_Ada_tech_quiz/assets/103690254/ccf1e6ec-523a-47f5-a12d-945f186afc17)

Question

![Question](https://github.com/JoanneLongeville/Mobile_app_Ada_tech_quiz/assets/103690254/650abd46-2203-404a-b9a9-6d9d988e7653)

Right answer

![Right_answer](https://github.com/JoanneLongeville/Mobile_app_Ada_tech_quiz/assets/103690254/dab2330b-de79-46cc-bbf8-0b38d2429229)

Final score

![Score](https://github.com/JoanneLongeville/Mobile_app_Ada_tech_quiz/assets/103690254/583ef691-9481-4500-bb62-31255123ae62)
