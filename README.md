todo 
================================
todo is a lightweight ruby to-do system. 

The inspiration for writing this was simple:

*  I want something very easy and fast in my home directory to keep track of my day-to-day sysadmin tasks.
*  I didn't find anything lightweight out there already available.
*  I love ruby and want to keep learning.



Examples
------------------------
1. List all of your todo tasks

        andysource:~ $ todo -le
        Action => reading

        Choices:
        1) Add remove function to todo
        2) Testing todo

        Choice => 1


        ------------------------------------

        Title: Add remove function to todo

        Description: Just realized I don't have a remove function intodo. Need to implement.

        Priority: 7

2. Create a new task

        andysource:~ $ todo -cr
        Action => creating

        ## New Entry
        Title: Add in update task function


        Description: Need to add the update task. It's nearly done, just need to implement it.


        Priority (1-10): 8

        Successfully wrote /home/awojnarek/.todo/1359594990.entry

