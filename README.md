# Practical1
Starter repository for Practical 1

# Question 1

- What is the difference between a python package and a module (\emph{in your own words!})?

- List the full set of packages installed in your virtual environment.

- List 3 sites where you can download/install python packages from.

- In what directory are python packages installed on your machine?

- Run the following command to install a simple python package on your system

```bash
pip install sudoku_maker	
```

Check it works by running:

```bash
sudoku_maker	
```

After running the `pip` command, what files did this add/modify in your virtual environment?



# Question 2

For this question, you will create a simple python package and upload it to github. You will then install the package in your Amazon EC2 instance and check it works. Don't worry if you don't know how to do all the parts just yet. The point of doing this is to get you up and running with the various tools and check that everything is working.


- python
  Make sure you have anaconda installed
- eclipse
  Get the `neon` version of Eclipse and pydev
- github
  Sign up for an account on github if you don't have one already
- Amazon EC2
  Talk to me or the demonstrators for a key


*Keep a log of all the steps you take to do these task (a text log or screenshots).*


- On your laptop, create a simple python project to find the system information on your machine (start with basic information, like platform, machine name, operating system, etc...)
- Create a `setup.py` file to allow the project to be installable using pip.
- Upload the project to github.
- Log in to your EC2 account (and configure your virtual environment if necessary).
- Install your package directly from github:

```bash
pip install git+https://github.com/username/project
```

- Run the script which your package just installed and report the output.


