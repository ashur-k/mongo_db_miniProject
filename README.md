# Introduction:
    This is mini project that I have created watching as my student learning module. I was suppose to
    create a mongo data base and then from python command prompt, I was supposed to find, add, delete and create 
    database entries.

# Implementaiton:
    Its a simple straight forward project with straight forward codes, easy to understand and follow along.
    I have 7 main functions as following other than database connection functions. All funmctions run in a loop which only breaks when user asks to exit from the code.
    ### main_loop():, get_record():, def show_menu():, def add_record():, def find_record():, def edit_record():, def delete_record():
# Installed Packages:
    dnspython==1.16.0
    pymongo==3.10.1

# Things that I have learnt:
    Now projects are complicated for me fir I have realsied setting and strting a project and running commands needs attention and accuracy.
    For e.g. what is going to be in requirements file, setting up envioronment variavles, installing packages, knowing what are their names and commands.
    I have entered all steps in new_project_implementation doc.

# Problems I faced:
    I haven't face any major problems during this project, and tutors were very helpful, they have warned me about problems already.
    At start of project I was suppose to add a line to main folder to bashcrc file. Line was suppose to add username and password of database.
    but later with tutors help I acheived same task by adding those files to env.py, which I also added to .gitignore so actual username password don't goes to
    github repo. But for future refrences I have updated setup instructions in project implemntaion.txt. 

    Second at a point when I implemented find data from database function, I realised my queries were not able to find any data from database. It was becasue I was not using .lower and .captialize, in way how 
    I was suppose to and that my code not to find entries from database becasue of case senstivity issues.

    I also made simple mistake for k for key in loop which was capital so it ends up to show error which I think was corrected in a instance. 



