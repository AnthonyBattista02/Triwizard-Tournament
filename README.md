# Project-1-Proposal

## Description
My goal is to use an API in order to create ranking system. This will grab information such as a name and picture from the Harry Potter API and display them to the user. The user will then be prompted to choose between the two characters that the API provides them with, and the winner will move up in the bracket displayed below. This will repeat and continue until the bracket is filled and will have the player choose which Harry Potter character is their favorite one by one.
Potential challenges for this project will be grabbing the random character from the API as this will help to finally make sure I completely understand how to use APIs. Another challenge will be designing the page. The bracket above seems like it could be challenging to incorporate into the website both because of its shape and size. I might have to create a miniature display of it that you can click on to enlarge it in order to make the site look professional. 

## Wireframing
![TheTriwizardTournament drawio](https://github.com/AnthonyBattista02/Triwizard-Tournament/assets/47795224/ec4a0e5f-c392-4bac-95ac-4df607c7046a)



## Pseudocode Steps
1. Create a call to the API using the key: 845891660486879 and the base url: https://superheroapi.com/api/access-token/
2. Create a Function that will take a random superhero from the API in a loop for the amount of Characters in the bracket
3. Under that random character get the image url, name, house, and patronus and assign them to an object
4. Set the name of the character into the current space of the bracket, and then set the current space of the bracket to the next
5. Once the loop is complete set the innerHTML of the versus section of the page to the first two characters and information found in the objects created
6. Create an event listener for clicking on an image
7. The image on click will take the name from the object of the image selected and display it in the innerHTML of the bracket for the current round winner and set the current space of the bracket to the next
8. If the last round is completed then display the winning name and picture large in the middle of the versus screen and set the current versus screen visibility to hidden 
9. Make a reset function and call it when reset button is clicked
