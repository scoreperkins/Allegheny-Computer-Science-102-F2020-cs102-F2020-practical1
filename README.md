# cs102-F2020-practical1-starter

![](../../workflows/build/badge.svg)

## Table of Contents

* [Objectives](#objectives)
* [Introduction](#introduction)
* [Continuous Learning](#continuous-learning)
* [Assignment Reminders](#assignment-reminders)
* [Accessing the Assignment](#accessing-the-assignment)
* [Practical Assignment Tasks](#practical-assignment-tasks)
  + [Installing Programs that Support Python Programming](#installing-programs-that-support-python-programming)
  + [Converting Temperature Using the Fahrenheit and Celsius Units](#converting-temperature-using-the-fahrenheit-and-celsius-units)
  + [Running a Test Suite for a Temperature Conversion Program](#running-a-test-suite-for-a-temperature-conversion-program)
  + [Reflecting on the Practical Assignment](#reflecting-on-the-practical-assignment)
* [Automated Checks with GatorGrader](#automated-checks-with-gatorgrader)
* [Assignment Assessment](#assignment-assessment)
* [Advance Feedback on an Assignment](#advance-feedback-on-an-assignment)
* [Discussion of a Graded Assignment](#discussion-of-a-graded-assignment)
* [Additional Resources](#additional-resources)
  + [System Commands](#system-commands)
  + [Using Docker](#using-docker)
  + [Using the Docker Shell](#using-the-docker-shell)
  + [Downloading Project Updates](#downloading-project-updates)
  + [Using GitHub Actions](#using-github-actions)
  + [System Requirements](#system-requirements)
  + [Reporting Problems](#reporting-problems)
  + [Receiving Assistance](#receiving-assistance)

## Objectives

The learning objectives for this practical assignment are as follows:

- To configure Git and GitHub on your laptop and on the GitHub servers
- To transfer files from your laptop to your GitHub repository
- To use your text editor to manipulate code blocks in a Markdown file
- To use your text editor to manipulate code blocks in a Python file
- To use a Docker container to run the automated checks performed by GatorGrader
- To use a terminal window to run a Python program and observe its output
- To use a text editor and a terminal window to add functions to a Python program
- To use a terminal window to run test cases in a Pytest test suite
- To practice translating a mathematical equation to its implementation in a Python program

## Introduction

Designed for use with [GitHub Classroom](https://classroom.github.com/) and
[GatorGrader](https://github.com/GatorEducator/gatorgrader/), this repository
contains a practical assignment for an introductory computer science class that
uses the Python programming language. The source code and technical writing for
this assignment must pass tests set by the [GatorGrader
tool](https://github.com/GatorEducator/gatorgrader). When you use the `git
commit` command to transfer your source code to your GitHub repository, GitHub
Actions will initialize a build of your assignment, checking to see if it meets
all of the requirements. If both your source code and writing meet all of the
established requirements, then you will see a green ✔  in the listing of commits
in GitHub. If your submission does not meet the requirements, a red ❌ will
appear instead. Please note that, at the option of the course instructor, some
checks may be run in GitHub Actions that are not run locally by the [GatorGrader
tool](https://github.com/GatorEducator/gatorgrader).

## Continuous Learning

If you have not done so already, please read all of the relevant [GitHub
Guides](https://guides.github.com/) that explain how to use many of the features
that GitHub provides. In particular, please make sure that you have read the
following GitHub guides: [Mastering
Markdown](https://guides.github.com/features/mastering-markdown/), [Hello
World](https://guides.github.com/activities/hello-world/), and [Documenting Your
Projects on GitHub](https://guides.github.com/features/wikis/). Each of these
guides will help you to understand how to use both [GitHub](http://github.com) and
[GitHub Classroom](https://classroom.github.com/).

Students who want to learn more about how to use
[Docker](https://www.docker.com) should review the [Docker
Documentation](https://docs.docker.com/). Students are also encouraged to
review the documentation for their text editor, which is available at [VS
Code](https://code.visualstudio.com/docs). You should also review the [Git
documentation](https://git-scm.com/doc) to learn more about how to use the Git
command-line client. In addition to talking with the instructor and technical
leader for your course, students are encouraged to search
[StackOverflow](https://stackoverflow.com/) for answers to their technical
questions.

As outlined in the course schedule in the [course planning
repository](https://github.com/Allegheny-Computer-Science-102-F2020/cs102-F2020-plans),
students should also read all of the assigned readings for up to and including
the week of the semester on which this practical assignment was assigned.

## Assignment Reminders

- **Follow each step carefully**. Slowly read each sentence in this document,
  making sure that you precisely follow each instruction. Take notes about each
  step that you attempt, recording your questions and ideas and the challenges
  that you faced. If you are stuck, then please tell a technical leader or the
  course instructor what assignment step you recently completed.

- **Regularly ask and answer questions**. Please log into Slack at the start of
  the practical session and then join the appropriate channel. If you have a
  question about one of the steps in an assignment, then you can post it to the
  designated channel, discussing your questions through both Slack and the
  Google Meet designated for the class.

- **Store your files in GitHub**. Starting with this practical assignment, you
  will be responsible for storing all of your files (e.g., Python source code
  and Markdown-based writing) in a Git repository using GitHub Classroom. Please
  verify that you have saved your source code in your Git repository by using
  `git status` to ensure that everything is updated. You can see if your
  assignment submission meets the established correctness requirements by using
  the provided checking tools on your local computer and by checking the commits
  in GitHub.

- **Keep all of your files**. Don't delete your programs, output files, and
  written reports after you submit them through GitHub; you will need them
  again when you study for the course assessments and work on the other
  practical, practical, and technical challenge assignments.

- **Hone your technical writing skills**. Computer science assignments require
  to you write technical documentation and descriptions of your experiences when
  completing each task. Take extra care to ensure that your writing is
  interesting and both grammatically and technically correct, remembering that
  computer scientists must effectively communicate and collaborate with their
  team members and the student technical leaders and course instructor.

- **Review the Honor Code on the syllabus**. While you may discuss your
  assignments with others, copying source code or technical writing is a
  violation of Allegheny College's Honor Code.

## Accessing the Assignment

To access this assignment, you should go into the `#announcements` channel in
our Slack workspace and find the announcement that provides a link for it. Copy
this link and paste it into your web browser. Now, you should accept the
practical assignment and see that GitHub Classroom created a new GitHub
repository for you to access the assignment's starting materials and to store
the completed version of your assignment. Specifically, to access your new
GitHub repository for this assignment, please click the green "Accept" button
and then click the link that is prefaced with the label "Your assignment has
been created here". If you accepted the assignment and correctly followed these
steps, you should have created a GitHub repository with a name like
`Allegheny-Computer-Science-102-Fall-2020/computer-science-102-fall-2020-practical-1-gkapfham`.
Unless you provide the course instructor with documentation of the extenuating
circumstances that you are facing, not accepting the assignment means that you
automatically receive a failing grade for all of its components.

Before you move to the next step of this practical assignment, please make
sure that you read all of the content on the web site for your new GitHub
repository, paying close attention to the technical details about the commands
that you will type and the output that your program must produce. Now you are
ready to download the starting materials to your practical computer. Click the
"Clone or download" button and, after ensuring that you have selected "Clone
with SSH", please copy this command to your clipboard. To enter into your
course directory directory you should now type `cd cs102F2020`. Next, you can
type the either `ls` (on either MacOS or Linux) or `dir` (on Windows 10 Pro or
Windows 10 Enterprise) and see that there are no files or directories inside of
this directory. By typing `git clone` in your terminal and then pasting in the
string that you copied from the GitHub site you will "download" all of the code
for this assignment. For instance, if the course instructor ran the `git clone`
command in the terminal, it would look like:

```
git clone git@github.com:Allegheny-Computer-Science-102-F2020/computer-science-102-fall-2020-practical-1-gkapfham.git
```

After this command finishes, you can use `cd` to change into the new directory.
If you want to "go back" one directory from your current location, then you can
type the command `cd ..`. Finally, please continue to use the `cd` and `ls`
commands to explore the files that you automatically downloaded from GitHub. If
one of the aforementioned commands does not work correctly, then it is possible
that your terminal window is not up-to-date or not configured correctly. In this
case, please share your specific error messages with the instructor, ultimately
working to master the use of terminal commands. What files and directories do
you see? What do you think is their purpose? Spend some time exploring, telling
your discoveries to a student technical leader.

## Practical Assignment Tasks

### Installing Programs that Support Python Programming

If you have not done so already, then, in order to implement a full-fledge
Python program, you need to install the [Poetry
tool](https://python-poetry.org/docs/) for dependency management and packaging
of Python programs. After ensuring that you have Python 3.8 installed on your
laptop through Pyenv, please follow the installation instructions for Poetry.
For instance, you are using either MacOS or Linux you need to type the
following command in your terminal window `curl -sSL
https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py |
python`. Importantly, this command will only work if you have already installed
a program called `curl`. If you are using Windows 10 Pro then you will need to
follow the PowerShell installation instructions on Poetry's web site.

Now, making sure that you are in your "home base" directory for this practical
assignment, you need to install the dependencies for the `converter` program
that you will implement, debug, and observe. To complete this step you need to
type `cd converter` and then `poetry install`. What output did this command
produce? What do you think that this step did? Why is important to type these
commands? Make sure that you know the answers to these question before moving
onto the next step of the assignment.

### Converting Temperature Using the Fahrenheit and Celsius Units

After you have reviewed the structure of the provided Python source code and
reviewed the content in *Doing Math with Python*, you are ready to provide an
implementation of the functions called
`convert_celsius_to_fahrenheit(temperature: float)` and
`convert_fahrenheit_to_celsius(temperature: float)`. As you implement these
functions, your job is to ensure that they perform the requested function based
on their name and their input `temperature.` For instance, the function with the
name `convert_celsius_to_fahrenheit` should convert the provided `temperature`
in Celsius to Fahrenheit. Once your function performs the correct conversion of
the provided temperature, it should return that temperature so that it can be
used by other functions inside of the Python program. Before you move onto the
next step of this assignment, please make sure that you review the
implementation of the `convert_temperature` function. Can you explain the
purpose of this function? How does this function use the
`units.TemperatureUnitOfMeasurement` enumeration defined in a separate Python
file?

### Running a Test Suite for a Temperature Conversion Program

If you look in the Python file called `converter/tests/test_convert.py` you will
see that it contains several test cases that call the functions in the Python
program in an attempt to ensure that they are working correctly. Please take
time to review each of these test cases and work to understand how they are
testing the functions in the file called `convert.py`. Importantly, please make
sure to notice that some of the test cases in the test suite contain assertions
of the form `assert converted_temperature == 32` while other tests have
assertions of the form `assert converted_temperature == approx(80, rel=1e-3)`.
Can you explain why different test cases need to have different types of
assertions? Finally, if your Python program is correct, you should be able to
run the test suite by typing `poetry run pytest` and see that it produces the
following output:

```
=========================== test session starts ============================
platform linux -- Python 3.8.5, pytest-5.4.3, py-1.9.0, pluggy-0.13.1
rootdir: /home/gkapfham/working/teaching/github-classroom/Allegheny-Computer-Science-102-F2020/solutions/cs102-F2020-practical1-solution/converter
collected 8 items

tests/test_convert.py ........                                       [100%]

============================ 8 passed in 0.02s =============================
```

### Reflecting on the Practical Assignment

Once you have finished both of the previous technical tasks, use your text
editor to answer all of the questions in the `writing/reflection.md` file. For
instance, you should provide the output of the Python program in a fenced code
block, explain the meaning of the three provided commands, and answer all of the
other questions about your experiences in completing this practical assignment.

## Automated Checks with GatorGrader

In addition to meeting all of the requirements outlined in this assignment
sheet, your submission must pass the following checks that
[GatorGrader](https://github.com/GatorEducator/gatorgrader) automatically
assesses:

If [GatorGrader's](https://github.com/GatorEducator/gatorgrader) automated
checks pass correctly, the tool will produce the output like the following in
addition to returning a zero exit code (which you can access by typing the
command `echo $?`). You will need to run
[GatorGrader](https://github.com/GatorEducator/gatorgrader) in a Docker
container by following the steps in the [Using Docker](#using-docker) section.

- The command `cd converter; poetry install; poetry run python converter --from-unit Fahrenheit --to-unit Celsius --temperature 32; cd ..` executes correctly
- The `convert.py` in converter/converter has at least 4 multiple-line Python comment(s)
- The `convert.py` in converter/converter has at least 4 single-line Python comment(s)
- The `convert.py` in converter/converter has exactly 0 of the `TODO` fragment
- The `convert.py` in converter/converter has exactly 1 of the `from converter import units` fragment
- The file `convert.py` exists in the converter/converter directory
- The file `__main__.py` exists in the converter/converter directory
- The file `reflection.md` exists in the writing directory
- The file `test_convert.py` exists in the converter/tests directory
- The `__main__.py` in converter/converter has at least 2 multiple-line Python comment(s)
- The `__main__.py` in converter/converter has at least 4 single-line Python comment(s)
- The `__main__.py` in converter/converter has exactly 0 of the `TODO` fragment
- The `reflection.md` in writing has at least 3 of the `code` tag
- The `reflection.md` in writing has at least 400 word(s) in total
- The `reflection.md` in writing has exactly 0 of the `Add Your Name Here` fragment
- The `reflection.md` in writing has exactly 0 of the `TODO` fragment
- The `reflection.md` in writing has exactly 1 of the `list` tag
- The `reflection.md` in writing has exactly 3 of the `code_block` tag
- The `reflection.md` in writing has exactly 8 of the `heading` tag
- The repository has at least 5 commit(s)
- The `test_convert.py` in converter/tests has at least 9 multiple-line Python comment(s)
- The `test_convert.py` in converter/tests has exactly 0 of the `TODO` fragment
- The `test_convert.py` in converter/tests has exactly 1 of the `from converter import units` fragment
- The `test_convert.py` in converter/tests has exactly 1 of the `from pytest import approx` fragment

```
        ┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
        ┃ Passed 24/24 (100%) of checks for cs102-F2020-practical1! ┃
        ┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛
```

## Assignment Assessment

Again taking inspiration from the principles of [specification-based
grading](https://www.amazon.com/Specifications-Grading-Restoring-Motivating-Students/dp/1620362422),
the grade that a student receives on either a practical assignment or a
technical challenge will be based on whether or not it meets the standards for
technical work in the fields of software engineering and discrete structures as
evidenced by:

- **GitHub Actions Build Status of Either ✔  or ❌**: Your work will receive a ✔
  if the last before-the-deadline build in GitHub Actions passes and a ✔ appears
  in the GitHub commit log instead of an ❌. The build status reported by
  GitHub Actions will only be a ✔ if the Python source code and technical
  writing in the GitHub repository pass all of both the GatorGrader checks and
  any additional checks.

## Advance Feedback on an Assignment

Students who wish to receive feedback on their work for any course assignment
should first open an issue on the issue tracker for their assignment's GitHub
repository, giving an appropriate title and description for the type of feedback
that you would like the course instructor to provide. After creating this issue,
you will see that GitHub has created a unique web site that references it. To
alert the course instructor to the fact that the issue was created and that you
want feedback on your work, please send it to him by a Slack direct message at
least 24 hours in advance of the project's due date. After the instructor
responds to the issue, please resolve all of the stated concerns and participate
in the discussion until the issue is resolved and ultimately marked as closed.

## Discussion of a Graded Assignment

Students who wish to receive feedback on their work for any graded course
assignment should leave question in the same region of Github where the course
instructor submitted the assignment's grade. For example, if the instructor
submits your grade to a pull request in your repository for a practical
assignment, then you should ask questions about your grade in that pull request,
bearing in mind the need to @-mention the course instructor in the body of your
comment. Students can continue to discuss the graded assignment with the course
instructor until they understand all the technical topics that were the
focus of the particular assignment.

## Additional Resources

### System Commands

This project invites students to enter system commands into a terminal window.
This assignment uses [Docker](https://www.docker.com) to deliver programs, such
as `gradle` and the source code and packages needed to run
[GatorGrader](https://github.com/GatorEducator/gatorgrader), to a students'
computer, thereby eliminating the need for a programmer to install them on their
development workstation. Individuals who do not want to install Docker can
optionally install of the programs mentioned in the [Project
Requirements](#requirements) section of this document.

### Using Docker

Once you have installed [Docker
Desktop](https://www.docker.com/products/docker-desktop), with MacOS and Linux
you can use the following `docker run` command to start `gradle grade` as a
containerized application, using the
[DockaGator](https://github.com/GatorEducator/dockagator) Docker image available
on
[DockerHub](https://cloud.docker.com/u/gatoreducator/repository/docker/gatoreducator/dockagator).

```bash
docker run --rm --name dockagator \
  -v "$(pwd)":/project \
  -v "$HOME/.dockagator":/root/.local/share \
  gatoreducator/dockagator
```

The aforementioned command will use `"$(pwd)"` (i.e., the current working
directory) as the project directory and `"$HOME/.dockagator"` as the cached
GatorGrader directory. Please note that both of these directories must exist,
although only the project directory must contain something. Generally, the
project directory should contain the source code and technical writing for this
assignment, as provided to a student by the instructor through GitHub.
Additionally, the cache directory should not contain anything other than
directories and programs created by DockaGator, thus ensuring that they are not
otherwise overwritten during the completion of the assignment. To ensure that
the previous command will work correctly, you should create the cache directory
by running the command `mkdir $HOME/.dockagator` on the MacOS and Linux
operating systems. However, if you are using the Windows operating system then
you will instead need to type the command `mkdir
%HomeDrive%%HomePath%/.dockagator`. Finally, if the above `docker run` command
does not work correctly on the Windows operating system, you may need to instead
run the following command to adapt to the differences in the `cmd` terminal
window:

```bash
docker run --rm --name dockagator \
  -v "%cd%:/project" \
  -v "%HomeDrive%%HomePath%/.dockagator:/root/.local/share" \
  gatoreducator/dockagator
```

Here are some additional commands that you may need to run when using Docker:

* `docker info`: display information about how Docker runs on your workstation
* `docker images`: show the Docker images installed on your workstation
* `docker container list`: list the active images running on your workstation
* `docker system prune`: remove many types of "dangling" components from your workstation
* `docker image prune`: remove all "dangling" docker images from your workstation
* `docker container prune`: remove all stopped docker containers from your workstation
* `docker rmi $(docker images -q) --force`: remove all docker images from your workstation

### Using the Docker Shell

Since the above `docker run` command uses a Docker images that, by default, runs
`gradle grade` and then exits the Docker container, you may want to instead run
the following command so that you enter an "interactive terminal" that will
allow you to repeatedly run commands within the Docker container. Don't forget
that, if you are using the Windows operating system, then you will need to use a
different command to run Docker, as explained previously in this document.
Importantly, the command that you type if you are a Windows user should still
contain the `-it` at the start of the `docker run` and the `/bin/bash` at the
end of the command. However, the other components of this command need to be
customized for the Windows operating system.

```bash
docker run -it --rm --name dockagator \
  -v "$(pwd)":/project \
  -v "$HOME/.dockagator":/root/.local/share \
  gatoreducator/dockagator /bin/bash
```

Once you have typed this command, you can use the [GatorGrader
tool](https://github.com/GatorEducator/gatorgrader) in the Docker container by
typing the command `gradle grade` in your terminal. Running this command will
produce a lot of output that you should carefully inspect. If GatorGrader's
output shows that there are no mistakes in the assignment, then your source code
and writing are passing all of the automated baseline checks. However, if the
output indicates that there are mistakes, then you will need to understand what
they are and then try to fix them.

To run one of these commands, you must be in the main (i.e., "home base")
directory for this assignment where the `build.gradle` file is located.

### Downloading Project Updates

If GatorGrader's maintainers push updates to this sample assignment and you
received it through GitHub Classroom and you would like to also receive these
updates, then you can type this command in the main directory for this
assignment:

```
git remote add download git@github.com:Allegheny-Computer-Science-102-F2020/cs102-F2020-practical1-starter/
```

You should only need to type this command once; running the command additional
times may yield an error message but will not negatively influence the state of
your Git repository. Now, you are ready to download the updates provided by the
GatorGrader maintainers by typing this command:

```
git pull download master
```

This second command can be run whenever the maintainers needs to provide you
with new source code for this assignment. However, please note that, if you have
edited the files that we updated, running the previous command may lead to Git
merge conflicts. If this happens, you may need to manually resolve them with the
help of the instructor or a student technical leader. Finally, please note that
the [Gradle plugin](https://github.com/GatorEducator/gatorgradle) for
[GatorGrader](https://github.com/GatorEducator/gatorgrader) will automatically
download the newest version of GatorGrader.

### Using GitHub Actions

This assignment uses [GitHub Actions](https://github.com/features/actions) to
automatically run [GatorGrader](https://github.com/GatorEducator/gatorgrader)
and additional checking programs every time you commit to your GitHub
repository. The checking will start as soon as you have accepted the assignment
&mdash; thus creating your own private repository &mdash; and the course
instructor and/or GitHub enables GitHub Actions on it. If you do not see either
a yellow &#9679; or a green ✔ or a red ❌ in your listing of commits, then
please ask the instructor to see whether or not GitHub Actions was correctly
enabled.

### System Requirements

This assignment was developed to work with the following software and versions:

- Docker Desktop
- Operating Systems
  - Linux
  - MacOS
  - Windows 10 Pro
  - Windows 10 Enterprise
- Programming Language Tools
  - Gradle 6.6
  - MDL 0.5.0
  - Python 3.7 or 3.8

### Reporting Problems

If you have found a problem with this assignment's provided source code or
documentation, then you can go to the [Computer Science 102 Fall 2020 Planning
Repository](https://github.com/Allegheny-Computer-Science-102-F2020/cs102-F2020-plans)
and [raise an
issue](https://github.com/Allegheny-Computer-Science-102-F2020/cs102-F2020-plans/issues).
If you have found a problem with the [GatorGrader
tool](https://github.com/GatorEducator/gatorgrader) and the way that it checks
your assignment, then you can also [raise an
issue](https://github.com/GatorEducator/gatorgrader/issues) in that repository.
To ensure that your issue is properly resolved, please provide as many details
as is possible about the problem that you experienced. Individuals who find, and
use the appropriate GitHub issue tracker to correctly document, a mistake in any
aspect of this assignment will receive extra credit towards their grade for the
course.

### Receiving Assistance

If you are having trouble completing any part of this project, then please talk
with either the course instructor or a student technical leader during the
course session. Alternatively, you may ask questions in the Slack workspace for
this course. Finally, you can schedule a meeting during the course instructor's
office hours.
