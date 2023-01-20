---
toc: true
layout: post
description: my grades on the 4 example preformance tasks
categories: [markdown, java]
title: Performance Task Part 2
---
# Submission 1
<html>
<style>
    table, th, td { 
        border:2px solid white;
    }
<!DOCTYPE html>
<html>
<head>
   <style>
      table, th, td {
         border: 1px solid green;
      }
   </style>
<body>
   <table>
         <th>Reporting Category</th>
         <th>Student Score</th>
         <th>College Board Score</th>
         <th>Comments</th>
      </tr>
      <tr>
         <td>Program Purpose and Function</td>
         <td>1</td>
         <td>0</td>
         <td>The stated goal of the program is to allow users to view animals and recognize them later, it mentions the underlying issue or artistic motivation behind it which was good. However, the description provided does not match the functionality shown in the video and conflates the input and output.</td>
      </tr>
      <tr>
         <td>Data Abstraction</td>
         <td>0</td>
         <td>0</td>
         <td>Two code snippets are presented, one that demonstrates how data is stored in the list "animalImages", and another that depicts the list "animalList". However, the "animalList" is not used in either of the code snippets. The explanation provided mentions the content of "animalList" but also includes details about the images from "animalImages" which are stated to be in that list.</td>
      </tr>
      <tr>
         <td>Managing Complexity</td>
         <td>1</td>
         <td>0</td>
         <td>The provided response includes two code segments that demonstrate the efficient storage of data in a list named "animalImages" and "animalList". This effectively utilizes the capability of a list to store multiple variables in a shorter and more organized manner, thus simplifying the overall complexity of the code. Furthermore, the response explains the practical application of using a list to manage complexity and how it streamlines the overall program structure.</td>
      <tr>
      </tr>
         <td>Procedural Abstraction</td>
         <td>0</td>
         <td>0</td>
         <td>The response features a student-created function named "evaluateGuess" that takes in one input, "guess" and demonstrates its usage in a separate code snippet. The function is described as determining the accuracy of the user's guess. However, it does not elaborate on how this function fits into the larger picture and contributes to the overall functionality of the program.</td>
      </tr>
      <tr>
         <td>Algorithm Implementation</td>
         <td>0</td>
         <td>0</td>
         <td>The "evaluateGuess" function created by the student, includes elements of sequencing, iteration (using a for loop) and selection (utilizing an if statement) within the algorithm. The explanation provided gives a brief overview of the algorithm, but it lacks sufficient detail to allow someone to replicate it.</td>
      </tr>
   </table>
</body>
</html>


# Submission 2
<html>
<style>
    table, th, td { 
        border:2px solid white;
    }
<!DOCTYPE html>
<html>
<head>
   <style>
      table, th, td {
         border: 1px solid green;
      }
   </style>
<body>
   <table>
         <th>Reporting Category</th>
         <th>Student Score</th>
         <th>College Board Score</th>
         <th>Comments</th>
      </tr>
      <tr>
         <td>Program Purpose and Function</td>
         <td>1</td>
         <td>1</td>
         <td>The program aims to tap into the user's creativity by allowing them to express themselves through poetry using their own words. It displays poems based on the user's input of words and settings, resulting in a variety of poems with different word arrangements and another set of poems with different words but no articles. The program also outlines the inputs and outputs.</td>
      </tr>
      <tr>
         <td>Data Abstraction</td>
         <td>1</td>
         <td>1</td>
         <td>Two pieces of code are given, one where data is being saved in a list called nounList, and the other where the data is being retrieved from that list under the name wordList when it is passed as an argument. The text explains that the data in the list is nouns that have to be in specific places in the poem for it to make sense.

</td>
      </tr>
      <tr>
         <td>Managing Complexity</td>
         <td>0</td>
         <td>1</td>
         <td>The code presented in the response attempts to make the process of generating poetry easier by using lists of words, but this approach is not optimal. Storing noun inputs in separate variables and calling them individually would have resulted in more readable code. Furthermore, using a different method, such as generating a random integer, to randomize selection would have been more efficient and resulted in less cluttered code, rather than having to write multiple statements for each possible integer generated.</td>
      <tr>
      </tr>
         <td>Procedural Abstraction</td>
         <td>1</td>
         <td>1</td>
         <td>The response features a createPoems procedure that was created by a student, and which has four parameters that are used within it. It describes how the procedure plays a role in the overall program, by being used along with the inputs from the user and constructing poems based on the number of poems specified by the user and whether the user requested for articles to be included in the poems.</td>
      </tr>
      <tr>
         <td>Algorithm Implementation</td>
         <td>0</td>
         <td>1</td>
         <td>The student-developed algorithm within the procedure, createPoems, attempts to incorporate sequencing, selection (if statement), and iteration (while loop) but it is not well structured. The response explains the poorly designed algorithm, it starts by defining a variable to count the number of poems generated and then defines an empty string, then it has an iteration that tries to generate as many poems as the user specified by running through the selection statements, which call articlePoem or noArticlePoem each time. However, it is not clear how these steps are organized and how the algorithm is supposed to work.</td>
      </tr>
        <tr>
         <td>Testing</td>
         <td>1</td>
         <td>1</td>
         <td>The response explains two invocations of the procedure createPoems, which lead to different code being executed by changing the argument for the last parameter. The first one is createPoems(nounList, verbList, adverbList, 1) and the second one is createPoems(nounList, verbList, adverbList, 0). The last parameter represents the article preference setting. The response describes the conditions that the code tests, which are whether the user input is 1 or 0 for the article preference setting.</td>
      </tr>
   </table>
</body>
</html>

# Submission 3
<html>
<style>
    table, th, td { 
        border:2px solid white;
    }
<!DOCTYPE html>
<html>
<head>
   <style>
      table, th, td {
         border: 1px solid green;
      }
   </style>
<body>
   <table>
         <th>Reporting Category</th>
         <th>Student Score</th>
         <th>College Board Score</th>
         <th>Comments</th>
      </tr>
      <tr>
         <td>Program Purpose and Function</td>
         <td>0</td>
         <td>0</td>
         <td>The video showcases a program that purports to let the user pick two Marvel characters from a drop-down menu, and then displays their rankings and the winner of the battle using an image, but it is not well thought through. The response describes the supposed function of the program, the functionality demonstrated in the video, and the supposed input and output. The response describes the input as various button clicks to switch screens and the character names selected from each drop-down box, but it does not explain how these inputs lead to the output or the logic behind it.</td>
      </tr>
      <tr>
         <td>Data Abstraction</td>
         <td>1</td>
         <td>1</td>
         <td>The response presents two pieces of code, one where information is being saved in a list called firstCharacterList and the other where that data is being accessed from the list using a loop. The data saved in the list is identified as the power rankings and the URL for the image of a character that was selected from a drop-down box.</td>
      </tr>
      <tr>
         <td>Managing Complexity</td>
         <td>1</td>
         <td>1</td>
         <td>The response features a list that brings together six scores and a URL for an image of a character into one organized unit, this is done to simplify the program code. It explains that this list helps to streamline the code, and that without it, the program would require more parameters and more steps to determine the winner, making it more complicated.</td>
      <tr>
      </tr>
         <td>Procedural Abstraction</td>
         <td>1</td>
         <td>1</td>
         <td>The response explains a findWinner procedure that compares the mean power rankings of two Marvel characters which are passed as inputs. The procedure alters the winner screen to show the character with the higher average and if the averages are the same, it shows a "tie" image. This procedure plays a crucial role in the overall program by determining the hypothetical victor in a fight between characters.</td>
      </tr>
      <tr>
         <td>Algorithm Implementation</td>
         <td>0</td>
         <td>1</td>
         <td>The student-developed algorithm in the findWinner procedure attempts to use sequencing, selection, and iteration to compare the average power rankings of two characters selected from a drop-down menu, but it is not well-structured. The algorithm iterates through the list of each character, sums up the rankings, and divides by 6 to get the average, but it is not clear how these steps are organized. It then compares the averages using a conditional statement to determine the winner and display their name and image on the winner screen, but this approach is not efficient.</td>
      </tr>
        <tr>
         <td>Testing</td>
         <td>1</td>
         <td>1</td>
         <td>The response explains two invocations of the procedure findWinner, with distinct arguments (Vision and Bishop; Carnage and Venom) that yield dissimilar outcomes. The response depicts how the procedure employs an if-else statement to establish the winner based on the mean ranking and presents the winner's image and name or a tie image accordingly.</td>
      </tr>
   </table>
</body>
</html>

# Submission 4
<html>
<style>
    table, th, td { 
        border:2px solid white;
    }
<!DOCTYPE html>
<html>
<head>
   <style>
      table, th, td {
         border: 1px solid green;
      }
   </style>
<body>
   <table>
         <th>Reporting Category</th>
         <th>Student Score</th>
         <th>College Board Score</th>
         <th>Comments</th>
      </tr>
      <tr>
         <td>Program Purpose and Function</td>
         <td>1</td>
         <td>1</td>
         <td>The video showcases a program that aims to assess critical thinking abilities by gathering input through a text entry field for guessing an 8-letter word and displaying the matching letters. In the demonstration, the user inputs words in an attempt to correctly guess "touching" in 4 attempts, but failing to guess "sandwich" in 6 attempts. The input is a word the user inputs, and the output is the color scheme of the corresponding letters.</td>
      </tr>
      <tr>
         <td>Data Abstraction</td>
         <td>1</td>
         <td>0</td>
         <td></td>
      </tr>
      <tr>
         <td>Managing Complexity</td>
         <td>1</td>
         <td>0</td>
         <td>The response presents two pieces of code, the first one where data is being saved in a list called 'guesses', in the second segment, the data is not being used directly but the length of the list is accessed. The response explains that the data saved in the list represents all the user's word inputs and that it is used to keep track of all the user's attempts and evaluate their performance.</td>
      <tr>
      </tr>
         <td>Procedural Abstraction</td>
         <td>1</td>
         <td>1</td>
         <td>The response includes a student-developed procedure, isitcorrect, which compares a user input guess to the correct word or letter positions. The procedure is called in the program with the argument answer. The procedure checks the user's answer every time they input a guess and contributes to the overall program.</td>
      </tr>
      <tr>
         <td>Algorithm Implementation</td>
         <td>1</td>
         <td>1</td>
         <td>The response features a isitcorrect procedure which was created by a student, that compares a user's input guess to the correct word or letter positions, this procedure is invoked in the program using the argument answer. The procedure examines the user's answer every time they input a guess, and it plays an important role in the overall program by providing feedback to the user on their performance.</td>
      </tr>
        <tr>
         <td>Testing</td>
         <td>0</td>
         <td>0</td>
         <td>The response explains the situations being evaluated in the procedure, particularly "if the user inputs the correct letter in the correct location" and "if the user inputs the correct letter in the incorrect location." It also details the outcome of these conditions, with the letter's color switching to green or yellow accordingly. The response does not mention the specific parameters used in the procedure's invocation.<td>
      </tr>
         <tr>
         <td>Summary: The passages describe the results of two submissions for a performance task in computer programming. The task includes multiple categories such as Program Purpose and Function, Data Abstraction, Managing Complexity, Procedural Abstraction, and Algorithm Implementation. The first submission received low scores in all categories, with comments indicating that the program did not match the description provided and that some elements were not explained well enough. The second submission received higher scores, with comments praising the program's aim to tap into the user's creativity and its ability to generate a variety of poems based on input.<td>
      </tr>
   </table>
</body>
</html>