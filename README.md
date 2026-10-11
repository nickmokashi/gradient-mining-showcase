# Gradient Mining

### It is the gap that pays, not the pile.

A research book, and a Windows map of the research behind it, about getting useful work out of the difference between things, and out of the enormous amount of energy thrown away on purpose: the heat a supermarket's refrigeration dumps out of the back, compressed air, braking, sewer heat, data centres, and electricity at the wrong place and hour.

**The book, the research file and the ideas in them are private.** This page shows how the two are made, and what the checking caught.

---

## The book

<p align="center"><img src="cover.jpg" alt="Gradient Mining cover: a pickaxe striking a seam of crystal that runs from hot orange to cold blue" width="420"></p>

**Version 12, about 123,750 words.** It stood at 66,000 at Version 4. Each version is rebuilt whole from the chapter files, and copies go to a Kindle Scribe for reading. Version 11 added the cover: a pickaxe striking a seam that runs from hot to cold, because the gradient is the ore. Version 12 added four researched and cross-checked ideas, on how Idaho prices power for its biggest customers, on waste heat already being turned into electricity at a phosphate plant, and on what the federal records rule promises the person asking.

It is made for a reader who is not a trained engineer or scientist and teaches himself fast.

* **The idea in ordinary words first, then a number, then the technical name,** and only if the name has earned a place. Naming a thing is not explaining it.
* **Every chapter opens with a page called Start here** that defines every word it is about to use, from zero, whether or not another chapter already did.
* **There is no reading order.** Open it anywhere.
* **Plain Words**, a section before chapter one, gives every term in the book in ordinary language, for when looking something up beats guessing.
* **When a number decides something, the arithmetic is shown once, in full**, with real figures.
* **Fahrenheit and feet throughout.** Chapter one once had twenty-five temperatures in Celsius and twenty-four distances in metres, and it went unnoticed because nobody was counting.

**Appendix Two**, at the back, lists what every version added, changed and dropped, and what the checkers caught.

## How the research is checked

Research runs in pairs. Two agents each take an idea from a queue and research it, then they **swap and check each other's work**, and only what survives goes into the book. Every checker report is kept with the book.

A separate version of the book, made with Solina (ChatGPT), was taken apart claim by claim. Five genuinely new topics came out of it and were researched again from scratch, and a few small details were folded in. The rest was dropped, including a load figure that was simply wrong and two figures with no source behind them.

## What the checking caught

A method that never costs anything is decoration. These are the receipts.

**A checker caught the book about to print something false.** It said a federal agency had invented a particular phrase. The Justice Department's own annual report uses that phrase more than four thousand times, 1,555 of them in the office that writes the rules. Nobody had opened that document.

**Every conclusion reversed.** A chapter went back to a federal file of 2,096 records requests and read every one. A third of the file was two people sending the same letter over and over, and once they were taken out, every conclusion the first pass had drawn turned around. The passage now says so. And because each row begins with the requester's name, the fingerprint used to spot the repeat letters carries a private person's surname, so it is never printed.

**The one number the book trusted died.** Checked against a second quarter, the real grant rate for those requests was 48 percent, not 32, and the pattern the book had leaned on, that short requests do better, was gone. Naming a file format still helps.

**A leak rate was quoted at the top of its range.** The book gave a supermarket refrigerant leak rate of 25 percent. That is the ceiling of the typical range. Where somebody actually measured across many stores, it was 15.6 percent. Still enormous, just not what was printed.

## The app

A Windows desktop map of everything the book is built from.

* **Seven groups of research**, sized by how much each holds, with lines between them weighted by how many connections cross.
* **Inside a group, every topic is a circle.** A filled dot means an opportunity lives there, a small number means open next steps, a dashed ring means an open question. Click a topic and everything unrelated dims, so you can see what it actually touches. Drag it, and it stays where you put it.
* **A reading panel opens beside the map**, never over it: plain English first, numbers and sources underneath.
* **A one-line entry takes about ten seconds.** Four fields show, everything else waits behind More details, and changes save themselves.
* **One research file**, a real SQLite database, is the master copy. Right now it holds 79 topics and more than 140 connections.
* **Every change rebuilds a Word reading edition** a few seconds later, so the map and the document can never drift apart.
* Search, category filters, light and dark.

**Honest about its limits:** removing a topic archives it rather than deleting it, but there is no button to bring one back yet.

Plain Electron, with no framework and no build step. The database runs as WebAssembly, so there is no native compile step either.

**There are no screenshots here, on purpose.** Every screen of the app shows the research.

## Status

The book is at Version 12. The app is version 0.1.0, for Windows. The code and the book are private.

---

**Directed by Greygray. Produced by Solina and Claude.**

Human judgment stays in the driver's seat.
