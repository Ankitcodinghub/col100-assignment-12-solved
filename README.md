# col100-assignment-12-solved
**TO GET THIS SOLUTION VISIT:** [COL100 Assignment 12 Solved](https://www.ankitcodinghub.com/product/col100-assignment-12-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101489&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COL100 Assignment 12 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
1 Organisation Hierarchy

Note: Please read the description carefully for attempting the questions as there are some changes with respect to Assignment 11. This assignment is an extension from Assignment 11 and most keywords remain the same.

I am the CEO of a “Fortune 500” company and we have to create a software to manage all the employees. Unfortunately, I don’t know how to code therefore I request you to help me with it. My organisation has many levels; with me at the top i.e. level 0. You did a great job last time and now I want to add some new functionality. Each employee (including me) may be in charge of at most two people. An employee of my organisation has an Employee ID (unique in the organisation and is a non-negative integer), Employee Name (It consists of one word the Surname or Last name), Employee Salary (This is a non-negative integer) and two pointers which points to the subordinates. For the sake of convention lets call them subordinate one and the subordinate two of the employee. Let us understand the terms of my company in detail.

We have a weird tradition of calling people by their last name however this causes some confu- sion. You will be helping us with this. Note that the name of two employees may be the same but their id will be unique.

<ol>
<li>Employee: This is a structure in C that contains Employee ID, Employee Name, Employee Salary and two pointers which points to the subordinates.</li>
<li>CEO: The CEO is the top most employee of the company that has no manager above them. There is only one CEO in my company.</li>
<li>Edge: Edge acts as a link between the manager and the subordinates.</li>
<li>Intern: An employee that has no subordinates is known as the Intern. It is the last employee of
the company. There can be multiple interns in a company.
</li>
<li>Level: Level of the employee is the distance from the CEO to that particular employee i.e. count of how many positions is an employee below the CEO in hierarchy of the company. The CEO is at level 0.</li>
<li>Subordinate: This is an employee that works directly under another employee.</li>
<li>Team: It is a sub-organisation inside the company. The team with the CEO as head is the company itself. Then we have two teams – one led by subordinate one and the other led by subordinate two. Each team can have at max two sub teams lead by the subordinates of the team head.</li>
<li>Company: The collection of all the employees working under the CEO. It is also called organisa- tion. Both words are used interchangeably.</li>
</ol>
In this assignment you are given this structure of an organisation and you have to implement certain functions.

You are given a global pointer CEO that always points to the head of the Company and some helper function to create an employee and to print the employees. You are not allowed to change these helper

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
functions that are already there since any changes might interfere with the Auto-grader. Also, make sure that CEO points to the head of the company always. Not following this invariant might result in malfunctioning of the Auto-grader.

Some description of the helper functions provided to you:

<ol>
<li>create_employee(int id, char* name, int salary): This function would create a new Employee with the emp_id attribute as id, the emp_name attribute as name and the emp_salary as the salary. The subordinate one and subordinate two pointers are set as NULL. This function returns a pointer to the employee. Note that the creation of the structure is done by us and we will provide only non negative unique IDs.</li>
<li>create_company(): This function would create a new Company from the input given in the input.txt and return a pointer to the CEO.</li>
<li>print_company(struct Employee* head): This function would print the organisation at any moment for you starting from the head. You can pass another pointer to print the team with the given employee as the head.</li>
</ol>
You have to implement the functions mentioned below and are also provided with the main function. Again, as above, do not change the main function. You can change the inputs given to the program to check your code, you may also add print statements in your functions but make sure before submitting, you comment/remove all such print statements.

Hint: Please see the implementations of the Helper functions carefully to get a fair idea about how to implement the functions.

Please download the skeleton code from Moodle. Please read the comments of the Skeleton code for some clarity on the functions. You only need to fill the functions in the skeleton code and change nothing else. You can’t change the parameters and the return types of the functions in the skeleton code. You just have to return the values in the functions and rest will be handled by the main given to you.

1 23

4 5 8 NULL

6 7 NULL 9

Consider the above company, the input file will contain the list of employee IDs, employee names and employee salaries together. Name and salary has not been included in the figure here to ensure readability, but after each id there is a string which corresponds to the name and a integer which corresponds to the salary. Therefore in the explanation below we have omitted name and salary.

The input format will be like employeeId employeeName employeeSalary. The only change between assignment 11 and this one is that instead of only id we also provide name and salary right after.

Theinput1 2 4 6 -1 -1 7 -1 -1 5 -1 9 -1 -1 3 8 -1 -1 -1 ,basedonthislistthecreate_company() will create the given company hierarchical structure. Here we have followed the convention that at first

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
we have the employee id (and name and salary which is not included here for the sake of comprehen- sibility) of the CEO followed by the employee id of subordinate one. Then we will have the values assuming subordinate one to be at top. Then followed by ids assuming subordinate two to be on top. This is called a pre-order traversal and you can read about it more online here.

The actual input will be something like 1 Prakash 1000 2 Bansal 300 4 Jain 100 and so on, note that when we have a NULL pointer there is no name or salary given. We handle this in the driver code. This order will always be unique for a company and we handle the creation of the same. Some explanations –

1. Here the CEO is 1 as it is at the top, he has no manager/boss at it’s top and we access all the other employees using the CEO only.

2. The Employee 4 has two pointers subordinate_one and subordinate_two, they point to employees with id 6 and id 7 respectively.

3. The employee with id 5 has its subordinate_one as NULL but it’s subordinate_two points to a employee with id 9.

4. All the ids are non-negative and unique.

5. The Interns i.e. – 6,7,8,9 have both their subordinates as NULL

If the input for the company was 5 2 -1 -1 3 -1 -1 then the company would be the follows. The first value is always the CEO, followed by the subordinate_one team. The subordinate_one team starts at 2 and has both pointers as NULL as the input is -1 and the team with subordinate_two on top starts at 3 with both pointers as NULL. Here the actual input to the starter code is 5 Gate 10000 2 Nadela 5000 -1 -1 3 Ballmer 6000 -1 -1. Here there will be three employees. The employee with id as 5 will have his name as Gates and his salary as 10000. Similarly

5 23

Anotherexampleis5 2 6 -1 -1 -1 3 -1 1 -1 -1thenthehierarchywouldbe- 5

23

6 NULL NULL 1

NULL NULL NULL NULL

The first value is the CEO then subordinate_one’s team input will start at 2, then we will give the CEO’s subordinate_one’s subordinate_one’s id with value 6. 6 has both pointers NULL as the two next numbers are -1. Similarly the CEO’s subordinate_two team is made. You do not have to handle creation of the company as that is done by the starter code. You only have to use this structure for implementation of the functions. The above explanation is so that yo can give your own custom input in the input.txt file

Functions to be implemented are as below:

</div>
</div>
<div class="layoutArea">
<div class="column">
FUNCTIONS:

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
<ol>
<li>double get_average_salary(int emp_id):

This function takes a parameter emp_id as Employee ID and return the average salary of the team which he is the team head.(Remember: CEO is the head of the company). You do not have to round off or truncate just return the actual double value.</li>
<li>void get_all_bosses(int emp_id):

This function takes the parameter emp_id as Employee ID and prints ids of all the team heads of the teams in which employee is working starting from the CEO till his boss. If there is no boss, print -1. For ex. – if we call get_all_bosses(9) in the Fig1. then it would print names of the employees with IDs 1,2,5 all in same line with spaces thus the output will be 1 2 5.</li>
<li>void same_last_names(int emp_id):

This function takes the parameter emp_id and prints the employee ids of all the employees in the company, who have the same last name as of the employee with id emp_id (including him) all in same line with spaces. You must print them according to there ascending order of their levels. If two person have the same level and same last name then you can print them in any order.</li>
<li>int get_first_common_boss(int emp_id1,int emp_id2):

This function takes two parameters emp_id1 and emp_id2 and returns the first common boss of both the employees. The first common boss is defined as the team head of the team, with least number of employees of which both employees are part of.</li>
</ol>
Important Notes:

<ol>
<li>You can import Lists from previous assignment (Assignment 10), if needed. We are releasing the solutions, you can make the necessary changes and include it in the headers file or maybe copy-paste the code. If you include in the header file you must include the other file in the submission as well or it would not run.</li>
<li>The emp_id will always be an id of employee in the company and we will not give random values here.</li>
<li>The level may not be valid.</li>
</ol>
Below we provide a description of the input.txt file that is given to you along with starter-code for more clarity. You may change the file to test your code on various other inputs. We have also provided a Makefile that enables you to compile your code and then run it on the given input.txt file. Just use the command make on the terminal. For more information on makefiles, refer here and here.

INPUT: 1

2 3 4 5 6 7 8 9

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
1 smith 10000 2 kumar 2000 4 gates 400 6 bansal 5000 -1 -1 7 jain 67 -1 -1 5 yadav 22 -1 9 kumar 789 -1 -1 3 taylor 67 8 smith 111 -1 -1 -1

<pre>7
get_first_common_boss 1 4
get_first_common_boss 6 9
same_last_names 1
get_average_salary 2
get_all_bosses 6
get_all_bosses 1
get_all_bosses 2
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
OUTPUT:

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
1 smith 10000 2 kumar 2000 4 gates 400 6 bansal 5000 -1 -1 7 jain 67 -1 -1 5 yadav 22 -1 9 kumar 789 -1 -1 3 taylor 67 8 smith 111 -1 -1 -1

1

2

18 1379.67 124 -1

1

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

2 3 4 5 6 7 8

</div>
</div>
<div class="layoutArea">
<div class="column">
EXPLANATION The structure that gets built is –

1

23

4 5 8 NULL

6 7 NULL 9

<ol>
<li>The first common team in which both 1 and 4 work is the organization itself so team head of the organization is 1 so print.</li>
<li>The first common team which 6 and 9 work is the team with head 2 so first common boss is 2.</li>
<li>Last names of employee 1 is ’smith’ and employee 8 is also ’smith’ and as level of employee 1 is
less so we print 1 8(seperated by a space).
</li>
<li>The team of which 2 is the head has employees 2, 4, 6, 7, 5, 9. Hence the average salary calculated
turns out to be 1379.67.
</li>
<li>Team head of the teams which 6 works under is 4 and then if we go up a level then team head of the team in which 6 work in is 2 and if we again go up a level then we reach the organization and team head of the organization is CEO – 1. So we print in the ascending order of the levels so finally we print 1 2 4.</li>
<li>Since no level above CEO so we print -1.</li>
<li>Team head of the team which 2 works under is 1.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
