---
title: "The List"
layout: single
---

# The List

The List is simply a list of personal projects I am, have, will, do, and am working/worked/want-to-work on; no more, no less.

It is in no particular order. Many of the projects listed (if not all) are what I like to call (to help myself sleep at night) "long-term projects". I'll work on one for a week or a few months or something and then get depressed and wait a few days (or weeks) and then go to another, rinse and repeat.

The important thing to note is that I _do intend_ to continue developing all of the projects on this list.

Also, some of them (many? *shugs*) may or may not be public; however, I will only add projects to this list that I intend to _eventually_ make public (open-source). If the project is public, its name will be a link to the git repo. (And of course, anything and everything on this list is subject to change without notice at any time.)

:)

 - [**ihex.lua**](https://github.com/sci4me/ihex.lua) - An Intel Hex encoder/decoder for Lua
   - I have absolutely no idea why I decided to create this, other than that it was (has been) a lot of fun. I think the fun in this project was honestly nothing to do with what the library itself is and does, but more about the process.
     It's nothing special; Intel Hex is a _very_ simple file format that conveys binary information in ASCII form. A simple implementation only takes a few hundred lines (or perhaps even less in more terse languages). But like I said,
     it was ... it was "an end to a means"(?) -- does that even make sense? lol. That probably isn't a very good phrase to explain what I said about "the process" but f*ck it, ya get me. ;)
     
 - **bred** - Better Editor
   - I have used just about every editor that is actually worth giving a shot that exist;
     VS Code, IntelliJ, Sublime Text 2 and Sublime Text 3, Notepad++ (lol jk that was before I knew anything), Vim, etc. (Okay I'm only kidding, I'm _quite certain_ there's plenty of editors worth giving a shot that I didn't include here. Don't @ me.) The only major one that I haven't tried for long enough to count (that I can think of rn) is Emacs.

     They all have their pros and cons, of course, and I love them all for different reasons, but simultaneously hate them all for different (and some shared) reasons.

     So one day I was like "Write a text editor I said. It'll be fun I said."
     Next thing you know, **bred** came into existence. From humble beginnings as a [lite](https://github.com/rxi/lite) ripoff (seriously though, thank you [rxi](https://github.com/rxi) -- you gave me **one heck of a head-start** on this project!), **bred** has become my to-be daily-driver for editing code as well as, well, just any arbitrary text. And other things perhaps? ;)

 - **eso69** - One small step for sci4me, one giant leap for esolangs around the globe.
   - This is "my esolang". Well, one of them.
   
     So, first of all, "eso69" is a placeholder name; I have yet to think of the real name.
     
     This is a statically-typed, compiled language, heavily inspired by [aya](https://github.com/nick-paul/aya-lang/), among others. Here's a quick list of the major elevator-pitch features:

       - parametric polymorphism
       - arbitrary compile-time code execution
       - macros
       - garbage collected (this isn't on the list out of pride btw)
       - coroutines
       - single threaded (totally a feature; who needs threads anyway)
       - self-hosted (this is an aspirational "feature"; 'bootstrap' compiler is written in Kotlin )

     Hilariously, as of the time I'm writing this, this compiler is my "best" compiler yet in terms of completeness. I have written a small handful of compilers over my programming career, with varying degrees of completeness; none of them even come close to this one, which amuses me to no end because this isn't even a "real language"; it's an esolang. The compilers I've written for "real languages" can't even compete with this. :joy:

 - **brainsucc** - Totally not an esolang.
   - So, as an edgy shitlord, I enjoy my fair share of _brainfuck_. **brainsucc** is my (to-be) "high-level" language that compiles to raw brainfuck. Not much to say about it as of now, unfortunately.

 - [**lbf4me**](https://github.com/sci4me/lbf4me) - another brainfuck
   - This time, written in one of my favorite LISP implementations, [Urn](https://urn-lang.com/).

 - [**J7Seg**](https://github.com/sci4me/J7Seg) - I love LEDs!
   - A stupid, simple 7-segment LED JComponent display thingy I wrote like 10^24 years ago.

 - [**turt-reynolds**](https://github.com/sci4me/turt-reynolds) - Turtle + Graphics

 - [**circuitfuck**](https://github.com/sci4me/circuitfuck) - like brainfuck but 2d and also not like brainfuck

 - [**Valerie**](https://github.com/sci4me/Valerie) - Believe it or not, I've never actually met one.
   - This is pure trash, don't read the code ever. Also it's the 'first' compiler I ever 'wrote'. It's pretty far from complete, to say the least. It was a statically-typed langauge with syntax 200% inspired by Jai (the best language that has ever been created, by Jonathan Blow), but for _some_ reason I decided that I wanted to compile this language to _Lua_. So that's what I 'did'.

 - [**NotACPU**](https://github.com/sci4me/NotACPU) - From the beforefore times...
   - So first of all, _I love relays._

     This is the remnants of a project I was working on like, idk, fifty trillion years ago, which was to design and build a _simple_ CPU using relays. (ngl tho I will actually execute on this someday TM)

     I actually wrote a pretty dope emulator for the design I had been planning to build, physically, with a GUI and everything. It actually emulated the design of the processor down to the microcode level; it was far more than just an interpreter. But, **tragically** I have lost the source code to this! Which is really a shame because it was essentially the coolest part of the whole project lol. Oh whale.

     And of course, the design I had was _practically a ripoff_ of [the incredible work of Harry Porter](http://web.cecs.pdx.edu/~harry/Relay/).

 - **XConnect** - Because one-upping is fun
   - XConnect is a Minecraft mod that allows you to transfer _anything_ (TM) between multiple Minecraft servers that are all running the mod.

 - [**CCLuaJIT**](https://github.com/sci4me/CCLuaJIT) - A mod that changes ComputerCraft to use LuaJIT
   - Not much else to say really; the goal was to be as lean as possible and implement just that one feature: LuaJIT rather than LuaJ as the "backend" for [ComputerCraft](https://www.computercraft.info/). It had [some success](https://www.curseforge.com/minecraft/mc-mods/ccluajit) (and it even works!).

     Also, side note, this was the project I used to learn JNI -- everyone talks shit about JNI but frankly, I'm kinda a fan (in _some_ sense of the word).

 - [**Neo**](https://github.com/sci4me/Neo-old) - My version of Lua but not crap
   - Don't get me wrong, I love Lua to death, but I also hate it for a few (mostly superficial) reasons.
     1. then/end rather than braces
     2. arrays starting at 1
     3. probably some other(s) I'm forgetting

     **Neo** is a dynamically-typed, interpreted/JIT-compiled language I wrote starting back in, iirc, 2017. This was still in what I'd consider the earlier days of my learning about compilers, parsers, etc. It is, as of now, perhaps my most complete "real language" (as in, not an esolang). It is very strongly inspired by Lua but I changed up the syntax, started arrays at the correct index, and did a handful of other things (such as add the defer keyword, for example).

 - [**FrainBuck**](https://github.com/sci4me/FrainBuck) - Using Lua as a Brainfuck DSL
   - This was a little experiment I did back in the day, using Lua to create an embedded DSL for generating brainfuck code in order to make it easier to "write brainfuck code by hand" (as it were).

 - [**Stella**](https://github.com/sci4me/Stella) - A top-down Factorio-style game (also, off-the-rails)
   - I love [Factorio](https://factorio.com/) as any sane person would. I also love making things. So, I made not Factorio (other than the extreme lack of completeness, ofc).

     That would be the end of the story except... for reasons that were once between God and I but now only God knows, I ended up deciding that I was going to refuse to use the C standard library (much less the C++ stdlib, lmao). So, a chunk of the project turned into learning about building software without libc, which was actually a LOT of fun, despite the pain. This project is also the best example I have of a lot of the things one learns in [Handmade Hero](https://handmadehero.org/). Also, it happens to be, afaik, my most well-commented project (as of time of writing) (which yes, of course I would be proud enough of to mention).

 - [**xboot**](https://github.com/sci4me/xboot) - A basic XMODEM "bootloader" for my 65(c)02-based homebrew computer
   - In 2019 I breadboarded up a simple 65(c)02-based computer, because why the fuck not :P
  
     In mid 2020, I got a wild hair up my ass and decided to spend a few days learning KiCad and designing a PCB for the computer (and of course I added a feature or three in the process because that's a good idea lol).

     And then I got it manufactured by [JLCPCB](https://jlcpcb.com/). It was my first time working with JLC; had used [PCBWay](https://www.pcbway.com/) in the past. (Not that it's relevant, but, in my experience, both are fine companies that offer **very** competitive pricing and have pretty-darn-good turnaround times).

     (Excuse the long background story lmao)

     **xboot** is a "bootloader" I can write onto the computer's EEPROM that lets me download code via the serial port and run it, so that I don't have to constantly remove the EEPROM, insert it into the programmer, program it, and reinsert it into the computer (which would've been (and was, actually) especially painful since I, in my infinite wisdom, failed to include a ZIF socket for said EEPROM on this PCB).

     (There either is or will be (TM) more on the 65(c)02 computer project on this page or somewhere on this site.)

 - [**FadeBabe02**](https://github.com/sci4me/FadeBabe02) - A crappy esolang that runs on my 65c02 computer

 - [**ICDB**](https://github.com/sci4me/ICDB) - In-Circuit Debugger (for 65(c)02 computer systems)
   - So after getting the PCB manufactured for my homebrew 65(c)02 computer, unsurprisingly, there were a few kinks (bugs, as it were). This (incomplete) project was an attempt to build something that could get inbetween the CPU and the rest of the computer to allow me to debug things. As I recall, I got bored of working on it (debugging) and haven't touched it since :P

 - [**sci.h**](https://github.com/sci4me/sci.h) - My single-header C/C++ library
   - Single-header libraries are a gift from God. This is mine. It's incomplete and I haven't touched it in ages. :P

 - [**brrr.h**](https://github.com/sci4me/brrr.h) - Just sh*tposting here, don't mind me.

 - [**nbody**](https://github.com/sci4me/nbody) - A super-old, incomplete octree-based n-body simulation

 - [**bfc**](https://github.com/sci4me/bfc) - A brainf*ck compiler
   - One of my numerous brainfuck implementations; not much else to say here. It's written in Java, the optimizations are all hardcoded (so I'm not particularly proud of their implementations :P), and uh, yeah. It emits C source code. If I recall correctly, this particular brainfuck implementation of mine is the one that implements the most optimizations:
     - contraction
     - clear loop removal
     - scan loop optimization
     - "multi-loop" optimization
     - "adjust set" optimization
     - set deduplication
     - "set adjust" optimization
     - null instruction removal
     - read clobber optimization
     - offset optimization

     (In all honesty, half of them are nearly worthless, but still :P)

 - [**caesar**](https://github.com/sci4me/caesar) - A rewrite of one of the programming projects I did in college before dropping out
   - Honestly I just enjoyed this project so much, for whatever reason, that I decided to re-implement it (numerous times lol). This one happens to be in [Crystal](https://crystal-lang.org/).

 - [**RustKatas**](https://github.com/sci4me/RustKatas) - A few tiny little programs from when I was first learning Rust

 - [**JBFJit**](https://github.com/sci4me/JBFJit) - A simple brainfuck-to-JVM bytecode JIT
   - This is from when I was first learning JVM bytecode and the [ASM](https://asm.ow2.io/) library. Not much to say about it; it translates brainfuck to JVM bytecode and runs it.

 - [**8x8display**](https://github.com/sci4me/8x8display) - A cute little electronics project I did once upon a time
   - This was a 8x8 LED matrix display I built using some small PIC microcontroller (iirc) and a couple shift registers because I was bored.

 - [**CrypticVision**](https://github.com/sci4me/CrypticVision) - A Minecraft mod that adds animated REZZ glasses

 - [**sgl**](https://github.com/sci4me/sgl) - A (very WIP, kinda dead) software rasterizer written in [Odin](https://odin-lang.org/)
   - Once upon a time I decided to actually write code along watching [thebennybox's](https://www.youtube.com/user/thebennybox) [3D Software Rendering](https://www.youtube.com/watch?v=Y_vvC2G7vRo&list=PLEETnX-uPtBUbVOok816vTl1K9vV1GgH5) tutorial series. Then I said "this is cool but what if it had a JIT compiler". Then I stopped working on it. Thank you for coming to my TED talk.

 - [**odin-libjit**](https://github.com/sci4me/odin-libjit) - [libjit](https://www.gnu.org/software/libjit/) bindings for Odin

 - [**odin-sdl_bitmap_font**](https://github.com/sci4me/odin-sdl_bitmap_font) - Before I learned the glory of [stb_truetype](https://github.com/nothings/stb/blob/master/stb_truetype.h)

 - [**odin-quad_tree**](https://github.com/sci4me/odin-quad_tree) - A simple quadtree library written in Odin

 - [**ff4j**](https://github.com/sci4me/ff4j) - A hobby JVM implementation written in Odin
   - I got "pretty far" into it. I had a decent chunk of class file parsing implemented and had even taken the first baby steps on an interpreter.

     Quick backstory: I started this project back when I was playing with [Odin](https://odin-lang.org/) quite a bit, and needed a project to work on (as an excuse to write Odin code). A friend of mine had worked on a (really amazing) project called [JVML-JIT](https://github.com/Team-CC-Corp/JVML-JIT) which was a (get this) JVM, written in Lua, running in ComputerCraft (you know, the Minecraft mod), that JIT-compiled to Lua bytecode. I shit you not. It sounded like a fun idea at the time. Eventually though I got bored; writing a JVM is not a weekend project :P
    
 - [**odin-ring_buffer**](https://github.com/sci4me/odin-ring_buffer) - Name says it all; it's a ring buffer library, written in Odin

 - [**odin-sparse_bitset**](https://github.com/sci4me/odin-sparse_bitset) - A super-neat little data structure, written in Odin
   - This was sort of another project I did as an excuse to write some Odin code back when I was first getting excited about the language.
   
     This is also one of my favorite [data structures](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.30.7319&rep=rep1&type=pdf), not because of its usefulness necessarily, but just because, well, idk really :P I just think it's neat. It's certainly one of the more unique ones I've seen. It also happens to be beautifully simple.

     Maybe I'll blog about it someday (TM)

 - [**jaja**](https://github.com/sci4me/jaja) - A rewrite of a stupid esolang I made a few years ago (or.. more..) or something.
   - So back in the day (long enough ago that my memory is essentially nonexistent) I wrote a little esolang which was _basically_ just [False](http://strlen.com/false-language/). (Now that I think about it, it must have been around the time (after, probably) I wrote **JBFJit** because this esolang also had a JIT to JVM bytecode...)

     **jaja** was an attempt to rewrite this language in C++ using [libjit](https://www.gnu.org/software/libjit/) rather than an interpreter. As I recall, it was _somewhat_ complete, if you exclude the bugs and the joke of a garbage collector.

 - [**ll65**](https://github.com/sci4me/ll65) - A 65(c)02 compiler toolkit
   - This was going to be the toolchain I would use for my homebrew 65(c)02 computer. I did implement "a bunch of stuff" but again, eventually slipped away from the project. As much as I don't hate Rust, I think nowadays, I'd probably do this in C++ (Or Jai if it were (is? i.e. in le' future) available).

 - [**x6502**](https://github.com/sci4me/x6502) - A fork of [the original x6502 project](https://github.com/haldean/x6502) that implements the full WDC 65c02 instruction set

 - [**bfkit**](https://github.com/sci4me/bfkit) - A brainfuck 'toolkit' including a compiler and (gdb-style) debugger

 - **MCRHDL** - Minecraft Redstone Hardware Description Language
   - Someday (TM)
