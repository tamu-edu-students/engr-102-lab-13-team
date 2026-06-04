# ENGR 102 Lab Topic 13 (team)
There are several deliverables for this combination team and individual assignment. Please submit all of the following files **to your section's Canvas** page. Please include the team header information at the top of each file with the names of all contributing team members. This is a team assignment, but **everyone** must submit the files for credit. You may discuss the problems with other teams, but your submitted work must be unique. Check out the [Frequently Asked Questions](#frequently-asked-questions) below.

## Activities

1. [Planning your program](#planning-your-program)
2. [Writing your code](#writing-your-code)
3. [Reflecting on the design process](#reflecting-on-the-design-process)

## Planning your program
Engineers today are expected to maintain a combination of technical problem-solving capabilities, content literacy, and societal skills of communication, creativity, and collaboration[^1]. This lab is meant to improve your creativity skills while also working on your technical problem-solving capabilities within the framework of a programming project. Your team is first tasked with deciding on a project idea – as a team you will create a program for users (humans) to play one of the following games:
- [Flip 7](https://boardgamegeek.com/boardgame/420087/flip-7)
- [TEN](https://boardgamegeek.com/boardgame/335609/ten)

Regardless of which game you choose, your program must meet a set of minimum requirements, defined below. At a **minimum**, your program is required to do the following:
- Display the rules of the game and instructions for the user
- Display a set of options for the various things your players can do (display instructions, display score, quit early, etc)
- Utilize basic coding elements taught in this class including if-elif-else statements, loops, dictionaries, functions (with docstrings), try-except statements, and comments
- Use file input/output for something
- Create a nice-looking user interface (consider using turtle graphics, tkinter, or pygame)
- Create a complete, fully functional, high quality gaming experience
- Incorporate at least one thing beyond what is covered in the course (learn something new)
- Be creative and have fun!

*You are encouraged to add extra features to your program, but please submit a **working** file for grading.*

After your team decides on a game, start thinking about how your program will work. Using the bottom-up approach, create a hierarchy for the design of your program. You can draw it by hand or use software of your choice. Think carefully so that all of the leaves of your hierarchy can each be implemented in no more than about 10 lines of code. When you begin to code, you will likely change your mind about how you want to implement the various aspects of your game. You may not know exactly how to do something right now, but you will learn along the way. After you begin planning your program, think about what kind of test cases you will need to ensure your final design works. Create a document named `game_plan.pdf` that contains a short description of why your team chose the game you chose (about 100 words), your team’s hierarchy, a short explanation of your hierarchy and general flow of the game (about 200 words), and a minimum of ten test cases. The test cases can be simple input/output checks, they can check intermediate processes or individual functions (unit testing), or they can check overall game flow. It’s probably best to include at least one of each type to fully test your game.


## Writing your code
**After** your team develops a plan for your game, divide up the workload among all members so that each person can write one portion of the program on their own. If you planned your program well in the planning stage, each portion can be written and tested individually. Remember, you should have written test cases before you start to write code and use the pyramid style of code development. *You may use AI tools to complete the coding portion of this assignment.* Your hierarchy, descriptions, and test cases (planning document) as well as your reflection below must be written by you, in your own words.

After each team member has written their part, combine the code into one file named `fun_game.py`. As a team, work together to complete the final bits of code and testing needed to debug your program. When you are done, have each team member independently verify that the program works as desired.

**After your team has finalized your code**, create a short user manual to include in `game_plan.pdf`. This manual MUST describe how to run your program and include examples of valid inputs and expected outputs. Feel free to include screenshots or flowcharts. *We will use this document to run your program and grade your lab, so please be thorough!*


## Reflecting on the design process
Create a document named `reflection_yourname.pdf` and answer the following questions (50 – 100 words per question). Please fill in your first initial and last name for the text `yourname`. For example, `reflection_nritchey.pdf`. **Please write in complete sentences.**

1.	Did you like your program topic? Why (not)?
2.	Did your team stick with your initial bottom-up approach to program development, or did you switch to a different design approach at some point? Which approach did you prefer and why?
3.	Did your final design closely match the original hierarchy your team developed? In what ways is it the same? In what ways is it different?
4.	Briefly describe how you used AI tools to complete your program. In what ways did AI tools help or hinder your progress?
5.	Briefly describe the thing(s) you learned on your own, beyond what was covered in the lectures. How did you incorporate them into your program?
6.	If you had more time to work on your program, what additional features would you want to add? Is there anything about your submitted program you would change?
7.	What was the most difficult part of this assignment? Please explain.
8.	Estimate the portion of the assignment completed by each member of your team (yourself included). Please explain any significant workload imbalances and give a brief summary of who did what. For this question it’s ok to make a bulleted list instead of writing complete sentences. Example:
    - Amari: 25% - completed hierarchy and pdf document, programmed instructions function, helped with debugging
    - Bailey: 35% - really enjoyed working on the project and took over, created list of functions and variables used, created test cases, coded almost half of it, put code together and debugged it
    - Cameron: 15% - sick and busy studying for other classes, programmed one function
    - Dylan: 25% - programmed input validation and menu options, helped with debugging, wrote user manual


## Frequently Asked Questions
1. **What do I submit where?** Please submit a pdf of your description of why you choose that game, hierarchy, your explanation of your hierarchy and general flow of the game, and your test cases to LAB: Topic 13 (team) part 1 on Canvas. Don't forget to include a user manual! Also submit all files needed to make your program work. We need to run your program on our own computers, so any additional files (~.txt, ~.csv, images, audio, etc) need to be included. The easier it is for us to run it, the easier it is for us to grade it. So that means submit `game_plan.pdf`, `fun_game.py`, and any `~.txt`, `~.csv`, etc files needed to make your program work to LAB: Topic 13 (team) part 1 on Canvas.

2. **What else do I submit where?** Please submit your individual portion of the lab to LAB: 13 Topic 13 (team) part 2. That's activity 3, where you answer 8 questions in the file `reflection_yourname.pdf`.

3. **In the documents we create, do we have to write in complete sentences?** Yes! Please provide explanations as needed, but don't write a novel. Practice being concise while also conveying all the information needed. We really don't want to read more than we have to.

4. **For the reflection, are you really going to read everyone's submission?** Yes!

5. **You want me to program an entire game?!** Well, yes, but you can use AI tools to help you out. The point of this assignment is to use your design skills and practice coding with everything we've learned in class. Plus you will end up with something fun to play over the break. Your game doesn't have to be perfect, but it should demonstrate everything you've learned this semester. Be creative! Have fun!

6. **Wait, we get to use AI tools?!** Yes... but only for the coding portion of the assignment. Your design plan and reflection must be written by you, in your own words.

7. **Can I program a different game or do I have to choose one of those listed in the pdf?** If you want to program a different game, talk to your instructor during class.

8. **Do I have to use the bottom-up design method?** Yes, but just to start. It's okay to get halfway through then switch to the top-down approach (or something else entirely).

9. **What kind of stuff is considered "beyond what is covered in the course" (learn something new)?** This is open ended and we're lenient on this requirement. As long as it wasn't used previously in the course (lectures or assignments), it counts. Examples may include a new module, tkinter or pygame, using an audio file, displaying an image, interacting with a webpage... and many more.

10. **Any advice (or help)?** [Check out this free online textbook](http://inventwithpython.com/invent4thed/). If you're stuck, go to office hours and ask for help in class!

Have a question you don't see here? Email your instructor!

Revised Summer 2026 SNR

[^1]: X. Du, M. Thrane, M. Lehmann, P. Christensen. Problem-oriented and project-based learning (popbl) as innovative learning strategy for sustainable development in engineering education. European Journal of Engineering Education, 33(3):283–295, 2008.
