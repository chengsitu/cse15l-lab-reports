## Part 1: **Search Engine**
---
* This is my code for the SearchEngine
<br/>
![image](SearchEngine.PNG)
* For this code, if you want to run this code, you need to type --> javac Server.java (Your Search Engine's file name).java in the Ternimal. <br/>
 Then --> java (Your Search Engine's file name) (some number greater than 4000)
* It will go out a link, Shift + click get into it. Like this:
![image](Somethinglikethis.PNG)
* Then when you type /add?s=anewstringtoadd at the back your website like this:
![image](addwords.PNG)
* In the code, it will sorted that word that you put into a arraylist in order to do it in the search late. 
![image](addmethod.jpg)
* The red circle that I draw that is the add method is working at that place. I just try to sort the word into a arraylist
* Same way, I add two similar words into the arraylist again by same way that I add word before like this:
![image](addwords2.PNG)
![image](addotherwords.PNG)
* After I done that, my arraylist will sort **3** different words (**anewstringtoadd**, **apple**, **pineapple**)
* Next, we can use the search method to find some words that contain the character that you are looking for. There is search method in my code: 
![image](searchmethod.JPG)
* From my code, I write get key word that you want me to look for, then I use for loop to get every words that you adds into the list and try to find out every word that contain key word that you put. Then put those qualified word into a new arraylist and return them. <br/>
**For Example:**
![image](Searchwords.PNG)
* From here, you can see that I want to find any words that include **"app"** and before I add three words into the word bank: (**anewstringtoadd**, **apple**, **pineapple**). 
* The words that qualifed the requirment is only **apple** and **pineapple**. My code also shows that.
<br/>
---
## Part 2: **Bugs fix**
---
* For the first bug that I found is in the array Example file, after I run the my own test to the reversed class: it shows:
![image](test.PNG)
* From this, I can see that the except input for the first num is 5, but code give me the Zero, so I go back to check where do it get wrong.
* After 3 mins, I see the bugs: (red circles is the bug that need to fix)
![image](wrongcode.PNG)
* newArray is empty, we don't put anything in it. Which **arr** can not copy any of the char from newArray. Then what we need to fix is:
![image](correctcode.PNG)
* Make **arr[i]** to **newArray[i]** and return **newArray** instead of return **arr**.
* After I correct my code, the test is passed.
![image](good.PNG)

**Second bug**
* Second bug that I found is in the listExample.java file.
* It did not return a same order of input, it return the inverse of the input. Which it is caused from here:
![image](problem.PNG)
* It always add the String to the **first** index and then every string that put already will move to next one automatically. 
* If we want to fix it, we just need to delete the (**0,**), then it will automatically append a specific element to the **end** of a list.
![image](好的.PNG)