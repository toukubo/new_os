# Tester’s Manual
1. test case rules
doing the test in a systematic way and its integrated  to the  basecamp and for the files or  features we need to implement we use the concepts of tickets or test cases.

And test cases Google if the admin people are those testers don’t know and in a programming team it’s a very famous way for handling the tests and the to dos and test case makes  the instructions clearer one of the best clearest way for specifying what do we need to do.

it consists of three things  
1. [steps to repeat] 
2. [what expected to be displayed] 
3. [what currently is displayed]

 for example like if we imagine we are developing a system named Twitter.
if you want your developer to make this page, you should write the set test cases 
 like this

[ steps to repeat ]  we open a timeline page 
[what expected] there is a public timeline and  tweets of users you are following should be displayed and if you keep waiting, then the new tweets dinamically appeaers.
[now] no tweets!

[ steps to repeat] 
click the reply button on the one of the tweets 
[ what expected] the log-in button should be displayed if he is not logged-in,and if logged in, a text box pop up come up. 
[now] no tweets list so far. and no reply function enabled


2. status rules ( regading who should complete the development tickets )

developers say the features is implemented, this is done, and they sometimes checks the tickects by themselves. No. we do not allow this workflow. what we need to do is , change the assignment to the testers, then testers do the test and if it is really done, then tester can mark it done. and tell it to  the developers.

usually the bugs occurs not in the developers local environment and not experienced developers tell just it is done perfectly and do not code that could run anywhere. but the systems always must run in the OTHER environment and contexts than the developers local. try move the code to other environment. and check the codes on the different serves, different conditions. the main reason why we should have testers while developers must do tests by themselves is hidden in this. moving the environment.


3. evidences.
please keep trying to use the screen capture tools and error messages. JING, snagit, or those tools that allows you to upload the images immediately is encouraged. good testers maximize developers debugging speed with greater informations. it is good you can capture more and more information. 


so, testers and directors make the ticket to basecamp. then developers impl, then changes the assignments  to testers, then they mark it done, or if not completerd, assign it to the developer again with the test result and error messages + evidences.
