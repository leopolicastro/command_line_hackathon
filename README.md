# Command Line Hackathon

## Setup
* `git clone git@github.com:leopolicastro/command_line_hackathon.git`. 
* `cd` into `command_line_hackathon`.
* `ls` from within the `command_line_hackathon` folder.  You should see a file called `presidents.txt` and one called `README.md`.  

## Your Task

Use only Terminal commands to achieve these goals.  No cheating by using a GUI!

* Make a new directory called `presidents`.
* Move the `presidents.txt` file into the `presidents` directory.
* Inside the `presidents` directory, make a new file called `sorted.txt`, which `sort`s the presidents in alphabetical order by first name.
* Inside the `presidents` directory, make a new file called `jameses.txt` which contains all the presidents named James (Hint: `grep`).
* Inside the `presidents` directory, make a new file called `williams.txt`, which contains all the presidents named William (Hint: `grep`).
* Inside the `presidents` directory, make a new file called `my_favorite.txt`.   Use `echo` to write the name of your favorite president inside.
* Use `curl` to download the contents of this webpage (https://en.wikipedia.org/wiki/List_of_Presidents_of_the_United_States) into a file called `presidents.html`

## Stretch Goals

* There's a secret file in this repository, which tells you Andy's favorite president, as well as the reason.  Inside the `presidents` directory, make a new file called `andys_favorite.txt`, which contains that information.
* Inside the `presidents` directory, make a new file called `presidents_with_middle_initials.txt`, which contains all the presidents with middle initials. (Hint: https://stackoverflow.com/questions/10346816/using-grep-to-search-for-a-string-that-has-a-dot-in-it)
* Inside the `presidents` directory, make a new file called `common_first_names.txt`, which has all of the first names that occur more than once.
* Grover Cleveland is listed twice because he was elected to two nonconsecutive terms, so he shouldn't really be on this list.  Figure out how to get him off the list.


