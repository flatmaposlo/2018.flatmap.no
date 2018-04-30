---
layout: talk
lookAndFeel: green
page_name:
  "winje_mork"
speakers:
-
  name:
    "Jonas Winje"
  bio:
    "<p>Jonas is a developer at Computas. He likes pretty animals and programming languages, and has an 
    MSc in Computer Science from the University of Oslo. Dislikes things. (Also likes cute animals. 
    (Some animals are pretty animals and are also cute animals.)) </p>"
  image:
    "winje.png"
  twitter:
    "JonasWinje"
-
  name:
    "Heidi Mork"
  bio:
    "<p>Heidi is a developer at NRK. She once studied mathematics and ended up with a PhD in algebraic geometry. But 
    at some point she discovered programming and she has been enthusiastic about it ever since. Heidi finds most 
    aspects of software development interesting, and is especially fond of functional programming and programming 
    language theory. </p>"
  image:
    "mork.png"
  twitter:
    "heidicmork"
title:
  "Make your own meta-circular evaluator!"
type:
  "Workshop"
abstract:
  '<p><b>Attendee preparation:</b><br/>
  Bring a laptop with DrRacket (https://racket-lang.org/) installed.</p>
  
  <p>Building evaluators is a fun way to learn about programming languages. “Amb” is cool because it’s a 
  pretty small extension to a more regular FP lang, but it’s enough to make it feel like proper different to 
  program in, and makes certain programs (particularly backtracky ones) really easy to write. </p>'
description:
  '<p><b>Attendee preparation:</b><br/>
  Bring a laptop with DrRacket (https://racket-lang.org/) installed.</p>

  <p>From building our own small evaluators we can learn about how programming languages are made and what kind of 
  design decisions we can make when building languages, as well as about ideas and techniques that we can make use 
  of in our everyday programming. More important: Making evaluators is lots of fun! </p>
     
  <p>A meta-circular evaluator is an implementation of a programming language in an existing language, where the 
  implementation “reuses” parts of the language it is implemented in. This lets us skip a lot of tedious plumbing, 
  and we can quickly get a working new language implementation that we can play and experiment with.</p>
      
  <p>In this workshop we will start with a simple evaluator for a “calculator-language” with basic arithmetic 
  operations, and then gradually expand it into more and more sophisticated evaluators. We will end up with an 
  evaluator for a language with special features for solving logic puzzles and constraint satisfaction problems, 
  similar to the amb-evaluator in the book “Structure and Interpretation of Computer Programs.”</p>'
---
