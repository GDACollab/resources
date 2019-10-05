# Code Editors

## General purpose editors

[Sublime Text](https://www.sublimetext.com/) (de facto free, feel free to pay for it if / when you get a job. outperforms most editors, fantastic out of the box for python, and/or any languages that you don't have a better editor for. Text buffers are insanely optimized, . fully cross platform, and the dev(s) who built this are fully worth supporting)


[Visual Studio Code](https://code.visualstudio.com/) (microsoft's free / open source clone of sublime. cross platform, open source, and has nothing to do with visual studio outside of the name. Built on web tech, ie. electron, but has better performance than eg. atom. tends to have better plugins and autocomplete support for some languages, particularly javascript variants and web stuff. And markdown - this article was written in VS code using the builtin markdown editor / no markdown plugins, for example)

Note: personally I use both of these, and I use them for different things. Sublime is a great default that performs better and can handle waaaay more open windows / textbuffers efficiently than vscode; vscode is great as a lightweight editor / semi-IDE that has better autocomplete and previewing, for some languages, than sublime. Meanwhile, I'll usually use a full IDE for some of the languages below. For c++ I usually use both an IDE and a good text editor, ie. using sublime for navigating through a codebase and making quick edits, and the IDE for larger changes where I need full autocomplete to write code that interfaces with existing code, libraries and frameworks, and/or for the debugger and profiling.

## C#

[Jetbrains Rider](https://www.jetbrains.com/rider/) (free while you're a student / have a .edu email. jetbrains IDEs are first in class, and rider is essential if you're working with c# on any platform but windows)

[Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) (free, runs on windows + mac os, bundled with unity installs. technically this is not visual studio either, as it's a rebrand of xamarin studio, an IDE used for cross-platform mobile development using c#, so it's worth noting that this is NOT visual studio, which is a good / bad thing. Properly, you should be calling this xamarin studio, cuz that's what it is. And microsoft did not develop this either, as xamarin was just a company they acquired that was using cross-platform .NET to build cross-platform mobile applications)

[Monodevelop](https://www.monodevelop.com/) (unity *used* to bundle this. It kinda sucks compared to the other options, if you have them, but is a solid, decent-ish IDE. And it's cross platform, free, and open source. Note that mono is the name for open source .NET, and mono is the core technology that unity's scripting system is / was built off of)

## C++

[Visual Studio](https://visualstudio.microsoft.com/downloads/) (awful text editor out of the box. maybe awful IDE in general. Gets much better with plugins, which are required. No, I don't have a list for you, sorry, though [Resharper](https://www.jetbrains.com/resharper/) and [Resharper C++](https://www.jetbrains.com/resharper-cpp/) are essential plugins if you like jetbrain's stuff. But anyways, visual studio has best in class performance profiling, and a powerful debugger. The debugger is... actually quite a bit worse than xcode's if you're just working with modern c++, but has more "features" you can use, like watch inspectors, and being able to view memory as hex, I guess. Pros: powerful tools and lots of extensions. Cons: this is a really shity IDE by default, no offense)

[Xcode](https://developer.apple.com/xcode/) (the apple IDE. relatively awful text editor, was not built for writing c++ at all (it's for swift and obj-c, and just incidentally has c and thus c++ support), but you do nevertheless get some pretty good autocomplete, and some fantastic, close to best in class breakpoints, debugging, and profiling tools. You will also need to install this if you want to develop literally anything from source on apple platforms, so if you're a dev and don't have this installed you should go do that. Pros: defaults + tools are very good (except the actual text editor, which is crap). Cons: not extensible at all, next to no plugins cuz apple gradually killed them all off, and xcode was never terribly extensible in the first place)

[Clion](https://www.jetbrains.com/clion) (jetbrain's badly named / punny c++ IDE. quite good by this point, and uses cmake as its native project format, which is a massive win. Best cross platform c++ IDE, slightly worse debugger than visual studio / xcode, but makes up for it by being a less shitty editor (in general), and is extremely extensible via plugins. Very good (albeit as a bit of a jack of all trades); suffers a bit from the fact that technically this is a very heavily modified java IDE (jetbrains IDEA is for and written in java). Obviously free while you're a college student, but not actually free afterwards, but don't let that stop you - any dev studio worth its salt would just buy this for you if you needed it)


## Rust

[Clion + Official Rust Plugin](https://plugins.jetbrains.com/plugin/8182-rust) (fantastic, literally turns clion into a fully featured rust IDE, by far the best way to write rust code, period)

There are also good plugins for visual studio code and sublime, and it was all made possible by the rust community's focus on building good tools for the language, specifically this: [racer](https://github.com/racer-rust/racer).
