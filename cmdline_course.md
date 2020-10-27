---
layout: default
---

<dl>
  <dt>Introduction to the Command Line course</dt>
    <dd>This course was about learning the basics of using command line tools in Unix. The emphasis was on tools useful for linguists, such as various text editing tools. The course serves as a good foundation for other courses where the command line environment is used.</dd>
<p>
<hr>
<p>
<dl>
  <dt>Week 1: Introduction to Command Line Environments</dt>
    <dd>Well, as the name suggests, this was the introductory lecture to the course. We learned some basic Unix commands, such as <b>ls</b> and <b>mkdir</b>, and how to view texts files.</dd>

<p><p>
<u>#### An example of some code I used on this lecture:</u>
<p><p>

<i><dd>>>> echo Hello, World!</dd></i>
<p>
<hr>
<p>

<dl>
  <dt>Week 2: Navigating a Unix system</dt>
  <dd>In week 2, we learned how to copy, move and remove directories, what system directories are, and we connected to the remote puhti server.</dd>


<p><p>
<u>#### An example of some code I used on this lecture:</u>
<p><p>
    <i><dd>>>> emacs hello_world.txt</dd></i>
<p>
<hr> 
<p>

<dl>
  <dt>Week 3: Basic Corpus Processing</dt>
  <dd>In week 3, we learned about standard streams, character encodings and the differences between Unix and Windows text files. The <b>head</b>, <b>tail</b>, <b>uniq</b> and <b>sort</b> commands were interesting. </dd>

<p><p>
<u>#### An example of some code I used on this lecture:</u>                                                                                                                                                         <p><p>
    <i><dd>>>> sort hello_world.txt</dd></i>
<p>
<hr> 
<p>

<dl>
  <dt>Week 4: Advanced Corpus Processing</dt>
  <dd>In week 4, we dived deeper into corpus processing. <b>sed</b> was a nice and powerful new text-processing command. Very useful. I learned to pipe various commands together.</dd>

<p><p>
<u>#### An example of some code I used on this lecture:</u>
 <p><p>
     <i><dd>>>> echo day | sed s/day/night/</dd></i> 
<p>
<hr> 
<p>
<dl>
  <dt>Week 5: Scripting and Configuration Files</dt>
  <dd>In week 5, scripts made their first appearance on the course. It was very handy to bundle a bunch of commands together instead of writing them individually. Variables expanded my horizons, too.</dd>

<p><p>
<u>#### An example of some code I used on this lecture:</u>                                                                                                                                                          <p><p>
<i>
<dd>diff $1 $2 > /dev/null<br>if [ $? = 0 ]<br>then<br>    echo -e "0\n" # Print "0" if the two files are idential.<br>    else<br>        echo -e "1\n" # Print "1" if the two files are not identical.<br>	fi</dd>
</i>
<p>
<hr> 
<p>
	
<dl>
  <dt>Week 6: Installing and Running Programs</dt>
  <dd>In week 6, we learned about installing programs. <b>pip</b> was a handy command for that. It was interesting to learn how to use Makefiles.</dd>

<p><p>
<u>#### An example of some code I used on this lecture:</u>
<p>
<p>
<dd><i>cat $1 >> $2</i></dd>
<p>
<hr> 
<p>

<dl>
  <dt>Week 7: Version Control</dt>
  <dd>This week we learned about version control, Jekyll and Git. The main points included working with Git, branches, repositories, and how to publish on GitHub something you've created on your local machine (in Ubuntu). It was a bit tricky to get everything working on GitHub, but I think I cracked it in the end.
<p><p>
<u>#### An example of some code I used on this lecture:</u>
<p><p>
    <i><dd>bundle exec jekyll serve</dd></i>
<hr>

