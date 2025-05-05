# information-security-systems-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [Information-Security-Systems Assignment 3 Solved](https://www.ankitcodinghub.com/product/information-security-systems-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98694&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Information-Security-Systems Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
<ul>
<li>Access Control Logging
For this assignment, you will develop an access control logging system using the C programming language. The access control logging system will monitor and keep track of every file access and modification that occurs in the system. So, each file access or file modification will generate an entry in a log file. This log file will be inspected by a separate high privileged process.

You will use “LD_PRELOAD”, which instructs the linker to bind symbols provided by a shared library before any other library. This way, you will override the C standard library functions that handle file accesses and modifications (fopen, fwrite) with your own versions in order to offer the extra functionality you are requested.

Important: The current assignment is required for your next assignment. This means that if you skip the current assignment, to fully implement the next one you will have to implement both.

Step 1: Access Control Logging tool

As reported above you are requested to develop a shared library, named “logger.so”, that overrides the C standard I/O library using the LD_PRELOAD. Specifically, your own versions of fopen and fwrite will collect and log the needed information for each file access, before continuing with the standard I/O operation. The log file should be named “file_logging.log”. The log file must be
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
stored somewhere, where it can be accessible by all users. Each log entry should contain the following information:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<ol>
<li>UID: The unique user ID assigned by the system to a user (hint: see getuid() function).</li>
<li>File name: The path and name of the accessed file.</li>
<li>Date: The date that the action occurred.</li>
<li>Timestamp: The time that the action occurred.</li>
<li>Access type: For file creation, the access type is 0. For file open, the access type is 1. For file write, the access type is 2.</li>
<li>Is-action-denied flag: This field reports if the action was denied to the user with no access</li>
</ol>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
privileges. It is 1 if the action was denied to the user, or 0 otherwise.

7. File fingerprint: The digital fingerprint of the file the time the event occurred. This digital

fingerprint is the hash value of the file contents (hint: You can use the md5 hash functions: https://www.openssl.org/docs/man1.1.0/man3/MD5_Init.html ).

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="section">
<div class="layoutArea">
<div class="column">
Notes

 Each log entry should have all the above 7 fields. In order to find the filepath from FILE*: from the

file pointer find the file descriptor, and from the file descriptor find the file name. Events that must be logged:

</div>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<ol>
<li>File creation: Every time a user creates a file, the log file must be updated with information about the creation of the file. Make sure to modify the fopen() function in a way that the creation of a file can be distinguished from the opening of an existing file.</li>
<li>File opening: Every time a user tries to open a file, the log file must be updated with the corresponding file access attempt information. For this case, fopen() functions need to be intercepted and information about the user and the file access has to be collected.</li>
<li>File modification (write): Every time a user tries to modify a file, the log file will be updated with the corresponding file modification attempt information. This means that fwrite() functions</li>
</ol>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
need to be intercepted and information about the user and the file access has to be collected. Every fopen()/fwrite() function should create a new entry in a log file.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Step 2: Access Control Log Monitoring tool

</div>
</div>
<div class="layoutArea">
<div class="column">
Develop a log monitoring tool, named “acmonitor.c”, which will be responsible for monitoring the logs created by the Access Control Logging tool (Step 1). This log monitoring tool will:

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
<ol>
<li>Parse the log file generated in Step 1 and extract all incidents where malicious users1 tried to access multiple files without having permissions. As an output, the tool should print all users that tried to access more than 7 different files without having permissions i.e. print those users (uids) that tried to access at least 7 different files, without actually having the permissions.</li>
<li>Given a filename, the log monitoring tool should track and report all users that have accessed the specific file. By comparing the digital fingerprints/hash values, the log monitoring tool should check how many times the file was indeed modified. As an output, the log monitoring tool is expected to print a table with the number of times each user has modified it.</li>
</ol>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
note: the creation of a file produces a file fingerprint X1, and writing into this file produces another file fingerprint X2. As “a modification” we consider a transition from X1 to X2.

</div>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Step 3: Test the Access Control Logging &amp; Log Monitoring tools

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Develop a simple tool, named “test_aclog.c”, that will be used to test and demonstrate the above tasks. The “test_aclog.c” tool has to create/open/modify files, in a way that will create the conditions that the “acmonitor.c” tool searches for. For instance, you should try to open files without having the permission to do so (see Step 2.1), and modify specific files (see Step 2.2).

Executing the “test_aclog.c” tool with your custom fopen() and fwrite() functions preloaded, will create the required access control log file entries in “file_logging.log”. Then use the log monitoring tool to get the relevant reports (Step 2).

Tool Specification

The Access Control Log Monitoring tool (Step 2) will receive the required arguments from the command line upon execution.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Options

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Prints malicious users

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
-m

<pre> -i &lt;filename&gt;
</pre>
1 For this assignment, a “malicious user” is the user that tries to access multiple files without having the permission. For Step 2, when we refer to a “malicious user” we refer to the user that tries to access more than 7 different files without having the permission.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Prints table of users that modified the file given, and the number of modifications

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 4">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Help message

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
-h

<ol>
<li>If no appropriate option was given, the Access Control Monitoring tool has to print the appropriate error message.</li>
<li>You need to create a Makefile to compile your library and programs (you must submit it with your source code) or you can use the one provided to you.</li>
<li>You are also provided with a corpus to build your own source code.</li>
<li>You must submit the following files: README, Makefile, logger.c, logger.so,
<pre>   acmonitor.c, test_aclog.c
</pre>
</li>
<li>You need to submit all the source code of your tool, a “Makefile”, and a “README.txt” file that explains briefly your implementation and what you didn’t implement and why. Place all these files in a folder named &lt;yourlastnameAM&gt;_assign3, and then compress it as a .zip file that you will upload to eclass. For example: christodoulou2018123456_assign3.zip.</li>
<li>The README.txt file is important to submit.</li>
<li>Very important: execute the command gcc –-version and write whatever the output is into your
README.txt file, e.g. “gcc (Ubuntu 9.3.0-10ubuntu2~20.04)”
</li>
<li>The tool’s corpus provided with this assignment is just an example. Feel free to define your own
functions or change the signatures of the given functions (except for fopen() and fwrite()). You can even re-design it from scratch. However, the options defined in the “Tool specification” section must remain as-is.
</li>
<li>If you are having a problem with LD_PRELOAD of the library go to terminal and do “make run” (after make). Don’t do ./test_aclog.</li>
<li>In terminal, you might need to run LD_PRELOAD=./logger.so ./test_aclog.</li>
<li>Please use the given code as guide, and then make any changes you might need as long as you will deliver the requirement of assignment. For example: you can modify the way you manipulate the variables in the struct, e.g. date and time can be placed in the same
variable instead of separate.
</li>
<li>You can develop any new functions/include any new files you might want. This means
that the code doesn’t have to be developed entirely within your fopen or frwite.
</li>
<li>If a user attempts to open a file that does not exist, using for example mode “r”, fopen will fail. You have to keep log of every call in the fopen and fwrite you have developed (in fopen
the file path passes as an argument).
</li>
<li>Access type : fopen() should be “0” for file create, and “1” for file open.</li>
<li>File hash value changes: Every fwrite() creates a new entry in the log file. Whenever the
content and the size of the file are changed, the fingerprint is also changed.
</li>
</ol>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Notes

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
<ol start="16">
<li>File fingerprint : You should calculate it into your fopen() και fwrite(), after you have called the fopen() και fwrite() of the standard library.</li>
<li>In the logfile, you should have an entry for every calling of fopen and fwrite. In the case you cannot calculate the file fingerprint, then leave it “0”.</li>
<li>When the content of the file is the same, then the MD5 you get from MD() will be the same.</li>
<li>Prior to start creating your own fopen() και fwrite() get help from man page, e.g. for the
return values of fwrite().
</li>
<li>From the man page study the return values of fopen(). Your fopen() should be doing
exactly the same as the fopen() of standard library and creating an entry in the log file. All

modes should be supported e.g. r+ w+ a+.
</li>
<li>Issue with file fingerprint: some characters might get converted to newline and there is a
problem with reading the logfile via fscanf(). Possible solution: use function fread() after putting fseek() at the beginning of the file. If you write into the logfile using fprintf(), and read with fscanf(), try using %s instead of %02x.
</li>
<li>We will check your own test_aclog so you should submit it along with the necessary files, e.g. files your open/write.</li>
<li>How you will test your program is your own decision, but you will be graded based on the requirements of the assignment.</li>
<li>Submitted code will be tested using plagiarism-detection software.
Example
</li>
</ol>
You need to use LD_PRELOAD to instruct the linker to load your implementation of fopen/fwrite before any other library. Example below:

</div>
</div>
</div>
<div class="page" title="Page 6"></div>
