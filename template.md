Programming Language Name
Perl

-History of the language: who/when invented it, which languages influenced it, etc.

- Why was it invented

- When/why shall we use it
Perl is a very good programming language which is used to do multiple task. A typical simple use of Perl would be for extracting information from a text file and printing out a report or for converting a text file into another form. But Perl provides a large number of tools for quite complicated problems, including systems programming.PERL is a language that interfaces with the front end HTML language and the backend database such as MySQL. Perl as a language has great support for string parsing and regular expressions.Perl is a programming language which can be used for a large variety of tasks. A typical simple use of Perl would be for extracting information from a text file and printing out a report or for converting a text file into another form. But Perl provides a large number of tools for quite complicated problems, including systems programming.Perl is the most powerful language to use when it comes to intensive text processing and image recognition.It works on all operating systems, that is, a language can be moved.Generally, Perl is used to create CGI scripts and to create various applications for web pages.Perl gives us a very strong service in case of intensive text processing or editing of regex expressions.OOP (Object Oriented Programming) uses functions quite well.

- How to setup an environment to use it in different platforms
For Windows:
Close the command prompt or terminal session. Go to the https://www.perl.org/get.html and click on the Download ActivePerl link for your operating system. If you are on Windows, you may see a choice of ActivePerl and Strawberry Perl. If you're a beginner, choose ActivePerl. If you have experience with Perl, you may decide to go with Strawberry Perl. The versions are similar, so it's entirely up to you.
Follow the links to download the installer and then run it. Accept all the defaults and after a few minutes, Perl is installed. Check by opening up the command prompt/terminal session window and repeating the

perl -v

command.
You should see a message indicating you have installed Perl correctly and are ready to write your first script.

 For Unix/Linux
 Open a Web browser and go to https://www.perl.org/get.html

Follow the link to download zipped source code available for Unix/Linux.

Download perl-5.x.y.tar.gz file and issue the following commands at $ prompt.

$tar -xzf perl-5.x.y.tar.gz
$cd perl-5.x.y
$./Configure -de
$make
$make test
$make install
NOTE − Here $ is a Unix prompt where you type your command, so make sure you are not typing $ while typing the above mentioned commands.

This will install Perl in a standard location /usr/local/bin and its libraries are installed in /usr/local/lib/perlXX, where XX is the version of Perl that you are using.

It will take a while to compile the source code after issuing the make command. Once installation is done, you can issue perl -v command at $ prompt to check perl installation.

For macOs:
Go to the  link https://www.perl.org/get.html and click on Mac OS X tab. Download the source file (click on Download latest stable source) and run the following commands in the terminal.

First change the directory in terminal where in you have downloaded the zipped file. for e.g. if you have downloaded the file in Downloads directory then change the directory by typing this command:

cd ~/Downloads
Once use are in the directory where you have the zipped file, run the following commands:

tar -xzf perl-5.24.1.tar.gz
cd perl-5.24.1
./Configure -de
make
make test
make install

Remember to change the version in the above commands according to the version you have downloaded. If you use different version ,you should change 5.24.1.

- Example codes

- Things that are specific to this language?

