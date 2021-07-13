# Options Database

What is this?
A Database System designed for picking options for school children

Who would want this? 
Who is my client? (Stakeholders)
My clients consist of two types of people. 
One of them is a young child within the age of 15 to 16 choosing their options for a school’s sixth-form college. 
The other is a school staff member who manages the students moving from years 11 to 12 – both already within the school and outside. They or the school’s IT department can act as the admin for their school.
What is their current way of doing things?
Let’s pretend ABT’s way of doing options is the school’s way.
A group of school staff use Microsoft Word to type up the options the school offers in blocks (where they are available). They are then printed out and presented to the student like so:

The form below is then printed out for the student to fill:
In the form, the school asks for the student’s full name and details as well as their parents/carers’ details. The school then asks for the students’ options, of which there are five to choose from – one from each block.
What’s their problem with said current way?
Let’s talk about the school staff member first. They’re probably concerned about how the school uses paper to submit their sixth-form/college applications since printing paper once a year is wasteful to the environment and costs too much money, of which could go to more important areas. They may instead want to keep up with the times or out-do their rival/the nearby better school.
Now to the student. They may not have any money to print the paper at home or could be very forgetful in the sense that they keep losing the paper.
How is it supposed to work?
What’s this supposed to include? (Main components)
Fast load times
Fast and ultra-secure data transfer
What’s my proposed way of doing things from now on? (The plan as of July 2021)
The school admin enters the website and registers their school. After an authentication process, they are given their own page. On the page, they outline the subjects their school offers and their grades required to do them.
The student enters the website and registers themselves. After they’ve gone through the sign-up process, they will be given a hub of their own, where they look at school recommendations and tips to pass student interviews. There will be a visible search bar for them to search for their school of choice. When they find their school of choice, and look up their subjects and required grades, they are going to submit their own.
Now, with the given information the system has given the school, the admin will handle the rest of the procedure outside of the website: accepting students, holding interviews and the like.
Comparisons with existing software
Croydon Council Application form (https://croydon.ac.uk/application-form/) allows swift and easy interface for students to apply to their school
Show My Homework/Satchel One (www.satchelone.com) and the official UCAS website (www.ucas.com) allow “buzzwords” or dropdown-menus for users to pick the school they’re applying to or from.
Area in need of development
The login system is not as thought out at the time of typing this.
The customisation that the school will receive for their page is not decided.
What solutions does this problem fix?
These are the reasons why I believe a computational approach to this problem is the best one.
Computational solutions 
Bringing options to one place will help applying for sixth-form become much easier
Financial solutions 
The cost for printing paper is quite large, so the site could cut it down significantly.
Environmental solutions
As with all technology, the end result will be environmentally safer due to there being a smaller need to cut down trees (though that would be more so if the network is bigger).
Why wouldn’t it work?
While I believe this is a good solution to the problem, the biggest reason why it will NOT work is because not all students have a stable or working internet connection. If schools exclusively use the site, students cannot apply to them if they truly wanted to. Another reason is that is that if there is a server-wide glitch or issue in the system, all schools on the site will be in grave danger. To avoid this, the site can recommend schools print backup application papers – and even so, it would seem as though not only are they back on square 1, they also have to pay more money!
What will I use to make this work?
Languages
The problem could be solved with many different types of programming languages. As such, I was very excited with what I could
Conceived
I did truly consider using languages that wouldn’t make sense to use in a project like this (like Rust with WebAssembly, a language used alongside a type of code – both of which I was far too difficult and dangerously inexperienced to settle with).
When I became more grounded on the matter, there were three options that came to mind.
JavaScript is quite well known to many as the simple, easy programming language of the internet (and arguably the best choice for the project) but, to me, as a language that feels very alien to me. As a result, I became very repulsed to use it – especially since I was introduced to Java and Python, languages that follow very similar structures compared to something like JavaScript.
PHP is the most popular server-side language and is used in many big-name websites like Facebook and Wikipedia; I do not like using it. My experience with the languages wasn’t so bad. It’s just that I have had less control over what I want to do with my project unless I pay money. Websites that let me host my site for free require wildly outdated versions of the languages and their frameworks. The experience was infuriating for all the worst reasons.  
Final Decision
I have ended up settling with Python. Python is a simple but very flexible and, as a result, extremely powerful language. It’s also one that I am most familiar with than the above. Python is quite well known to be very prominent in the web development world as of recent with frameworks that bridge between Python and Web Development.
Frameworks
Now that my programming language has been chosen on, I need to choose my framework.
Conceived
There were two that came to mind; the most popular ones.
Django is the framework well-known to be utilised by big-name companies like Instagram and Youtube. The biggest issue with Django is how it’s very complicated to understand. I know this because it was very hard to work with Flask.
Final Decision
In the end, I’ve decided to use Flask. Though it is used mainly for much smaller projects than Django, it’s much easier to understand. I also have experience working with the framework and felt satisfied working with this than the other site.

