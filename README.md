# Advent of Code 2022

### coming to you daily until i give up.


<b>log day 4:<br></b>
*12-4-22*<br>

bit of a slog today, my foot is bothering me so working from the<br>
living room makes it a little bit of a challenge. the beginning<br>
is very much the same, dissect the input into strings as required.<br>
once the numbers are extracted from the strings, it was just a <br>
matter of coming up with the right query. i started with something<br>
more complex with a bunch of ifs/elifs/else but realized that it <br>
was actually a pretty simple math range problem.<br>

the second part was mostly copy and paste. again, it's just a<br>
different type of triggering based on the relationship between<br>
the numbers in the input list. i found today to be more about<br>
getting the data in the right form.<br>

<b>log day 3:<br></b>
*12-3-22*<br>

this one felt like a return to the last previous couple of years,<br>
where i go in kind of a default mode to using loops like they're<br>
going out of style. i remember looking at the aoc subreddit and<br>
being super intimidated by the one line solutions or super <br>
efficient solutions. i'm sure i could probably create the dictionary<br>
map and create that in a more clever way.<br>

when i was originally writing part 1 here, i noticed that as <br>
i loop through, there were certain letters in each of the strings<br>
that were appearing multiple times. this was causing my count to<br>
count multiple times. to get rid of this, i used the built-in set<br>
function which creates a set of all occurring characters, leaving<br>
out duplicates. <br>

part 2 was very similar to part 1, but i had to do a little bit of<br>
math so the strings are indexed through properly.<br>


<b>log day 2:<br></b>
*12-2-22*<br>

i remember from last year that i created many elif statements. <br>
this problem reminded me of that, but i also recalled how <br>
python 3.10 introduced structural pattern matching. i've never<br>
used the technique before, so figured it was worth giving a try.<br>
i found that i didn't have 3.10 installed on my local machine,<br>
so i went and installed with brew. i found that because i already<br>
had python3 alias allocated, brew made python3.10 and pip3.10 the<br>
hyperlinks. i updated my .zconfig accordingly. i also installed<br>
jupyterthemes and used the onedork theme.<br>

there's probably a better, more programmatic way to tally up the <br>
scores for the two problems, but i am trying to solve the problems<br>
and sometimes it's less cumbersome to be too highfalutin with the code.<br>

<b>log day 1:<br></b>
*12-1-22*<br>

this is giving me the opportunity to become more familiar with .gitignore,<br>
using virtual environments, and honing into my IDE preference. currently <br>
finding jupyter notebook hosted locally, installed via terminal with pip<br>
on top of a venv to be the best methodology. it has code completion with<br>
tab, and "lookup" of embedded help menus for scripts with shift-tab. tried<br>
to not install numpy this go around. 😄
