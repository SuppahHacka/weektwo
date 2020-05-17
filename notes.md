# Task 1 - Wget

Downloading the website materials from activehistory

  - 1st command didn't seem to add anything to my folder created under C:\Users\Tony\wget-activehistory
        - Try to invoke command using wget.exe - did not work, got error message (see Error1 - Wget.png)
        - Tried to relocate wget to C:\Windows as instructed in discord - still nothing. 
        - FINALLY! Using the regular cmd prompt, i simply made a dir called week-2-thing as per Dr. Graham's reccomendation and invoked wget to download the webpage and it worked! I suppose anaconda powershell is not configured correctly. I will have to find out why. 
  - 2nd command to recursively download also worked like a charm! 
  
  - Using Pythong to generate a list of URL's
        - Something I noticed in this exercise is that I need to have wget.exe in the folder I want to invoke the command in. I looked through discord to see if there was any mention of a workaround but got quite overwhelmed with other inquires from other students. 
    - Instead, I just copied wget.exe into war-diaries subfolder and invoked 
        > wget -i urls.txt -r --no-parent -nd -w 2 --limit-rate=100k
    
    -Additionally, I also noticed that i can only run python commands within anaconda powershell and not the command prompt. I assume this is because anacaonda has the proper environment to execute a python command. 
 

# Task 2 - API's

  Getting material out of an API 
  
  The concept of API's was already very familiar to me. 

 - As an aside, I wrote a program with a friend back in highschool using Java which parses a JSON API in order to rename files! 
        - More detail on this can be found in my reflection 


# Task 3 - OCR 
 
 - Installing R was hard to do but thanks to discord, I was able to go back and find where I can download the file to install it. 
 - R is VERY unintuitive. took me forever to find the image I saved, so instead, I just saved the image to work with in the default folder RStudio wanted to search in. 
 - The looping of the files never worked. It seemed straightforward but the output never got generated. 
        - I figured it was time I threw in the towel and summed up my learnings.
        - It's very hard to make sure the code actually succesfully compiles. There's no indication other than this little > which frustrated me when it never showed up. 


# Summary 

This week's exercises did not pose as much of a complicated mind boggling challenge as much as it did software compatibility. The frsutrations many students experienced and communicated in Discord were felt among the peers and it goes to show that digitization isn't as easy as we may think. 

Of course, troubleshooting is the nature in the tech world and this week taught me more about that than anything else! 
