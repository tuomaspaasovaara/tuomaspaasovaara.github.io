---
layout: default
---

**Introduction to the Command Line course**


This course was about learning the basics of using command line tools in Unix. The emphasis was on tools useful for linguists, such as various text editing tools. The course serves as a good foundation for other courses where the command line environment is used.


| Course symbol        | Full name of course           | Term  |
| ------------- |:-------------:| -----:|
| KIK-LG219      | Command line tools for linguists | Autumn 2020 |

**Week 1**: Introduction to Command Line Environments

Well, as the name suggests, this was the introductory lecture to the course. We learned some basic Unix commands, such as **ls** and **mkdir**, and how to view texts files.


**#### An example of some code I used on this lecture:**

```
>>> echo Hello, World!
```
##### (Prints the text 'Hello, World!')

---

**Week 2**: Navigating a Unix system

In week 2, we learned how to copy, move and remove directories, what system directories are, and we connected to the remote puhti server.


**#### An example of some code I used on this lecture:**

```
>>> emacs hello_world.txt
```
##### (Opens hello_world.txt in the emacs text editor.)

---

**Week 3**: Basic Corpus Processing

In week 3, we learned about standard streams, character encodings and the differences between Unix and Windows text files. The **head**, **tail**, **uniq** and **sort** commands were interesting.


**#### An example of some code I used on this lecture:**

```
>>> sort -u hello_world.txt
```
##### (Sorts hello_world.txt and removes duplicates.)

---

**Week 4**: Advanced Corpus Processing

In week 4, we dived deeper into corpus processing. **sed** was a nice and powerful new text-processing command. Very useful. I learned to pipe various commands together.


**#### An example of some code I used on this lecture:**

```
>>> echo day | sed s/day/night/
```
##### (Starts to print *day* on screen BUT, before printing, changes it into *night*, meaning *night* (instead of *day*) is printed on screen.)

---

**Week 5**: Scripting and Configuration Files

In week 5, scripts made their first appearance on the course. It was very handy to bundle a bunch of commands together instead of writing them individually. Variables expanded my horizons, too.


**#### An example of some code I used on this lecture:**

```
>>> diff $1 $2 > /dev/null
```
##### (Shows how the two files differ AND does not print any error messages on screen.)

---

**Week 6**: Installing and Running Programs

In week 6, we learned about installing programs. **pip** was a handy command for that. It was interesting to learn how to use Makefiles.


**#### An example of some code I used on this lecture:**

```
>>> cat $1 >> $2
```
##### (Appends the contents of one file to the end of another file.)

---

**Week 7**: Version Control

This week we learned about version control, Jekyll and Git. The main points included working with Git, branches, repositories, and how to publish on GitHub something you've created on your local machine (in Ubuntu). It was a bit tricky to get everything working on GitHub, but I think I cracked it in the end.

**#### An example of some code I used on this lecture:**

```
>>> bundle exec jekyll serve
```
##### (Runs the Jekyll server version specified in the Gemfile.)

![Have a nice day](https://www.vectorkhazana.com/assets/images/products/have_a_nice_da.jpg "Have a nice day!")

