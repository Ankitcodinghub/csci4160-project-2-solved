# csci4160-project-2-solved
**TO GET THIS SOLUTION VISIT:** [CSCI4160 Project 2 Solved](https://www.ankitcodinghub.com/product/csci4160-project-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;28194&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;4.8&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;4.8\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI4160 Project 2 Solved&quot;,&quot;width&quot;:&quot;132.4&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 132.4px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            4.8/5 - (5 votes)    </div>
    </div>
<strong>Goal: </strong>

This assignment serves several purposes:

<ul>
<li>to be familiar with flex</li>
<li>to understand lexical analysis using the existing tool</li>
</ul>
&nbsp;

<strong>Description: </strong>

In this assignment, you are required to use flex – a scanner generator to generate a scanner for Tiger language. The manual for Tiger language can be found at the class repository: Tiger\manual.pdf.

&nbsp;

&nbsp;

<strong>Tiger language: </strong>

The reserved words of the language are:&nbsp; <em>while, for, to, break, let, in, end, function, var, type, array, if, then, else, do, of, nil.&nbsp; </em>

&nbsp;

The punctuation symbols used in the language are:

<em>,&nbsp; :&nbsp; ;&nbsp; (&nbsp; )&nbsp; [&nbsp; ]&nbsp; {&nbsp; }&nbsp; .&nbsp; +&nbsp; –&nbsp; *&nbsp;&nbsp; /&nbsp; =&nbsp; &lt;&gt;&nbsp; &lt;&nbsp; &lt;=&nbsp; &gt;&nbsp; &gt;=&nbsp; &amp;&nbsp; |&nbsp; :=&nbsp; </em>

&nbsp;

The string value that you return for a string literal should have all the escape sequences translated into their meanings.

&nbsp;

There are no negative integer literals; return two separate tokens for -32.

&nbsp;

Detect unclosed comments (at end of file) and unclosed strings.

&nbsp;

<strong>Tips and Requirements</strong>:

&nbsp;

Your lexer should use regular expressions to do the work EXCEPT for the nesting counting.&nbsp; For example, don’t find a beginning quote and then use C++ code to look for matching end quote… use regular expression(s)….

&nbsp;

The comments in Tiger language is the same as C style comments that start with /* and end with the matching subsequent */. Any symbol is allowed within a comment. However, the comments can be nested, i.e.,

/* this is a line

/* this is ok

As many lines as you desire

This one only has three

*/&nbsp; this closes the nested comment */&nbsp; // this closed the first one.

&nbsp;

Nesting can be of any level.&nbsp; Comments are ignored similar to whitespace. To handle nested comments, you will need a counter within lexer that counts the beginning of comment and decrements when ending.&nbsp; The comment is completed when it reaches zero.

&nbsp;

String literal is a sequence, between quotes (“), of zero or more printable characters, spaces, or escape sequences. Each escape sequence is introduced by the escape character \, and stands for a character sequence. The allowed escape sequences are as follows (all other uses of \ being illegal):

<ul>
<li>\n &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; a character interpreted by the system as end-of-line.</li>
<li>\t &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; TAB</li>
<li>\” &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; the double-quote character (“)</li>
<li>\\ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; the backslash character (\)</li>
</ul>
&nbsp;

<strong>What to do in this project? </strong>

You need to provide rules to recognize <strong>reserved words</strong> (<em>while, for, to, break, let, in, end, function, var, type, array, if, then, else, do, of, nil)</em>, <strong>punctuation symbols</strong> (<em>,&nbsp; :&nbsp; ;&nbsp; (&nbsp; )&nbsp; [&nbsp; ]&nbsp; {&nbsp; }&nbsp; .&nbsp; +&nbsp; –&nbsp; *&nbsp;&nbsp; /&nbsp; =&nbsp; &lt;&gt;&nbsp; &lt;&nbsp; &lt;=&nbsp; &gt;&nbsp; &gt;=&nbsp; &amp;&nbsp; |&nbsp; :=</em>), <strong>comments</strong>, <strong>identifiers</strong>, <strong>integer literals</strong>, and <strong>string literals</strong>. More specifically,

<ul>
<li>For white space character like “ “, \n, and \t; recognize them and discard it.</li>
<li>For each recognized reserved words , and punctuation symbols, return their corresponding tokens in the rule action. All tokens are defined in tokens.h file.</li>
<li>For comments, just ignore all content in the comments. Make sure your rules recognize nested comments.</li>
<li>For integer literal, recognize it and return the INT token. Make sure you store the associated integer value to variable <em>ival</em>.</li>
<li>For identifier, recognize it and return the ID token. Make sure you store the associated name to variable <em>sval</em>.</li>
<li>For string literal, it is better to use start condition o For the double quote (“) marking the beginning of the string literal, reset the variable <em>value</em> to be an empty string, modify variables beginLine and beginCol, and start</li>
</ul>
STRING condition; o For all rules under STRING condition that recognize part of the string literal, append&nbsp; the recognized part to the variable <em>value</em>;

<ul>
<li>For all rules under STRING condition that finds an error (like illegal escape sequence, unclosed string), report the error.</li>
<li>For the closing double quote (“), copy variable <em>value</em> to <em>sval</em>, just like the actions in identifier rule, and start the INITIAL condition.</li>
</ul>
&nbsp;

Make sure the provided function <strong>newline()</strong> is called for every newline character in the source file.&nbsp; Make sure the provided function <strong>error()</strong> is called for every recognized errors (illegal character, unclosed comments/strings, illegal escape character sequences, etc.). <strong>Other than calling function error(); there should be no output statement in rule actions. </strong>

<strong>&nbsp;</strong>

<strong>Instructor provided files in the class repository </strong>

&nbsp;

The following files are provided by the instructor:

<ul>
<li>Folder FlexProject. This contains a sample Visual Studio 2010 project. If you want to use this provided project for this assignment instead of creating your own project from scratch, please pay attention to the following:
<ul>
<li>You have installed the Flex and Bison as specified in the class repository document:</li>
</ul>
</li>
</ul>
How-to\flex and bison\ flex and bison installation.doc

Make sure the folder (like c:\gnuWin32\bin) containing flex.exe/bison.exe is added to your path.

<ul>
<li>Make sure instructor provided FlexLexer.h and flex.skl are copied to the correct location as specified in the first 2 pages of the following document in the class repository:</li>
</ul>
How-to\flex and bison\windows\ HOWTO-C++-flex-bison-Visual Studio.doc

<ul>
<li>Skeleton source files provided in the sample project are listed below:
<ul>
<li>h: contains the definition of all tokens and definition of YYSTYPE, which is a structure to hold values associated with matched token.</li>
<li>h: contains the definition of error handler</li>
<li>cpp: the driver</li>
<li>ll: a flex skeleton file for this project. In this assignment, you only need to work on this file. No change on other files is necessary.</li>
<li>tig, test1.tig, test2.tig: different test program of tiger language</li>
</ul>
</li>
<li>pdf: this file</li>
<li>doc: the rubric used to grade this assignment.</li>
<li>txt, test1.txt, and text2.txt. These are instructor provided output for test0.tig, test1.tig, and test2.tig, respectively. Your output may be different depending on how you handle string errors.</li>
</ul>
