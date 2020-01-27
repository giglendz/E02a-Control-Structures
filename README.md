
# E02a-Control-Structures

*If you wish your exercise to be graded, please edit the LICENSE file (add the current year and your name).*

Edit README.md to answer the following questions:

- Open main01.py. Before running it, what do you expect this program to do?
-   I expect it to say 'greetings' and then ask me what my favorite color is.

  - Now right click on the main1.py window and select “Run Python File in Terminal”. Click in the bottom panel, and answer the question. Describe what happened.
  -   The program didn't know what to do with my answer, so it stopped.

  - What do you think the program did with what you typed in answer to the question?
  -  I think it didn't have the correct data to have a response to my question.

- Open main02.py. Before running it, describe how this is different than main01.py.
-   This has another line of code with a response to the question asked in the line above.

  - What do you think the color = input() will do?
  It will generate another line underneath in the terminal that says color.

  - Run the program in the terminal and answer the question. Did the program do what you expected?
  Yes, it just generated a line that said color.

- Open main03.py. Before running it, describe how this is different than main02.py.
- This actually has a correct answer, and if you don't say 'red' then you are told 'sorry, try again'

  - What is happening on lines 9–12?
  -   These lines allow for an actual answer to the question, and if guessed wrong it informs you of your incorrect answer.

  - Why are lines 10 and 12 indented?
  -   They're in a loop

  - Run the program and answer the question. What happens if you don’t capitalize Red?
  -   It says your answer is incorrect

  - What does this tell you about "color"?
  -   color is case sensitive

- Open main04.py. Before running it, describe how this is different than main03.py.
-     It added red undercase to Red so that both answers are correct.

  - What problem is this trying to solve?
  -   The problem that if you don't type Red with the uppercase it is said to be incorrect

  - Run the program and answer the question. What happens if you use some other capitalization scheme (i.e., “RED” or “reD“)?
  - it says it is incorrect.

- Open main05.py. What do you expect line 9 to do?
- I expect that this line will make it so that the answer is not case sensitive

  - What problem is it trying to solve?
  - The problem that if you input the answer with the incorrect capitalization, it is said to be wrong.

  - Run the program and answer the question. What happens if you add spaces before or after the word (i.e., “ RED “ or “ red”)?
  - it is said to be incorrect

 - Open main06.py. How is line 9 different than in main05.py?
 - it makes it so that you can have spaces before or after 'red'

   - What would you guess .strip() is doing?
   - it is saying that as long as red is input into the answer, even if there are spaces it is still correct.

   - Run the program and answer the question. Is there another way of writing “red” that will break this logic?
   - Yes, if you type spaces between the letters it is said to be incorrect.

 - Open main07.py. Before running this program, how do you expect this to be different than main06.py?
 - This time, if you type in the color 'pink' the program will tell you that you are close to the answer.

   - What is happening on line 12?
   - elif means 'else if' so if you type in pink it will give you the answer 'close' otherwise you will be told you are incorrect

   - Run the program and answer the question.
   If you answer pink then you can't guess again.

 - Open main08.py. What is the purpose of line 9?
 - It allows you to guess again if you got the answer wrong

   - Why are lines 10–17 indented?
   - They are in a loop

   - Run the program. What would happen if line 10 were moved before line 9 (and no longer indented)?
   - Then there is no correct answer

   - Make that change and run the program again. (To end any Python program, you can type ctrl-c)
   I was correct, there is no correct answer if you switch them

 - Open main09.py. What is happening on line 13?
 - This will count how many times it took you to guess the correct color

   - What is the purpose of “count”?
   - It counts how many guesses you have made

   - What is happening on line 22?
   - It tells you how many guesses you've made, the {} being a place holder for whateverrr number it took.

   - Run the program.
   - I first typed in blue, and the purple, adding two to the count, then I guessed pink, after which it said 'close' and then I typed red and got the correct answer, and the program told me that it took 4 tries to guess.

 - *Extra credit:* open main10.py. Add a comment to each line describing what it is doing (a comment follows a pound sign [#]).

 - *Extra credit:* open main11.py. What is happening on lines 6-11?
  These lines make it so that the color is randomly chosen, and different every time

Commit your changes and push them back to the repository.
 

---

Instructions for forking this repository:
 
Log into your account on [github.com](https://github.com)

Go to the [exercise template page](https://github.com/BL-MSCH-C220-S20/E02a-Control-Structures) on GitHub

There is a button in the top right corner of the page labeled "Fork". Press that now

This will create an independent copy of this repository in your account that you can control and edit

Go to your GitHub home page, and select the new E02a-Control-Structures repository

On that page, you will see a green button labeled "Clone or download". Press that now. You will see a drop down box. Press the "Open in Desktop" button.

This should launch GitHub Desktop. It will ask you for a location (on your computer) where the repository may be cloned (downloaded). Choose a location that will be easy for you to find, and press the blue "Clone" button.

Once GitHub Desktop has cloned (downloaded) the code, it will be responsible for keeping the code on your local computer synchronized with the repository in your GitHub account. Now, open Visual Studio Code, and choose File->Open. Find the folder of the cloned repository and select Open.

In the left (File Explorer) panel, you should see a list of files that comprise this repository

First, edit the file called LICENSE. Replace year and name with the current year and your name. Save this file

Then open README.md. Feel free to remove any extraneous information, and then answer the questions posed in the file. You can add your answers after each question

When the time comes for you to run any of the python files, you can do so by clicking the green arrow in the top right corner of the window or by right-clicking on the code and selecting "Run Python File in Terminal". The results will appear at the bottom. If you don't see "Run Python File in Terminal" in the contextual menu, that is because VS Code doesn't have the Python extension installed. You can do that here: [https://marketplace.visualstudio.com/items?itemName=ms-python.python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

When you are done editing the files, return to GitHub Desktop. In the left panel, you should see a list of the files that have changed

At the bottom of the leftmost area, you should see a text box labeled "Summary (required)". Add a message that describes what you have done; these messages are typically stated in the active-present tense. For example, "Updates the LICENSE, README.md, and completes the assignment." Push the blue "Commit to master" button

In the top bar of the window, you should see a button that is labeled "Push origin", push that now

Check out your page on GitHub. You should see the changes you made reflected there, Repeat steps 10 through 16 as necessary

When you are satisfied with your efforts, turn in a URL to your repository on Canvas

---
If you try to push your changes, and you receive a permission error, it is likely that you are trying to edit the BL-MSCH-C220-S20 copy of the repository rather than your own. Make sure you don't skip the step of forking your own copy and cloning that.

---

The grading criteria will be as follows:
 
[1 point] Repository contains a description of the project in README.md

1 point will be awarded for answering the questions associated with each of the files

10 points total (+2 points extra credit)
