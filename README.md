# cs114-assignment-1-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs114-read-these-instructions-repeatedly-until-you-understand-then-begin-your-project-if-something-is-not-clear-ask-a-a%c6%92before-you-begina%c6%92a-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;128306&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS114 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
1. Log in to GitHub.

2. Fork this repo(sitory). See this video on how to carry out this step and step 3.

3. Clone your fork, using either the web site or the GitHub Desktop client.

4. Checkout your personalized branch, the one with your name and GitHub handle.

â–ãƒ»Introductionãƒ»â–

For this assignment, youâ€™ll be writing a single program that creates a string based on temperature and random factors.

1. Your program should print your first and last initials in large block letters. Use each letterâ€™s corresponding characters to form the letters. (See the Example Output section below.)

2. Next, ask the user to enter a number in Fahrenheit. Your program should convert the value to Celsius and save it. For example, entering 32 should yield 0.

3. Now take input from the user in the form of a 5-character string, then save the string in reverse without the first and last characters. In other words, trim the outside characters. For example, if the user enters abewz, your program would save web.

4. In this penultimate step, generate and save a random number between 32â€Šâ€“â€Š16,384, inclusive.

5. And, finally, combine the results of steps 2â€Šâ€“â€Š4 and print it to the screen. See the Example Output section below.

â–ãƒ»File Listãƒ»â–

This repo contains the following files, all required to carry out this assignment. Before you start working, ensure you understand the role of each file below.

1. Makefileâ€Šâ€”â€ŠRun make in your command line interface, or CLI, from this repoâ€™s root folder to build your assignment. As you test input, run make run to only run a previously-compiled Java program, not compile it.

2. .editorconfigâ€Šâ€”â€ŠEverything in this file is a redundancy of whatâ€™s already in the .editorconfig file you installed in your home folder during the first week of class. Itâ€™s here to make sure youâ€™re working with the formatting rules defined in

.editorconfig, as this is part of your grade. Do not move this file. Also, ensure EditorConfig is working in VS Code, before beginning this assignment.

3. .gitignoreâ€Šâ€”â€ŠDo not modify this file.

4. Assignment1.javaâ€Šâ€”â€ŠWhere you will do your assignment. Do not write your code in anything other than this file.

â–ãƒ»Example Outputãƒ»â–

If I was creating this program, itâ€™s output would look like this:

“`bash RRRRRRRR VVV VVV RRR RRR VVV VVV RRR RRR VVV VVV RR RRR VVV VVV RRR RRR VVV VVV RRR RRR VVVVV RRR RRR VVV

Please enter a number in Fahrenheit: 32 Please enter a 5-character string: abewz Random number generated. Continuing… Your new string is

0.0web15769 “`

â–ãƒ»Gradingãƒ»â–

| Item | Points | |————————————————|:——:| | Program works according to instructions | 34 | | Code compliant with

EditorConfig rules | 33 | | Code is neat and variable names are logical | 33 |

â–ãƒ»Dueãƒ»â–

â–ãƒ»Submissionãƒ»â–

You will need to issue a pull request back into the original repo, the one from which your fork was created for this project. See the Issuing Pull Requests section of this site for help on how to submit your assignment.
