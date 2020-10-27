---
layout: default
---

<dl>
  <dt>Introduction to the Command Line course</dt>
    <dd>intro</dd>

<dl>
  <dt>Week 1: Introduction to Command Line Environments</dt>
    <dd>Well, as the name suggests, this was the introductory lecture to the course. We learned some basic Unix commands, such as ´ls´ and ´mkdir´, and how to view texts files.</dd>

<p><p>
#### An example of some code I used on this lecture:
<p><p>
    <dd>>>> echo Hello, World!</dd>
<p>

<dl>
  <dt>Week 2: Navigating a Unix system</dt>
  <dd>In week 2, we learned how to copy, move and remove directories, what system directories are, and we connected to the remote puhti server.</dd>


<p><p>
#### An example of some code I used on this lecture:
<p><p>
    <dd>>>> emacs hello_world.txt</dd>                                                                                                                                                                          <p>

<dl>
  <dt>Week 3: Basic Corpus Processing</dt>
  <dd>In week 3, we learned about standard streams, character encodings and the differences between Unix and Windows text files. The **head**, **tail**, uniq and sort commands were interesting. </dd>

<p><p>
#### An example of some code I used on this lecture:                                                                                                                                                         <p><p>
    <dd>>>> sort hello_world.txt</dd>
<p>

<dl>
  <dt>Week 4: Advanced Corpus Processing</dt>
  <dd>In week 4, we dived deeper into corpus processing. 'sed' was a nice and powerful new text-processing command. Very useful. I learned to pipe various commands together</dd>

<p><p>
#### An example of some code I used on this lecture:
 <p><p>
     <dd>>>> echo day | sed s/day/night/</dd> 

<dl>
  <dt>Week 5: Scripting and Configuration Files</dt>
  <dd>In week 5, scripts made their first appearance on the course. It was very handy to bundle a bunch of commands together instead of writing them individually. Variables expanded my horizons, too.</dd>

<p><p>
#### An example of some code I used on this lecture:                                                                                                                                                          <p><p>
     <dd>#!/bin/bash<p>
<p>
# script: mydiff.sh<p>
# author: tp<p>
<p>
if [ $# -ne 2 ]<p>
then<p>
    echo "ERROR: Two command line arguments required!"<p>
        echo "$0 inputfile outputfile"<p>
	    exit 1<p>
	    fi<p>
<p>
diff $1 $2 > /dev/null<p>
if [ $? = 0 ]<p>
then<p>
    echo -e "0\n" # Print "0" if the two files are idential.<p>
    else<p>
        echo -e "1\n" # Print "1" if the two files are not identical.<p>
	fi<p>

</dd>

<dl>
  <dt>Week 6: Installing and Running Programs</dt>
  <dd>text.</dd>

<dl>
  <dt>Week 7: Version Control</dt>
  <dd>This week we learned about version control, Jekyll and Git. The main points included working with Git, branches, repositories, and how to publish on GitHub something you've created on your local machine (in Ubuntu). It was a bit tricky to get everything working on GitHub, but I think I cracked it in the end.
<p><p>
An example of some code I used:
<p><p>
    <dd>Code here.</dd>


