Harry Potter Sorting-Hat Web App


This project is designed to creat a dynamic and interactive page for the user. I have use Javascript, HTML, and CSS to create a dynamic app that will sort any name that a user types in. When the user activates the sort button, my Js dynamically prints a card with the user's desired name, and a random Howarts house for that user's desired name. 


No wireframes were used for this project.

Link to the deployed project (will learn in week 5)

https://ben-jarrett-sorting-hat.netlify.app/


https://github.com/BenJarrett/sorting-hat/projects/1


The ideal user for this application is a teacher
They have students in their classrooms that they would like to put into random groups and they have a love and passion of Harry Potter
The problem this app solves for them is it allows them to get their students involved and excited about being in random groups. The students have felt that the groups have not been so random and based on favorites.

Features

List of features
- Dynamically controlled form by the user
https://github.com/BenJarrett/sorting-hat/blob/main/Sorting-hat-form-button-1.png
https://github.com/BenJarrett/sorting-hat/blob/main/Sorting-hat-form-button-2.png

- User can add and sort any name they would like to type in. This will create a card that contains the name and the randomized house assigned of the name entered. 
https://github.com/BenJarrett/sorting-hat/blob/main/sorting-hat-cards.png

- User can delete any card previously created by clicking the "Expel!" button located in the individual cards.
Delete Card.PNG
https://github.com/BenJarrett/sorting-hat/blob/fa01b4e0c2ddb85584fb25cea5806e10fca6b364/Delete%20Card.PNG


Ben Jarrett is the only contributor.

https://github.com/BenJarrett



https://www.loom.com/share/020cd80eb02e4081a7d178fb12a358ac


https://ben-jarrett-sorting-hat.netlify.app/

Below shows the original requirement to complete this project
Technical Requirements
You MUST plan your project and create issue tickets and a project board fro your project
You MAY use the printToDom() function that we worked on in class, but you also need to be able to explain it if you use it
You have to create a data structure for your project. Review all the elements that need to be on the DOM and create the structure accordingly
You must use Boostrap to style your page components
You must use a loop other than a for loop
Your JS file should be comprised of functions, no actions should happen in your code outside of a function except for your initial init() function
Your code MUST be YOUR code. Do not copy and paste code into your project. Type every bit of it out
Your HTML and JS should all have proper indentation
Helpful Form: An error message shows if a user tries to sort a student without filling out the form
You should apply responsive design to your page (aka your app should be designed to work on small screens)
Add Button Hints
When a new student is added an object should be created and that object should be pushed into an array of students that then prints to the DOM.

Expel Button Hints
Think of a way you can expel students without just hiding those divs on the page. This would mean when the button is clicked you modify the array of students and pass the new array into your print to dom function. Double hint - put a unique id in the student object when you create them.
