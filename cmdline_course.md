---
layout: default
---

<dl>
  <dt>Introduction to the Command Line course</dt>
    <dd>This course was about learning the basics of using command line tools in Unix. The emphasis was on tools useful for linguists, such as various text editing tools. The course serves as a good foundation for other courses where the command line environment is used.</dd>
<p>
<table>                                                                                                                                                                                                     <tr>
<th>Course symbol</th>                                                                                                                                                                                      <th>Full name of course</th>                                                                                                                                                                                <th>Term
</th>
</tr>
<tr>
<td>KIK-LG219</td>
<td>Command line tools for linguists</td>
<td>Autumn 2020</td>
</tr>
</table>
<hr>
<p>
<dl>
  <dt>Week 1: Introduction to Command Line Environments</dt>
    <dd>Well, as the name suggests, this was the introductory lecture to the course. We learned some basic Unix commands, such as <b>ls</b> and <b>mkdir</b>, and how to view texts files.</dd>

<p><p>
<u>#### An example of some code I used on this lecture:</u>
<p><p>

<i><dd>>>> echo Hello, World! <h5>(Prints the text 'Hello, World!')</h5></dd></i>
<p>
<hr>
<p>

<dl>
  <dt>Week 2: Navigating a Unix system</dt>
  <dd>In week 2, we learned how to copy, move and remove directories, what system directories are, and we connected to the remote puhti server.</dd>


<p><p>
<u>#### An example of some code I used on this lecture:</u>
<p><p>
    <i><dd>>>> emacs hello_world.txt <h5>(Opens hello_world.txt in the emacs text editor.)</h5></dd></i>
<p>
<hr> 
<p>

<dl>
  <dt>Week 3: Basic Corpus Processing</dt>
  <dd>In week 3, we learned about standard streams, character encodings and the differences between Unix and Windows text files. The <b>head</b>, <b>tail</b>, <b>uniq</b> and <b>sort</b> commands were interesting. </dd>

<p><p>
<u>#### An example of some code I used on this lecture:</u>                                                                                                                                                         <p><p>
    <i><dd>>>> sort -u hello_world.txt <h5>(Sorts hello_world.txt and removes duplicates.)</h5></dd></i>
<p>
<hr> 
<p>

<dl>
  <dt>Week 4: Advanced Corpus Processing</dt>
  <dd>In week 4, we dived deeper into corpus processing. <b>sed</b> was a nice and powerful new text-processing command. Very useful. I learned to pipe various commands together.</dd>

<p><p>
<u>#### An example of some code I used on this lecture:</u>
 <p><p>
     <i><dd>>>> echo day | sed s/day/night/ <h5>(Prints 'day' on screen BUT changes it into 'night', meaning 'night' (instead of 'day') is printed on screen.)</h5></dd></i> 
<p>
<hr> 
<p>
<dl>
  <dt>Week 5: Scripting and Configuration Files</dt>
  <dd>In week 5, scripts made their first appearance on the course. It was very handy to bundle a bunch of commands together instead of writing them individually. Variables expanded my horizons, too.</dd>

<p><p>
<u>#### An example of some code I used on this lecture:</u>                                                                                                                                                          <p><p>
<i><dd>diff $1 $2 > /dev/null <h5>(Shows how the two files differ AND does not print any error messages on screen.)</h5></dd></i>
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
<dd><i>cat $1 >> $2</i><h5> (Appends the contents of one file to the end of another file.)</h5></dd>
<p>
<hr> 
<p>

<dl>
  <dt>Week 7: Version Control</dt>
  <dd>This week we learned about version control, Jekyll and Git. The main points included working with Git, branches, repositories, and how to publish on GitHub something you've created on your local machine (in Ubuntu). It was a bit tricky to get everything working on GitHub, but I think I cracked it in the end.
<p><p>
<u>#### An example of some code I used on this lecture:</u>
<p><p>
   <dd><i>bundle exec jekyll serve</i><h5> (Runs the Jekyll server version specified in the Gemfile.)</h5></dd>
<hr>
<p>
<img src="https://www.vectorkhazana.com/assets/images/products/have_a_nice_da.jpg">

