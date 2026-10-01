1. What did pwd print?
    
    Ans: It explicitly prints the current directory which the computer is on!

2. What did ls -a show that plain ls did not?
    
    Ans: It showed all the other hidden files that plain ls didn't show

3. Pick one line from ls -l. What do you think the first column means?
    
    Ans: It gives information about the who gave the permission to create the file/folder 

4. Why does that work from where you are standing? Which kind of path is coding-cafe/week02?
Absolute or Relative?

    Ans: It works because we are trying to list items in week02 directly within one cmd rather than opening desktop then coding-cafe etc. It's a relative path as we need no go home and start from the beginning

5. mv did two different jobs above. What were they?
   
    Ans: In the first command which included mv, it was used to move the README.md file into the week01 folder whereas in the second command mv was used to rename the file name!

6. How many folders are on your PATH? (They are separated by :)
    
    Ans: There are 15 folders on my PATH.

7. Write down exactly where your python3 lives. You will need this again in a minute.
    
    Ans: /opt/anaconda3/bin/python3

8. Compare your answer to 7 with the person next to you. Are they the same? If not, why might that be?
    
    Ans: They might not be the same because different users may have different installations of Python or may have installed it in different directories.

9. What exactly did the shell say? Explain the error in your own words, using the word PATH.
    
    Ans: It wasn't able to find the respective path for the directory!

10. .venv did not appear with plain ls. Why not? (Refer back to section 1.)
    
    Ans: As .venv was a hidden file ls wasn't able to display it. 

11. What changed about your prompt? 
    Ans: (.venv) appeared at the beginning of the prompt

12. Compare this with what you wrote down for question 7. Is it the same path? If not, what does that tell
you about what activate actually did to your PATH?

    Ans: /Users/naazparveen/Desktop/coding-cafe/.venv/bin/python3. No, it is not the same path. Earlier my python3 was /opt/anaconda3/bin/python3, but after activating .venv the shell finds the .venv virtual environment first than the anaconda python version!

13. What is in the second list that was not in the first?
 
    Ans: In the second list there were several other content in the two column tabular representation than the first list.

14. Where does python3 point now?
    
    Ans: It points back to the anaconda environment which my shell initially pointed out to.

15. Find what ls -h does. Write it in your own words.
    
    Ans: It lists all the contents inside the respective folder.

16. What is the difference between what Ctrl + C and Ctrl + D did?
Ans: Ctrl + C copied the history and Ctrl + D pasted the copied history!







