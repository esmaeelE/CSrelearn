    A Self-Learning, Modern Computer Science Curriculum   <!--/\*--><!\[CDATA\[/\*><!--\*/ .title { text-align: center; margin-bottom: .2em; } .subtitle { text-align: center; font-size: medium; font-weight: bold; margin-top:0; } .todo { font-family: monospace; color: red; } .done { font-family: monospace; color: green; } .priority { font-family: monospace; color: orange; } .tag { background-color: #eee; font-family: monospace; padding: 2px; font-size: 80%; font-weight: normal; } .timestamp { color: #bebebe; } .timestamp-kwd { color: #5f9ea0; } .org-right { margin-left: auto; margin-right: 0px; text-align: right; } .org-left { margin-left: 0px; margin-right: auto; text-align: left; } .org-center { margin-left: auto; margin-right: auto; text-align: center; } .underline { text-decoration: underline; } #postamble p, #preamble p { font-size: 90%; margin: .2em; } p.verse { margin-left: 3%; } body { max-width: 40rem; padding: 1rem; margin: auto; } pre { border: 1px solid #ccc; box-shadow: 3px 3px 3px #eee; padding: 8pt; font-family: monospace; overflow: auto; margin: 1.2em; } pre.src { position: relative; overflow: auto; padding-top: 1.2em; } pre.src:before { display: none; position: absolute; background-color: white; top: -10px; right: 10px; padding: 3px; border: 1px solid black; } pre.src:hover:before { display: inline; margin-top: 14px;} /\* Languages per Org manual \*/ pre.src-asymptote:before { content: 'Asymptote'; } pre.src-awk:before { content: 'Awk'; } pre.src-C:before { content: 'C'; } /\* pre.src-C++ doesn't work in CSS \*/ pre.src-clojure:before { content: 'Clojure'; } pre.src-css:before { content: 'CSS'; } pre.src-D:before { content: 'D'; } pre.src-ditaa:before { content: 'ditaa'; } pre.src-dot:before { content: 'Graphviz'; } pre.src-calc:before { content: 'Emacs Calc'; } pre.src-emacs-lisp:before { content: 'Emacs Lisp'; } pre.src-fortran:before { content: 'Fortran'; } pre.src-gnuplot:before { content: 'gnuplot'; } pre.src-haskell:before { content: 'Haskell'; } pre.src-hledger:before { content: 'hledger'; } pre.src-java:before { content: 'Java'; } pre.src-js:before { content: 'Javascript'; } pre.src-latex:before { content: 'LaTeX'; } pre.src-ledger:before { content: 'Ledger'; } pre.src-lisp:before { content: 'Lisp'; } pre.src-lilypond:before { content: 'Lilypond'; } pre.src-lua:before { content: 'Lua'; } pre.src-matlab:before { content: 'MATLAB'; } pre.src-mscgen:before { content: 'Mscgen'; } pre.src-ocaml:before { content: 'Objective Caml'; } pre.src-octave:before { content: 'Octave'; } pre.src-org:before { content: 'Org mode'; } pre.src-oz:before { content: 'OZ'; } pre.src-plantuml:before { content: 'Plantuml'; } pre.src-processing:before { content: 'Processing.js'; } pre.src-python:before { content: 'Python'; } pre.src-R:before { content: 'R'; } pre.src-ruby:before { content: 'Ruby'; } pre.src-sass:before { content: 'Sass'; } pre.src-scheme:before { content: 'Scheme'; } pre.src-screen:before { content: 'Gnu Screen'; } pre.src-sed:before { content: 'Sed'; } pre.src-sh:before { content: 'shell'; } pre.src-sql:before { content: 'SQL'; } pre.src-sqlite:before { content: 'SQLite'; } /\* additional languages in org.el's org-babel-load-languages alist \*/ pre.src-forth:before { content: 'Forth'; } pre.src-io:before { content: 'IO'; } pre.src-J:before { content: 'J'; } pre.src-makefile:before { content: 'Makefile'; } pre.src-maxima:before { content: 'Maxima'; } pre.src-perl:before { content: 'Perl'; } pre.src-picolisp:before { content: 'Pico Lisp'; } pre.src-scala:before { content: 'Scala'; } pre.src-shell:before { content: 'Shell Script'; } pre.src-ebnf2ps:before { content: 'ebfn2ps'; } /\* additional language identifiers per "defun org-babel-execute" in ob-\*.el \*/ pre.src-cpp:before { content: 'C++'; } pre.src-abc:before { content: 'ABC'; } pre.src-coq:before { content: 'Coq'; } pre.src-groovy:before { content: 'Groovy'; } /\* additional language identifiers from org-babel-shell-names in ob-shell.el: ob-shell is the only babel language using a lambda to put the execution function name together. \*/ pre.src-bash:before { content: 'bash'; } pre.src-csh:before { content: 'csh'; } pre.src-ash:before { content: 'ash'; } pre.src-dash:before { content: 'dash'; } pre.src-ksh:before { content: 'ksh'; } pre.src-mksh:before { content: 'mksh'; } pre.src-posh:before { content: 'posh'; } /\* Additional Emacs modes also supported by the LaTeX listings package \*/ pre.src-ada:before { content: 'Ada'; } pre.src-asm:before { content: 'Assembler'; } pre.src-caml:before { content: 'Caml'; } pre.src-delphi:before { content: 'Delphi'; } pre.src-html:before { content: 'HTML'; } pre.src-idl:before { content: 'IDL'; } pre.src-mercury:before { content: 'Mercury'; } pre.src-metapost:before { content: 'MetaPost'; } pre.src-modula-2:before { content: 'Modula-2'; } pre.src-pascal:before { content: 'Pascal'; } pre.src-ps:before { content: 'PostScript'; } pre.src-prolog:before { content: 'Prolog'; } pre.src-simula:before { content: 'Simula'; } pre.src-tcl:before { content: 'tcl'; } pre.src-tex:before { content: 'TeX'; } pre.src-plain-tex:before { content: 'Plain TeX'; } pre.src-verilog:before { content: 'Verilog'; } pre.src-vhdl:before { content: 'VHDL'; } pre.src-xml:before { content: 'XML'; } pre.src-nxml:before { content: 'XML'; } /\* add a generic configuration mode; LaTeX export needs an additional (add-to-list 'org-latex-listings-langs '(conf " ")) in .emacs \*/ pre.src-conf:before { content: 'Configuration File'; } table { border-collapse:collapse; } caption.t-above { caption-side: top; } caption.t-bottom { caption-side: bottom; } td, th { vertical-align:top; } th.org-right { text-align: center; } th.org-left { text-align: center; } th.org-center { text-align: center; } td.org-right { text-align: right; } td.org-left { text-align: left; } td.org-center { text-align: center; } dt { font-weight: bold; } .footpara { display: inline; } .footdef { margin-bottom: 1em; } .figure { padding: 1em; } .figure p { text-align: center; } .equation-container { display: table; text-align: center; width: 100%; } .equation { vertical-align: middle; } .equation-label { display: table-cell; text-align: right; vertical-align: middle; } .inlinetask { padding: 10px; border: 2px solid gray; margin: 10px; background: #ffffcc; } #org-div-home-and-up { text-align: right; font-size: 70%; white-space: nowrap; } textarea { overflow-x: auto; } .linenr { font-size: smaller } .code-highlighted { background-color: #ffff00; } .org-info-js\_info-navigation { border-style: none; } #org-info-js\_console-label { font-size: 10px; font-weight: bold; white-space: nowrap; } .org-info-js\_search-highlight { background-color: #ffff00; color: #000000; font-weight: bold; } .org-svg { width: 90%; } /\*\]\]>\*/--> // @license magnet:?xt=urn:btih:e95b018ef3580986a04669f1b5879592219e2a7a&dn=public-domain.txt Public Domain <!--/\*--><!\[CDATA\[/\*><!--\*/ function CodeHighlightOn(elem, id) { var target = document.getElementById(id); if(null != target) { elem.classList.add("code-highlighted"); target.classList.add("code-highlighted"); } } function CodeHighlightOff(elem, id) { var target = document.getElementById(id); if(null != target) { elem.classList.remove("code-highlighted"); target.classList.remove("code-highlighted"); } } /\*\]\]>\*///--> // @license-end

A Self-Learning, Modern Computer Science Curriculum
===================================================

Table of Contents
-----------------

*   [1\. Introduction](#Introduction)
    *   [1.1. Studying Strategies](#Studying%20Strategies)
    *   [1.2. Discord channel](#Discord%20channel)
*   [2\. Preliminaries](#Preliminaries)
    *   [2.1. Introduction to Computer Science](#Introduction%20to%20Computer%20Science)
    *   [2.2. Tools](#Tools)
    *   [2.3. Assumed Mathematical Background](#Assumed%20Mathematical%20Background)
*   [3\. Functional Programming](#Functional%20Programming)
    *   [3.1. Principles of Functional Programming](#Principles%20of%20Functional%20Programming)
    *   [3.2. CS 3110 Data Structures and Functional Programming](#CS%203110%20Data%20Structures%20and%20Functional%20Programming)
*   [4\. Algebra](#Algebra)
    *   [4.1. Linear Algebra](#Linear%20Algebra)
    *   [4.2. Abstract Algebra](#Abstract%20Algebra)
*   [5\. Discrete Mathematics](#Discrete%20Mathematics)
    *   [5.1. Math Workshop](#Math%20Workshop)
    *   [5.2. Discrete Math with Standard ML](#Discrete%20Math%20with%20Standard%20ML)
    *   [5.3. Great Theoretical Ideas in Computer Science](#Great%20Theoretical%20Ideas%20in%20Computer%20Science)
*   [6\. Computer Systems & Architecture](#Computer%20Systems%20%26%20Architecture)
    *   [6.1. x86 Computer Systems](#x86%20Computer%20Systems)
    *   [6.2. RISC-V Architecture](#RISC-V%20Architecture)
    *   [6.3. Operating Systems](#Operating%20Systems)
*   [7\. Compilers](#Compilers)
*   [8\. Database Systems](#Database%20Systems)
    *   [8.1. Advanced Database Systems](#Advanced%20Database%20Systems)
*   [9\. Web](#Web)
*   [10\. Data Science](#Data%20Science)
    *   [10.1. Practical Data Science](#Practical%20Data%20Science)
    *   [10.2. Introduction to Computational Thinking](#Introduction%20to%20Computational%20Thinking)
    *   [10.3. Advanced Data Science](#Advanced%20Data%20Science)
*   [11\. Symbolic Programming](#Symbolic%20Programming)
*   [12\. Natural Language Processing](#Natural%20Language%20Processing)
*   [13\. Programming Language Theory](#Programming%20Language%20Theory)
*   [14\. Isolating Software Failure, Proving Safety and Testing](#Isolating%20Software%20Failure%2C%20Proving%20Safety%20and%20Testing)
    *   [14.1. Physical Systems Software Security](#Physical%20Systems%20Software%20Security)
*   [15\. Workshop in Algorithms](#Workshop%20in%20Algorithms)
    *   [15.1. Introduction to Parallel and Sequential Algorithms](#Introduction%20to%20Parallel%20and%20Sequential%20Algorithms)
    *   [15.2. Functional Data Structures](#Functional%20Data%20Structures)
    *   [15.3. Advanced Data Structures](#Advanced%20Data%20Structures)
*   [16\. Complexity Theory](#Complexity%20Theory)
    *   [16.1. Undergraduate Complexity Theory](#Undergraduate%20Complexity%20Theory)
    *   [16.2. Graduate Complexity Theory](#Graduate%20Complexity%20Theory)
    *   [16.3. Useful Math for Theoretical CS](#Useful%20Math%20for%20Theoretical%20CS)
*   [17\. Introduction to Quantum Computing](#Introduction%20to%20Quantum%20Computing)
*   [18\. Performance Engineering](#Performance%20Engineering)
*   [19\. Topics in Mathematics for Finance](#Topics%20in%20Mathematics%20for%20Finance)
*   [20\. Jobs](#Jobs)
*   [21\. Workshop in Computational Type Theory](#Workshop%20in%20Computational%20Type%20Theory)
*   [22\. Workshop in Machine Learning/AI](#Workshop%20in%20Machine%20Learning%2FAI)
    *   [22.1. General AI](#General%20AI)
    *   [22.2. Math Background for ML](#Math%20Background%20for%20ML)
    *   [22.3. Statistics Theory](#Statistics%20Theory)
    *   [22.4. Modern Regression](#Modern%20Regression)
    *   [22.5. Introduction to Machine Learning](#Introduction%20to%20Machine%20Learning)
    *   [22.6. Introduction to Practical Machine Learning](#Introduction%20to%20Practical%20Machine%20Learning)
    *   [22.7. Graduate Introduction to ML](#Graduate%20Introduction%20to%20ML)
    *   [22.8. Advanced Statistical learning theory](#Advanced%20Statistical%20learning%20theory)
    *   [22.9. Convex Optimization](#Convex%20Optimization)
    *   [22.10. Deep Learning](#Deep%20Learning)
    *   [22.11. Further Research](#Further%20Research)
*   [23\. Workshop in Cryptography](#Workshop%20in%20Cryptography)

1 Introduction
--------------

> "The great idea of constructive type theory is that there is no distinction between programs and proofs… Theorems are types (specifications), and proofs are programs" (Robert Harper)

This is a collection of modern resources on various undergrad level computer science topics, for someone with an interest in theory. Use [WorldCat](https://www.worldcat.org/) or [LibGen](https://en.wikipedia.org/wiki/Library_Genesis) if you can't buy these books. You don't have to do everything here, just whatever interests you. If I list a resource here it's because I either completed the whole resource or I used parts of it for something I needed to learn and found it a quality enough resource to include here for somebody else who wants deeper coverage of these topics.

### 1.1 Studying Strategies

On Isaac Newton's iteration method to self-learn geometry:

> "He bought Descartes' Geometry and read it by himself .. when he was got over 2 or 3 pages he could understand no farther, than he began again and got 3 or 4 pages father till he came to another difficult place, than he began again and advanced farther and continued so doing till he made himself master of the whole without having the least light or instruction from anybody" (King's Cam.,Keynes MS 130.10,fol. 2/v/)

Numerous anecdotes exist on studying strategies, like the Feynman method explained [here](http://calnewport.com/blog/2012/10/26/mastering-linear-algebra-in-10-days-astounding-experiments-in-ultra-learning/) "If you can’t, out loud or on paper, explain the idea without confusion or contradiction, stop and figure it out right there". There's some books that model that method, like Gilbert Strang's _Calculus_ has you reciting back the entire chapter you just read.

If you ignore the copious amounts of marketing on his site, Cal Newport has some other interesting anecdotes on studying, such as how he was able to get the [best](http://calnewport.com/blog/2008/11/25/case-study-how-i-got-the-highest-grade-in-my-discrete-math-class/) grade in his Discrete Mathematics class, and the rest of the site is full of advice on studying, how to schedule yourself and [deliberate](https://azeria-labs.com/the-importance-of-deep-work-the-30-hour-method-for-learning-a-new-skill/) [practice](http://calnewport.com/blog/2010/01/06/the-grandmaster-in-the-corner-office-what-the-study-of-chess-experts-teaches-us-about-building-a-remarkable-life/).

My personal advice is just commit some time everyday to learning, and life will give you days off as things come up, you don't really need a schedule just do something daily and magically by the end of the year you will have achieved a huge amount of work. Always get the errata for what you're reading, even course notes sometimes have errata on the author's page, and always take something a little harder than your skill level so then it becomes a research exercise backfilling all the requirements. For example many people want to relearn math they forgot, so they start working through some enormous 1000+ page pre-calculus book and lose interest after the first few chapters. Instead make the goal to learn calculus, and start there, using the huge pre-calc book as your research project. This is what the exercises are for you pick up all the algebra from highschool you forgot while grinding through a calc book.

### 1.2 Discord channel

If you want to learn this material with a community, some anons have started a Discord [channel](https://discord.gg/V34pTzY).

2 Preliminaries
---------------

### 2.1 Introduction to Computer Science

I've rewritten this entire section into a [workshop](https://learnaifromscratch.github.io/) we work through Brown University's [CS019 class](https://www.youtube.com/playlist?list=PLl0tHXI7SBjncgRrhL4DPEwDgUjUtk2_C) and Tao's _Analysis I_, plus many other topics to fill in beginner blanks. They're draft quality notes but the idea is if you get stuck on something, you can look at them like asking a TA for help.

*   [(Full Course) CS019 Accelerated Intro to CS](https://cs.brown.edu/courses/cs019/)
    *   Lectures [here](https://www.youtube.com/playlist?list=PLl0tHXI7SBjncgRrhL4DPEwDgUjUtk2_C)
    *   Use the lastest version of [PAPL](https://papl.cs.brown.edu/2020/)
    *   You can complete this course on a phone/tablet if needed, you use a simple [online](https://code.pyret.org/) IDE for the assignments

Torrent archive

2018 Lectures, labs, recorded recitations
magnet:?xt=urn:btih:891283aff7f336ba6c56ed47e03a2f72a9b186d0&dn=cs019

### 2.2 Tools

MIT's the missing semester of your [CS education](https://missing.csail.mit.edu/). Editors such as emacs/vim are also introduced [here](https://www.cs.cmu.edu/~15131/f17/) but any IDE will do you prefer like [Atom](https://atom.io/) or online ones like [replit](https://replit.com/). The 1980s book [The Unix Programming Environment](https://en.wikipedia.org/wiki/The_Unix_Programming_Environment) by Kernighan & Pike walks through Awk/Grep/Sed and shell scripting too.

### 2.3 Assumed Mathematical Background

> "So I went to Case, and the Dean of Case says to us, it's a all men's school, "Men, look at, look to the person on your left, and the person on your right. One of you isn't going to be here next year; one of you is going to fail." So I get to Case, and again I'm studying all the time, working really hard on my classes, and so for that I had to be kind of a machine. In high school, our math program wasn't much, and I had never heard of calculus until I got to college. But the calculus book that we had was (in college) was great, and in the back of the book there were supplementary problems that weren't assigned by the teacher. So this was a famous calculus text by a man named George Thomas ([second edition](https://www.amazon.com/gp/customer-reviews/R1HJTYVOE94R83/ref=cm_cr_dp_d_rvw_ttl?ie=UTF8&ASIN=0201077795)), and I mention it especially because it was one of the first books published by Addison-Wesley, and I loved this calculus book so much that later I chose Addison-Wesley to be the publisher of my own book. Our teacher would assign, say, the even numbered problems, or something like that (from the book). I would also do the odd numbered problems. In the back of Thomas's book he had supplementary problems, the teacher didn't assign the supplementary problems; I worked the supplementary problems. I was scared I wouldn't learn calculus, so I worked hard on it, and it turned out that of course it took me longer to solve all these problems than the kids who were only working on what was assigned, at first. But after a year, I could do all of those problems in the same time as my classmates were doing the assigned problems, and after that _I could just coast in mathematics, because I'd learned how to solve problems_" ([Don Knuth](https://github.com/kragen/knuth-interview-2006) )

Try the new [math from scratch](https://learnaifromscratch.github.io/math.html) experimental curriculum we'll try and teach ourselves the math needed to try most of the courses here. There's also [calculus](https://learnaifromscratch.github.io/calculus.html) and [linear algebra](https://learnaifromscratch.github.io/linear.html).

3 Functional Programming
------------------------

### 3.1 Principles of Functional Programming

Robert Harper keeps a [blog](https://existentialtype.wordpress.com/2012/08/17/intro-curriculum-update/%20) and a follow up [post](https://existentialtype.wordpress.com/2011/03/21/the-dog-that-didnt-bark/) on the success of teaching this material to undergrads. Since the CMU 15-150 course is locked down now we can instead do [Dan Licata's](https://dlicata.wescreates.wesleyan.edu/) version at Wesleyan (PhD advised by Robert Harper) that has short recorded lectures and assignments open to the public, it's very similar to the original 15-150 curriculum.

*   [(Full Course) COMP 212 - Functional Programming](https://dlicata.wescreates.wesleyan.edu/teaching/fp-s21/lect.html)
    *   This course differs from CS19 in that you write proofs of specs, focus on parallelism

The labs and hw are locked for COMP212 now, but you can get the sp20 hw and labs from this torrent
 - de-select the video lectures if you want a smaller download
 
magnet:?xt=urn:btih:4802b90e2b2c0f419690b0a09ee8e2128a92d32f&dn=fp-s20

### 3.2 CS 3110 Data Structures and Functional Programming

Cornell's version uses OCaml, their [book](https://cs3110.github.io/textbook/cover.html) now has embedded YouTube [videos](https://www.youtube.com/playlist?list=PLre5AT9JnKShBOPeuiD9b-I4XROIJhkIU) and you can download a VM image to run OCaml as they have set it up in the course. Some overlap with CS19 in the exercises if you already did CS19, COMP212 focuses more on parallelism and the exercises much more difficult, try both courses they compliment each other.

4 Algebra
---------

It is possible in a functional language like ML to do algebra with types, proving two types are isomorphic with the desired properties of reflexivity, symmetry, and transitivity. It's also possible to abstract Lists and Trees into polynomials, as every polynomial looks like a sum of terms. As you will learn in 15-150 _Principles of Functional Programming_ "most functional datastructures have constant time access near the outer layer of their structure, ie: the head of a list or the root of a tree. However, access at some random point inside the structure is typically linear since looking at some element of a list is linear in the length of the list, and looking at some element of a tree is linear in the depth of the tree. Datatype derivatives allow constant time access to the entire structure."

### 4.1 Linear Algebra

I now have my own [Modern Applied Linear Algebra](https://learnaifromscratch.github.io/linear.html) workshop if you want to do MIT's latest 18.06, Terence Tao's notes and some Wildberger lectures.

*   [(Full Course) CS053 - Coding the Matrix](http://cs.brown.edu/courses/cs053/current/lectures.htm)
    *   A lot of linear algebra over the complex field
    *   No formal prerequisites except assumes you know how to do basic proofs, book uses python bu you can do this course in any language, they all have linear algebra libraries
        *   A [crash course](https://www.youtube.com/playlist?list=PLC7GP7QTnIJ8w2qcrHK1nIy7mWQnYSOmr) in linear algebra if you've taken some before

### 4.2 Abstract Algebra

See the [crypto](https://functionalcs.github.io/curriculum/crypto.html) workshop, abstract algebra will done there.

5 Discrete Mathematics
----------------------

### 5.1 Math Workshop

Poh-Shen Loh has lectures on his YouTube channel for CMU's 21-228 Discrete Math class. We do it [here](https://learnaifromscratch.github.io/math.html#Math%20circle).

### 5.2 Discrete Math with Standard ML

If you don't know how to program this book will teach you by modeling math functions in SML, polynomials into lists, sets into types, creating relations and proving their results with programs.

*   [(Book/Lectures) Discrete Mathematics and Functional Programming - Thomas VanDrunen](https://cs.wheaton.edu/~tvandrun/dmfp/)
    *   Lectures exist on the author's homepage, this book is used for a one semester university course with additional elective chapters in Graph Theory, Complexity Theory, Automata, etc.

### 5.3 Great Theoretical Ideas in Computer Science

This is a crash course in multiple topics such as Probability, Linear Algebra, Modular Arithmetic, Polynomials, Cryptography and Complexity Theory.

*   YouTube [lectures](https://www.youtube.com/playlist?list=PLm3J0oaFux3aafQm568blS9blxtA_EWQv) (missing some) and [course notes](https://www.anilada.com/) with solutions on Anil Ada's page. Panopto still has the 2013 course [here](https://scs.hosted.panopto.com/Panopto/Pages/Sessions/List.aspx#folderID=%22e0adbd1d-f211-49da-9231-871360c2a1f6%22&maxResults=50) taught by a younger Ryan O'donnell and the missing lectures not in the youtube playlist.

6 Computer Systems & Architecture
---------------------------------

> "\[Computer science\] is not really about computers - and it's not about computers in the same sense that physics is not really about particle accelerators, and biology is not about microscopes and Petri dishes…and geometry isn't really about using surveying instruments. Now the reason that we think computer science is about computers is pretty much the same reason that the Egyptians thought geometry was about surveying instruments: when some field is just getting started and you don't really understand it very well, it's very easy to confuse the essence of what you're doing with the tools that you use." (Hal Abelson)

### 6.1 x86 Computer Systems

This covers architecture from a programmer's perspective, such as how to write cache friendly code/optimizations, assembly, how compilers work, return oriented programming (ROP) to bypass stack protections, the memory hierarchy, and networks. You could read K&R's _The C Programming Language_ for a brief intro, though this course will explain C as you go anyway and fully covers pointers at the assembly language level making it self contained.

*   [(Full Course) 15-213 Intro to Computer Systems (CMU)](https://www.cs.cmu.edu/~213/schedule.html)
    *   Recorded lectures [here](https://scs.hosted.panopto.com/Panopto/Pages/Sessions/List.aspx#folderID=%22b96d90ae-9871-4fae-91e2-b1627b43e25e%22&maxResults=50) or download them [here](http://scs.hosted.panopto.com/Panopto/Podcast/Podcast.ashx?courseid=b96d90ae-9871-4fae-91e2-b1627b43e25e&type=mp4)
        *   YouTube has lectures uploaded for this course too for multiple semesters
    *   Uses CS:APP book, 3rd version for x86-64 beware of the global version [errata](http://csapp.cs.cmu.edu/3e/errata.html)
    *   If you want a well written crash course in C read these [notes](https://cs.uwaterloo.ca/~plragde/flaneries/IYMLC/) )
    *   The labs (Data Lab, Bomb Lab ect) are on the [book website](http://csapp.cs.cmu.edu/3e/students.html)
        *   Try the embedded security CTF [here](https://microcorruption.com/login) after you finish the Attack Lab

I do some of this course [here](https://learnaifromscratch.github.io/theabsolutestateofsoftware.html)

### 6.2 RISC-V Architecture

MIT's 6.004 course covers RISC-V: The free and open RISC Instruction Set Architecture. Take this if you are interested in programming FPGAs or [cheap](https://www.seeedstudio.com/sipeed) embedded modules.

*   [(Full Course) 6.004 Computation Structures](https://6004.mit.edu/web/spring19/resources/lectures)
    *   Recorded YouTube lectures [here](https://www.youtube.com/channel/UC1DcxXg6GkAcp2zk2w7U6qQ/videos)
    *   Book used is Computer Organization and Design: [RISC-V Edition](https://www.elsevier.com/books/computer-organization-and-design-risc-v-edition/patterson/978-0-12-812275-4)

### 6.3 Operating Systems

MIT teaches OS engineering using a rewrite of the sixth edition Unix(v6) similar to the classic [Lions' Commentary](https://en.wikipedia.org/wiki/Lions%27_Commentary_on_UNIX_6th_Edition,_with_Source_Code) but in ANSI-C called xv6. The idea is you read the source as you read book, to understand the system. MIT has a full course w/YouTube lectures [here](https://pdos.csail.mit.edu/6.828/2020/schedule.html) or find most recent semester.

The latest xv6 source and text are available via:

*   git clone git://github.com/mit-pdos/xv6-riscv.git
*   git clone git://github.com/mit-pdos/xv6-riscv-book.git
    *   If you have problems building the book, get the [pdf](https://pdos.csail.mit.edu/6.828/2020/xv6/book-riscv-rev1.pdf)

7 Compilers
-----------

The course has a recorded screencast

*   [(Full Course) CSE 131: Compilers](https://cseweb.ucsd.edu/classes/sp17/cse131-a/index.html)
    *   Recorded lectures/podcast [here](https://podcast.ucsd.edu/podcasts/default.aspx?PodcastId=4014) uses OCaml
    *   There exists a tutorial by Abdulaziz Ghuloum in [Scheme](https://cseweb.ucsd.edu/classes/sp17/cse131-a/s_materials.html)
    *   See also the MIT course [18](#Performance%20Engineering)

8 Database Systems
------------------

Interesting [post](http://www.cs.cmu.edu/~./pavlo/blog/2015/09/the-next-50-years-of-databases.html) on the future of database systems by Andy Pavlo.

*   [(Full Course) 15-445 Intro to Database Systems](https://15445.courses.cs.cmu.edu/fall2019/schedule.html)
    *   Recorded lectures on [YouTube](https://www.youtube.com/watch?v=oeYBdghaIjc&list=PLSE8ODhjZXjbohkNBWQs_otTrBTrjyohi&index=1), course changes every year take the most recent version
    *   Uses readings from this [book](http://db-book.com/), assumes you have taken [15-213](#x86%20Computer%20Systems) and know some basic set theory

### 8.1 Advanced Database Systems

At the end of the semester the grading scripts are publically available.

*   [(Full Course) 15-721 Advanced Database Systems](https://15721.courses.cs.cmu.edu/spring2019/)
    *   Recorded lectures on [YouTube](https://www.youtube.com/playlist?list=PLSE8ODhjZXja7K1hjZ01UTVDnGQdx5v5U) (find the most recent ones)
    *   Everything is in C++17 which you can teach yourself from the bounty of books/documentation available via search engine.
    *   Purpose of this course is to learn how to design and build your own dbms

9 Web
-----

Here are the (poor) [notes](https://functionalcs.github.io/web/) I took for MIT's 6.148 Web Programming Competition and MIT's 6.170 Software Studio. I did most of these assignments on a phone using [Eruda](https://eruda.liriliri.io/) since I wrote this while on lunch breaks. The MIT workshop and 6.170 are actually pretty good, giving you just enough to make a MVP yourself, expecting you to fill in the rest of the details on your own now that you know the basics of express, react, CSS etc.

*   An [advanced](http://people.csail.mit.edu/dnj/teaching/6170/js-live-2020/) introduction to JavaScript

10 Data Science
---------------

### 10.1 Practical Data Science

Uses Python, teaches a crash course in linear algebra and probability

*   [(Full Course) 15-388 Practical Data Science](http://www.datasciencecourse.org/lectures/)
    *   Recorded lectures are [here](https://scs.hosted.panopto.com/Panopto/Pages/Sessions/List.aspx#folderID=%22912b80a3-625d-405d-8905-a8620133666b%22&maxResults=50) and archived [here](https://www.bilibili.com/video/av21738618/)
    *   Introduction to the 'full stack' of data science analysis: data collection and processing, data visualization and presentation, statistical model building using machine learning, and big data techniques for scaling these methods.
    *   Cornell also has a free [text](http://www.cs.cornell.edu/courses/cs1380/2018sp/textbook/) with interactive jupyter notebooks (in Python)

### 10.2 Introduction to Computational Thinking

MIT course featuring the 3blue1brown linear algebra guy as a lecturer.

*   [(Full Course) MIT 18.S191 Intro to Computational thinking sp2021](https://computationalthinking.mit.edu/Spring21/)
    *   Image transformations, learning, how a differential model works

### 10.3 Advanced Data Science

Cozma Shalizi is an ex Physicist, so he approaches statistics from that viewpoint which is refreshing. He is a research statistician so this won't be a recipe book.

*   [(Book) Advanced Data Science from an Elementary Point of View](http://www.stat.cmu.edu/~cshalizi/ADAfaEPoV/)
    *   Some overlap with his other book _The Truth About Linear Regression_
        *   Don't have the prereqs? See his [notebooks](http://bactra.org/notebooks/) like how to [teach statistics](http://bactra.org/notebooks/teaching-statistics.html)

11 Symbolic Programming
-----------------------

Try Sussman's new [book](https://mitpress.mit.edu/books/software-design-flexibility) _Software Design for Flexibility_ you only need the appendix on Scheme to start, most of this is self-contained, assumes you know the equivalent of his other book _Structure and Interpretation of Computer Programs_ or a CS19 style [intro course](https://learnaifromscratch.github.io/software.html).

12 Natural Language Processing
------------------------------

*   [(Full Course) 11-411 Natural Language Processing](http://demo.clab.cs.cmu.edu/NLP/)
    *   Recorded lectures on [YouTube](https://www.youtube.com/channel/UCiSfpwbPJTHo1CMiWaXlAMQ/videos) find the most recent ones
        *   Some [notes](http://demo.clab.cs.cmu.edu/11711fa18/) on NLP algorithms

13 Programming Language Theory
------------------------------

I go through Robert Harper's PFPL book [here](https://functionalcs.github.io/curriculum/typetheory.html) there's also an [Agda workshop](https://cs.uwaterloo.ca/~plragde/747/notes/index.html) with screencasts as a replacement for Pierce's _Types and Programming Languages_.

14 Isolating Software Failure, Proving Safety and Testing
---------------------------------------------------------

How to verify software, and strategies of programming that minimize catastrophe during failure. I do some of this [here](https://learnaifromscratch.github.io/theabsolutestateofsoftware.html).

*   [(Lecture Notes) 15-316 Software Foundations of Security and Privacy](https://15316-cmu.github.io/index.html)
    *   Covers side channel attacks, provable privacy, web security, proving the validity of a memory sandbox
    *   Read about tests, strategies to safe program design (in OCaml), and proving safety from the 2017 version: git clone [https://github.com/jeanqasaur/cmu-15316-spring17.git](https://github.com/jeanqasaur/cmu-15316-spring17.git)
    *   MIT's 6.858 _Computer Systems Security_ is fully open with [lectures](https://css.csail.mit.edu/6.858/2020/)

Brown's [CS195y](http://cs.brown.edu/courses/cs195y/2020/) _Logic For Systems_ I made a torrent for if you want to model state in a way similar to [Alloy](https://mitpress.mit.edu/books/software-abstractions-revised-edition), where you can prove it's logic before writing the program. Think about designing a security level scheme where different users have different access levels, you don't want some unforseen combination of states to result in granting access that shouldn't be granted. The _Software Abstractions_ book and 195y course help you with this by providing a way to model your security scheme before you write the code using something similar to set theory proofs.

CS195y partial archive, some recorded lectures missing:
magnet:?xt=urn:btih:3187a9951b43b85771a975653680a4a8d9faf61d&dn=195y

### 14.1 Physical Systems Software Security

*   [(Full Course) 15-424 Foundations of Cyber-Physical Systems](http://symbolaris.com/course/fcps16.html)
    *   Course (with recorded lectures) if you're interested in programming drones/space shuttles/robots/cars and other things that cannot fail from avoidable errors. Find the latest version.
    *   Mainly self contained, you may have to look up some lectures on differential equations, try Strang's 18.085 MIT lectures for _Computational Engineering_ on OCW.

15 Workshop in Algorithms
-------------------------

If you want to learn beginner to advanced algorithms try [here](https://learnaifromscratch.github.io/algorithms.html) where we practice mixing competitive programming with standard algorithms texts.

Here's a partial archive of [15-451](https://www.cs.cmu.edu/~15451-s20/schedule.html) if you want to learn about NP-Completeness, approximation algorithms, online algorithms, graph compression, multiplicative weights, computational geometry, fast multiplication, embeddings, FFT some other topics:

Recorded lectures 
15-451 partial archive:
magnet:?xt=urn:btih:0cd3da156921d9264a7e06b3fb148130037e1228&dn=15451

### 15.1 Introduction to Parallel and Sequential Algorithms

[Search libgen](http://libgen.rs/book/index.php?md5=133C8AB1B2EA8D696F762C1BCFFCC0F8) for 'Parallel and Sequential Algorithms' and get latest version. I archived all the lecture notes and some of the labs before they disappeared [here](https://github.com/functionalCS/15210labs). The book is excellent, it goes through many common algorithms you already know about and then teaches you how to make them more parallel and is used in CMU's 15-210 course which now is sealed up behind campus logins.

15-853 _Algorithms in the [Real World](https://www.cs.cmu.edu/afs/cs/project/pscico-guyb/realworld/www/slidesS18.html)_ is another excellent resource that covers some 15-210 content and more.

### 15.2 Functional Data Structures

"A stroll through intermediate data structures and their associated algorithms, from the point of view of functional programming." Note how pattern matching makes implementing these seemingly complicated structures a much easier task.

*   [(Book) Functional Data Structures](https://cs.uwaterloo.ca/~plragde/flaneries/FDS/)
    *   Exercises and examples done in OCaml, no formal background beyond a typical introductory CS course
    *   A more advanced book [Purely Functional Data Structures](http://www.cambridge.org/ca/academic/subjects/computer-science/programming-languages-and-applied-logic/purely-functional-data-structures?format=PB&isbn=9780521663502) by Chris Okasaki uses an imaginary version of SML with Haskell solutions in the appendix.

### 15.3 Advanced Data Structures

Taught by Erik Demaine's at MIT, mixes 2017 lectures with MIT OCW 2012 lectures, I used this course to learn cache-oblivious data structures while taking 15-853 _Algorithms in the Real World_.

*   [(Full Course) 6.851 Advanced Data Structures](https://courses.csail.mit.edu/6.851/fall17/lectures/)

16 Complexity Theory
--------------------

### 16.1 Undergraduate Complexity Theory

Expands on the lectures in 15-251.

*   [(Full Course) 15-455 Undergraduate Complexity Theory](http://www.cs.cmu.edu/~15455/)
    *   Recorded lectures [here](https://www.youtube.com/playlist?list=PLm3J0oaFux3YL5vLXpzOyJiLtqLp6dCW2)
    *   Uses Part III of the Sipser [book](http://math.mit.edu/~sipser/itoc-derrs3.1.html) _Introduction to the Theory of Computation_
    *   A 2017 [survey](https://www.scottaaronson.com/papers/pnp.pdf) of the current state of P vs. NP by Scott Aaronson

### 16.2 Graduate Complexity Theory

You may want to [try solving](https://news.ycombinator.com/item?id=6346697) some of the problems in this domain.

*   [(Full Course) 15-855 Graduate Computational Complexity Theory](http://www.cs.cmu.edu/~odonnell/complexity17/)
    *   Recorded lectures [here](https://www.youtube.com/playlist?list=PLm3J0oaFux3b8Gg1DdaJOzYNsaXYLAOKH)
    *   Uses the [book](http://theory.cs.princeton.edu/complexity/) (free draft) _Computational Complexity - A Modern Approach_

### 16.3 Useful Math for Theoretical CS

These scribed lecture [notes](http://www.cs.cmu.edu/~odonnell/toolkit13/) give you a diverse background in math useful for theoretical CS, from the excellent book [The Nature of Computation](http://www.nature-of-computation.org/) such as these [slides](http://www.cs.cmu.edu/~15751/2016-lecture1.pdf) from _A Theorist's ToolKit_ which describe how to find research, how to write math in LaTeX, how to give a talk, resources on math.overflow etc.

Prof Ryan O'Donnell has now uploaded [lectures](https://www.youtube.com/playlist?list=PLm3J0oaFux3ZYpFLwwrlv_EHH9wtH6pnX).

17 Introduction to Quantum Computing
------------------------------------

This is a graduate introduction to quantum computation/information theory, from the perspective of theoretical computer science.

*   [(Full Course) 15-859BB: Quantum Computation](http://www.cs.cmu.edu/~odonnell/quantum18/)
    *   Recorded lectures on [YouTube](https://www.youtube.com/playlist?list=PLm3J0oaFux3YL5qLskC6xQ24JpMwOAeJz).
    *   The prereqs are an undergrad background in complexity theory (15-251 or 15-455), linear algebra, and discrete [probability](http://www.cs.cmu.edu/~odonnell/papers/probability-and-computing-lecture-notes.pdf).
    *   "90% of the understanding of the quantum circuit model is achieved by reviewing three purely 'classical' topics: classical Boolean circuits; reversible classical circuits; and randomized computation"
        *   A [series](https://www.morganclaypool.com/toc/qmc/1/1) of curated papers on Quantum Computing

18 Performance Engineering
--------------------------

If you've taken 15-213 [Computer Systems](#x86%20Computer%20Systems) or 6.004 [RISC-V Architecture](#RISC-V%20Architecture), and understand basic graph algorithms and matrix multiplication you will understand this course, as it covers performance analysis, instruction-level optimizations, caching optimizations, and other techniques for high performance, scalable systems. The course is done in C but the concepts apply to any compiled language.

*   [(Lecture Notes) - 6.172 Performance Engineering of Software Systems](https://learning-modules.mit.edu/materials/index.html?uuid=/course/6/fa18/6.172#materials)
    *   Click on 'Export Materials ZIP' before they're gone
    *   There are older lectures for this course on MIT OCW/YouTube with similar content
    *   See the first slide 'Intro & Matrix Multiplication' for a good desc of this course

19 Topics in Mathematics for Finance
------------------------------------

Notice there's a [button](https://learning-modules.mit.edu/materials/index.html?uuid=/course/18/fa19/18.642) for "Export Materials ZIP". 18.642 also has an older course on Open CourseWare with [lecture videos](https://ocw.mit.edu/courses/mathematics/18-s096-topics-in-mathematics-with-applications-in-finance-fall-2013/). You may also find interesting this Quantitative trading [summary](https://blog.headlandstech.com/2017/08/03/quantitative-trading-summary/) and this old post on [pricing & hedging](https://ieor.columbia.edu/files/seasdepts/file_attach/BoysGuide.pdf) models.

20 Jobs
-------

This [service](https://triplebyte.com/) matches your skills to people who want to pay you. Jane Street Capital is a finance tech company that hires functional programmers worldwide, you may want to [apply](https://blogs.janestreet.com/interviewing-at-jane-street/) there (after practicing a lot on [Kattis](https://open.kattis.com/)). There are numerous opportunities to apprentice as a [security researcher](https://www.nccgroup.trust/us/about-us/careers/current-vacancies/security-consultant/). There are also bounties for writing features available on topcoder, gitcoin or bountysource A large collection of remote job listing and consulting platforms is [here](https://docs.google.com/spreadsheets/d/1JfNAbUX_lN9K3MCNHO15GJtJ5qpk7H9Cl3xTBwv2FR8/htmlview).

I recommend checking local schools and labs in your area for research programmer positions, students often do not apply to these campus jobs as they are chasing internships and it's where I got started.

21 Workshop in Computational Type Theory
----------------------------------------

I decided to make a new workshop [here](https://functionalcs.github.io/curriculum/typetheory.html) to learn cubical/computational type theory.

22 Workshop in Machine Learning/AI
----------------------------------

There exists an ongoing [workshop](https://learnaifromscratch.github.io/) to teach ourselves machine learning/ neural networks doing 3 courses at once.

### 22.1 General AI

You can still watch Berkeley's CS188 on [Youtube](https://www.youtube.com/playlist?list=PLVYtzYiUdm4ThHyh_pnhNQwdmN_OmryLc), uses Norvig's new 4th edition book out in 2020 but any edition you can find will do including the old Lisp addition that is available free on github. Just write your own autonomous agents for exercises. Sussman's grad [course](https://ai6034.mit.edu/wiki/index.php?title=6.S966:_A_Graduate_Section_for_6.034#Prospectus) is the perfect match to CS188 reviewing older papers with unsolved problems or deep ideas, like his own _Art of the Propagator_ paper and [implementation](http://groups.csail.mit.edu/mac/users/gjs/propagators/). There is also AI [readings](https://courses.csail.mit.edu/6.803/schedule.html) to explain intelligence from a computational point of view both these are nice compliments.

### 22.2 Math Background for ML

This free [book](https://mml-book.github.io/) _Mathematics for Machine Learning_ will describe the math often used in ML. There's also a series of [recorded](https://www.youtube.com/playlist?list=PL7y-1rk2cCsAqRtWoZ95z-GMcecVG5mzA) lectures and recommended [texts](https://canvas.cmu.edu/courses/603/assignments/syllabus) from CMU and a crash course in linear algebra [here](https://www.youtube.com/playlist?list=PLC7GP7QTnIJ8w2qcrHK1nIy7mWQnYSOmr) and a set of [notes](https://www.cs.cmu.edu/~zkolter/course/15-884/linalg-review.pdf). You may also enjoy the [Vector Boot Camp](http://www.math.brown.edu/~dkatz/vectorbootcamp/) from Brown for the multivariable calculus content.

### 22.3 Statistics Theory

*   [(Full Course) 36-705 Intermediate Statistics](http://www.stat.cmu.edu/~larry/=stat705/)
    *   The author of _All of Statistics_ Larry Wasserman covers Chapters 1 - 12 from his book and more covering the fundamentals of theoretical statistics in these recorded lectures
    *   The lectures assume you already read Chapter 1 - 2
    *   There are many probability lectures around to go with the beginning chapters such as [here](https://www.youtube.com/playlist?list=PL_Ig1a5kxu57qPZnHm-ie-D7vs9g7U-Cl)
    *   The quality of these can be changed to 1080p but the audio is terrible, however you can extract the audio easily, and use Audacity (free) to suppress some of the background noise and boost his voice.

### 22.4 Modern Regression

CMU professor Cosma Shalizi has a great set of lecture [notes](http://www.stat.cmu.edu/~cshalizi/TALR/) _The Truth About Linear Regression_ in fact if you go through his extremely large page on [notebooks](http://bactra.org/notebooks/) he will explain the insight to virtually [everything statistics](http://bactra.org/notebooks/statistics.html) related such as what are [stochastic differential equations](http://bactra.org/notebooks/stoch-diff-eqs.html) and notes about [teaching statistics](http://bactra.org/notebooks/teaching-statistics.html) which books are recommended. I wish more professors did this.

### 22.5 Introduction to Machine Learning

Torrent archive:

Recorded zoom lectures, homework:
magnet:?xt=urn:btih:2e1005d058b5f4c357d7338c85937aabdd91dcdc&dn=10601

*   [(Full Course) 10-301/601 Sp 2020 Introduction to Machine Learning](https://www.youtube.com/playlist?list=PLpqQKYIU-snAPM89YPPwyQ9xdaiAdoouk)
    *   Assignments are in your language of choice
    *   We're going to do this in the [AI workshop](https://learnaifromscratch.github.io/)

### 22.6 Introduction to Practical Machine Learning

"This course will teach you basic skills to decide which learning algorithm to use for what problem, code up your own learning algorithm and evaluate and debug it." You don't have to use Python, the prof in these lectures shills Julia for students to try instead.

*   [(Full Course) CS4780 Machine Learning for Intelligent Systems](http://www.cs.cornell.edu/courses/cs4780/2018fa/lectures/index.html)
    *   YouTube [lectures](https://www.youtube.com/playlist?list=PLl8OlHZGYOQ7bkVbuRthEsaLr7bONzbXS), additional reading [recommendations](http://www.cs.cornell.edu/courses/cs4780/2018fa/page18/index.html) and videos for each topic
    *   Kaggle has numerous [tutorials](https://www.kaggle.com/learn/intro-to-machine-learning) and competitions available
    *   We do this course in the [AI workshop](https://learnaifromscratch.github.io/)

### 22.7 Graduate Introduction to ML

There is also Cornell's advanced ML [class](https://www.cs.cornell.edu/courses/cs6780/2019sp/) though they deleted the recorded lectures like most other schools post-covid19

*   [(Full Course) 10-701 PhD Introduction to ML Fall 2020](https://www.cs.cmu.edu/~epxing/Class/10701-20/)
    *   Lectures are on YouTube, we go through this course in the [AI workshop](https://learnaifromscratch.github.io/)
    *   Use another semester for recommended [reading](http://www.cs.cmu.edu/~lwehbe/10701_S20/#schedule)
    *   Same professor teaches [10-708](https://www.cs.cmu.edu/~epxing/Class/10708-20/lectures.html) for problems with a very large number of attributes and huge datasets
    *   Try [18-337j](https://mitmath.github.io/18337/) a class in optimization (numerical analysis) and parallel ML using Julia, lectures are on YouTube

### 22.8 Advanced Statistical learning theory

*   [(Lectures) - 10-702 Statistical Machine Learning Theory](https://www.youtube.com/playlist?list=PLTB9VQq8WiaCBK2XrtYn5t9uuPdsNm7YE)
    *   A 2016 second grad course in statistical learning theory
    *   Assumes you have taken 36-705 (his book _All of Statistics_) and some kind of ML intro class at the level of 10-701
    *   Intended to be more advanced than the book _The Elements of Statistical Learning Theory_
        *   This course is now called 36-708 [Statistical Methods for Machine Learning](http://www.stat.cmu.edu/~larry/=sml/) w/course notes

### 22.9 Convex Optimization

Used to work on a variety of problems, recently research is in non-convex optimization of neural networks, search google scholar for 'non-convex'.

*   [(Full Course) 10-725 Convex Optimization](http://www.stat.cmu.edu/~ryantibs/convexopt/)
    *   Search YouTube for '10-725' to get most recent recorded lectures
    *   Completely self contained, see the [syllabus](http://www.stat.cmu.edu/~ryantibs/convexopt/syllabus.pdf)
    *   Some of this is in Wasserman's 10-702 above

### 22.10 Deep Learning

*   [(Full Course) 11-785 Introduction to Deep Learning](https://www.cs.cmu.edu/~bhiksha/courses/deeplearning/Fall.2015/)
    *   Recorded lectures [here](https://www.youtube.com/playlist?list=PLwrNrH82f0KgdZhGB7sm9NrOanfWBS-EN) to learn to build and tune deep learning models
        *   If the playlist is deleted, which is frequently, (use youtube-dl to archive) search YouTube for "CMU 11-785"
        *   Some [slides](http://www.archive.ece.cmu.edu/~ece739/schedule.html) on techniques for making deep learning robust to adversarial manipulation
        *   Thorough lecture [notes](https://www.cs.cornell.edu/courses/cs4787/2019sp/) and jupyter books on scalable machine learning systems

### 22.11 Further Research

*   Search 'AI competitions' and try some past competitions
*   Open [challenges](http://www.chalearn.org/) in ML
*   [Algorithmia.com](https://algorithmia.com/) an open marketplace for AI algorithms
*   [Cosma Shilizi's](http://www.stat.cmu.edu/~cshalizi/) notes on [machine learning](http://bactra.org/notebooks/learning-inference-induction.html) and [learning theory](http://bactra.org/notebooks/learning-theory.html)

23 Workshop in Cryptography
---------------------------

I am working through Tanja Lange's course in post-quantum crypto and cryptanalysis in the new [crypto workshop](https://functionalcs.github.io/curriculum/crypto.html)

Daniel J. Bernstein's posts on the IETF Crypto Forum Research Group \[Cfrg\] archive is a [master class](https://mailarchive.ietf.org/arch/msg/cfrg/E-q_6ABdKfPU5XG2N6IVAs_sNhA/?qid=435ba2be2c3db3444e338cc0259ee124) in modern [cryptanalysis](https://mailarchive.ietf.org/arch/msg/cfrg/oOY_QNA6QMsTJHLLbUjch6-GLsc/?qid=435ba2be2c3db3444e338cc0259ee124) and he rips apart bad standards/protocol designs, we will try to understand some of these in the crypto workshop above.