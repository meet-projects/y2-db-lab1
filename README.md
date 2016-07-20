# Databases lab 1

### Check out the code

Type the following commands into a terminal:

    git clone https://github.com/meet-projects/y2-db-lab1

### Set up python

Here's what you run the first time after you log in:

    exec bash
    wget http://tinyurl.com/MEETpythonY2
    source MEETpythonY2

If you have already run the code above but you've opened a new terminal window, please run:

    exec bash
    source ~/y2-venv/bin/activate

### Exercise: setting up tables

In `database_setup.py`, fill in the code to create a table for companies. Each
company should have a name, the date it was founded, number of employees, and a
description of what the company does.

Once you're done, here's how to check your work:

1. Run this to set up the database:

    ```
    python initialize.py
    ```

   This creates a file called `lab1.db` with the database. Right now, there are
   no rows, so it only has the column headings. 

2. Run this to print the database. You'll be using the `print_databases.py`
   script a lot for the rest of the labs and for your projects.

    ```
    python print_databases.py lab1.db
    ```

