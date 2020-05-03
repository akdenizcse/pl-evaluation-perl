- Programming Language Name

Perl

- History of the language: who/when invented it, which languages influenced it, etc.

Perl was originally developed by Larry Wall in 1987 as a general-purpose Unix scripting language to make report processing easier.
Since then, it has undergone many changes and revisions.

Originally its creator, Larry Wall, had chosen to name it Pearl as he felt that it was a short and memorable word with positive associations. However, just before the language was due to be released he discovered that there was already an existing programming language named PEARL. At this point he changed the spelling and then released it as Perl.

Wall began his work on developing Perl prior to 1987, with the first version finally being released at the end of that year. For the next couple of years of development, the Perl language progressed at a rapid pace and Perl 2 was soon published in 1988, an improvement on the original. The following year Perl 3 was released.

- Perl 2 - an improvement of the perl 1
- Perl 3 - held support for binary streams
- Perl 5 - for system administration, network programming, finance, bioinformatics

The beginning stages of Perl 5 went on from mid-1993 into 1994 and, it was during this time that the Perl 5-porters mailing list became established. The point of this module was to create a better coordination system between Perl 5 and other platforms. To this day it is still one of the top areas for development and maintenance of Perl 5.

Over the years Perl 5 has seen significant improvements. 1995 and 1996 saw Perl 5 being released with new prototype features, which allowed any programmers of the modules to be able to make subroutines.
- 1996 saw Perl 5 released alongside a security release.
- The next release of Perl 5 occurred in 1997 and contained a UNIVERSAL package. This new package provided Perl with the base for which all classes were derived automatically, and offered programmers the ability to use different versions of the modules in the system. 
- Perl 5.0005 was made public in 1998 and once again contained a number of enhancements, this time to the regex engine, backends for other modules, additional core modules plus support for other operating systems such as BeOS.
- The year 2000 saw the release of Perl 5.6. This release contained some very significant changes that included such additions as 64-bit support, unicodes, support of files that were over 2Gb and the Perl keyword.
- With Perl 6 underway, 2001 saw Apocalypses coming into development, specifically to link in with Perl 6. 
- Just after this, Perl 5.8 was released, and since that 2002 release, Perl 5 has undergone yearly updates. Even by 2013, the Perl 5.8 version was still one of the most popular.

Influenced;
Perl, which has sometimes been said to stand for “practical extraction and report language,” was influenced by existing programming languages—such as C, BASIC, and AWK.


- Why was it invented?

Perl was originally developed to make report processing easier.
Before Perl, almost all text processing on Unix-like systems was done with a conglomeration of tools that included AWK. Larry wanted to fill the void between "manipulexity" (the ability of languages like C to "get into the innards of things") and "whipuptitude" (the property of programming languages like AWK that allows programmers to quickly write useful programs). Thus, Perl, the Practical Extraction and Report Language was born.


- When/why shall we use it?

Perl is a very good programming language which is used to do multiple task. A typical simple use of Perl would be for extracting information from a text file and printing out a report or for converting a text file into another form. But Perl provides a large number of tools for quite complicated problems, including systems programming.PERL is a language that interfaces with the front end HTML language and the backend database such as MySQL. Perl as a language has great support for string parsing and regular expressions.Perl is a programming language which can be used for a large variety of tasks. A typical simple use of Perl would be for extracting information from a text file and printing out a report or for converting a text file into another form. But Perl provides a large number of tools for quite complicated problems, including systems programming.Perl is the most powerful language to use when it comes to intensive text processing and image recognition.It works on all operating systems, that is, a language can be moved.Generally, Perl is used to create CGI scripts and to create various applications for web pages.Perl gives us a very strong service in case of intensive text processing or editing of regex expressions.OOP (Object Oriented Programming) uses functions quite well.

- How to setup an environment to use it in different platforms?

For Windows:
Close the command prompt or terminal session. Go to the https://www.perl.org/get.html and click on the Download ActivePerl link for your operating system. If you are on Windows, you may see a choice of ActivePerl and Strawberry Perl. If you're a beginner, choose ActivePerl. If you have experience with Perl, you may decide to go with Strawberry Perl. The versions are similar, so it's entirely up to you.
Follow the links to download the installer and then run it. Accept all the defaults and after a few minutes, Perl is installed. Check by opening up the command prompt/terminal session window and repeating the

perl -v

command.
You should see a message indicating you have installed Perl correctly and are ready to write your first script.

 For Unix/Linux:
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

-Factorial Code:

$number = 5; # Change the number here 

$fact = 1;

for( $i = 1; $i <= $number ; $i=$i+1 ){

    $fact = $fact*$i;
}

print "Factorial of $number is: $fact"


-Calculator Code:

 my $operation;
 
 my $int;
 
 my $int2;
 
 my $answer;
 
 my $runagain;
 
 calculator();
 
 sub calculator {
 
 print "What operation (Add, Sub, Mult, Divd) do you want to do? ";
 
 chomp($operation = <>);
 
 print "Enter the first number: ";chomp($int = <>);
 
 print "Enter the second number: ";chomp($int2 = <>);
 
 if ($operation =~ /^a/) {
 
 	$answer = $int + $int2;
  
  } elsif ($operation =~ /^s/) {
  
  $answer = $int - $int2;
  
 	} elsif ($operation =~ /^m/) {
  
  	$answer = $int * $int2;
   
  } elsif ($operation =~ /^d/) {
  
  	$answer = $int / $int2;
   
  	}
   
  print "The answer is $answer\n";
  
  print "Do you want to run this again? ";chomp($runagain = <>);
  
  if ($runagain =~ /^y/) {
  
 	calculator();
  
 	} else {
  
  print "goodbye\n";
  
 	}
 }
 
 
 - Renaming Files
 
if ($#ARGV != 3) {
    print "usage: rename old new start stop\n";
    exit;
}

$old = $ARGV[0];
$new = $ARGV[1];
$start = $ARGV[2];
$stop = $ARGV[3];

for ($i=$start; $i <= $stop; $i++) {

    $num = $i;
    if($i<10) {	$num = "00$i"; }
    elsif($i<100) { $num = "0$i"; }

    $cmd = "mv $old.$num $new.$num";
    print $cmd."\n";
    if(system($cmd)) { print "rename failed\n"; }
}

- Image Processing

if ($#ARGV != 4) {
 print "usage: compem bg.rgb inbase outbase startNum stopNum\n";
 exit;
}

$bg = $ARGV[0];
$inbase = $ARGV[1];
$outbase = $ARGV[2];
$start = $ARGV[3];
$stop = $ARGV[4];

for ($i=$start; $i <= $stop; $i++) {

    # pad numbers
    $num = $i;
    if($i<10) { $num = "00$i"; }
    elsif($i<100) { $num = "0$i"; }

    # call unix command "over"
    $cmd = "over $bg $inbase.$num $outbase.$num 0 0";
    print $cmd."\n";
    if(system($cmd)) { print "over failed\n"; }
}


- Things that are specific to this language?

    Perl gives you safety and security. With most languages that are interpreted, somebody can read your source code. With a language that’s typically compiled to a native binary, it’s possible take the binary and reverse engineer it to get something vaguely similar to source code, and (although it’s much more difficult than with the original source code) figure out what algorithms were used and how it works. Perl has no such weakness. Even starting from the original source code, there’s no danger of them figuring out how your code works (or realizing that the code really doesn’t work correctly at all).
   Perl’s grammar is almost unbelievably advanced. Perl is one of only a tiny number of languages that can’t be parsed statically. 
Perl simply cannot be parsed statically, so it’s clearly much more advanced!
     Perl has a long and glorious history of use in web server back ends. Nothing else can really match Perl when you need that ultra-modern nineties look for your web site!
       What is important is that Perl try to move in the right direction extending existing structures to add more power or flexibility or both. But all in all Perl is the most successful of the new breed of very high language and it generated a lot of following. Think about Python, PHP and Ruby as three prominent examples.  In this sense Perl is as influential as Algol-60 was many years ago.
    Perhaps the main difference between perl and other languages is the flexibility of perl's syntax.Because of the richness of the language, you are encouraged to develop your own style. Much of  flexibility is achieved through perl's non-standard language design. For example, every variable in perl must be preceded by a symbol informing perl as to what kind of object is being stored in that variable. This allows perl to recognize names without the prepended symbol (``barewords'' in perl lingo) as being function calls or character strings. 
   Another area where perl differs from other languages is the way that it reads data from a file or the keyboard. Perl uses angle brackets (< and >) as an ``operator'' to read a line from an already-opened file. Thus, to read a single line typed from the keyboard (known as ``standard input'' in the UNIX world).
   Perl can recognize length and print as functions, even without parentheses.The secret lies in the magic behind the angle bracket while loop. When this construct is used, a special variable called $_ is created to hold the contents of the currently read line. In perl, when a function is called without any arguments, this special variable is passed to the function.
