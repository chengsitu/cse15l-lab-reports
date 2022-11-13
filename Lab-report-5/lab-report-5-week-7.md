# Lab Report 4 <br>
## Part 1
* In our lab group, we attemped the __chanllenge__ task: <br>
 `In TestDocSearch.java, copy the test called testSearchCount, rename the new test to testSearchCount2 and change the query string being tested to tax rather than taxation.` <br>
 * The steps we took: (38 keystrokes) <br>
 1. `/@ <Enter> nn` <br> find the where is __@__ located at <br>
 ![image](Search_For.png) <br>
 2. `6yy` <br> to copies the 6 lines that is under where do we find the third __@__ <br>
 ![image](6_line_copy.png) <br>
 3. `kp` <br> paste the what you copied <br>
 ![image](Pased_stuff.png) <br>
 4. `/C <Enter> n` <br> to find where is the Second __C__ located at <br>
 ![image](Search_For_C.png) <br>
 5. `ea2 <Esc>` <br> add the __2__ after we loacted where is the __parentheses__ that next to the __C__ we that located already <br>
 ![image](e_a_2_command.png) <br>
 6. `/ati <Enter> n` <br> search for the where is the second __ati__ locate <br>
 ![image](Search_for_ati.png) <br>
 7. `5x` <br> to delete the __5__ character after we located the __ati__ <br>
 ![image](5_x_command.png) <br>
 8. `/3 <enter> n` <br> search for where is the second __3__ locate<br>
 ![image](Search_for_3.png) <br>
 9. `i <rightrow> <delete> 161` <br> replace the __3__ to the __161__ <br>
 ![image](i_rightarrow_delete_161.png) <br>
 10. `:w <Enter>` <br> to save the any __change__ that you makes
 ![image](w_enter.png) 
 ---
## Part 2 <br>
__Method 1: Edit in the Local__ <br>
* This method took me about 3 minutes. The first method takes more time than do the second method. It think it because that in the first method you have to use the `scp command` to replace the old file to the new file that you finish edit already. When I using the `scp command` I have to type a lot to make the command work. Also that the speed that I edit the local file is slower because I rely on using the mouse, instead of using the shortcut of keyboard in VIM command. <br>

__Method 2: Remote editing using VIM__ <br>
* This method took me about 1 minute 30 second. I can edit the file remotely and no need to use the `scp command` to upload the file. After I finished editing in the VIM system, then I can just use the `bash test.sh` to run my code immediately. <br>

__Which of these two styles would you prefer using if you had to work on a program that you were running remotely, and why?__ <br>
* If I could edit the file on the remote sever, I will choose to use the VIM system to edit the file. It is because that it reduces the time of copying files remotely from the local computer to the remote server and moving the files to the appropriate directory.  <br>

__What about the project or task might factor into your decision one way or another? (If nothing would affect your decision, say so and why!)__
* If there is only 1 ot 3 files that I need to edit, I will use the second method. Other than that, I will use first method because __IDE__, such as VSCode because it is easy to access and make change. However, I still need to use the `scp command` to copy the file into the remote server. 

