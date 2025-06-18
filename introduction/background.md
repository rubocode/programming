> [introduction](./)

![banner](/programming/photos/banner.png)

## Background

> Premature optimization is the root of all evil.  
> **Donald Knuth**

When I joined the Institute of Fundamental Studies in April of 1989, I had graduated from high school and knew the BASIC programming language.  I learnt BASIC on a Sinclair Spectrum connected to a TV display that was available at my alma mater Royal College.  I later studied BASIC on a VTech LASER made available by the Lions Club of Malabe — my hometown.

At the IFS, we had a Data General MV/7800 Eclipse system running AOS/VS (Advanced Operating System / Virtual Storage) that had been donated by the Japanese government.  I learnt to program in Fortran77 and C.  I also learnt Donald Knuth's TeX typesetting system.

In 1990, I moved to the USA to study at Stevens Institute of Technology in Hoboken, New Jersey.  I majored in Computer Engineering with a minor in Philosophy.

I worked as a co-op student at Maidenform in Bayonne, New Jersey developing the Automated Lace Cutting Machine (ALCM).  It was initially developed using QuickBASIC.  After the initial prototype, we wanted to do a more advanced system and we realized QuickBASIC couldn't cut the mustard.  That was when — in 1993 — we considered C and when we ordered a C compiler from Borland, what we got was Turbo C++.  That was the beginning of my C++ journey.

In my senior year (1995-96) at Stevens, I worked at Engineering Information, Inc.  This was the time of the birth of the World Wide Web.  I learnt and programmed in Perl.

After graduation, I joined Salomon Brothers and continued to use C++ and Perl working with trading systems.  The trading systems were running on SunOS and Solaris operating systems from Sun Microsystems.  I was also exposed to Ruby and Python during this period.  I loved Ruby and disliked Python.

Later (2007-2013), I worked with the Swedish startup Cirrato Technologies developing Direct Print Technology (DPT) written primarily in C++.  I also used C# for some projects, but considered .NET to be unnecessarily complex — designed by engineers instead of programmers.  Imagine a house designed by a civil engineer instead of an architect.

C++ went through a standardization process and was hijacked by a committee.  If you ever heard the phrase “design by committee,” you would understand the ills that went with that.  As the language aged, the committee started pushing for adopting the syntax of more recent languages resulting in the desire for redesigning the language.  After four decades, the language is still not stable in the basics.  The standard gets updated every 3 years.  They are still not done on the syntax for modules. Please!

Since C++ became a complex jumbled mess, I was looking for an alternative programming language for high performance computing.  I was glad to discover the Go.  It has many good properties, and it is a systems language.  Unlike C++ which advocates complexity and a partial grasp of the language even for experts, Go advocates minimalism.

Ruby was very appealing to me when I encountered it in the nineties.  It was simple, elegant and sophisticated.
But, in the end, it is a dynamic interpreted language and reliability and quality guarantees are theoretically impossible given the programmer makes a mistake that will explode at run-time.  The general remedy is test-driven development and test coverage, but that is a false goal.

You must eventually get the machine (universal rules) to provide any guarantee.  Compiled languages with static type checking helps you avoid and correct bugs better and over time the programs become more reliable with much less tests.

Don’t forget that you have to test the tests as well.  So, there is still plenty of advantage in human intervention in the design and implementation of computing systems.

With the right abstractions at the lower layers reliability and flexibility improves over time.




