---
title: "Declarative Control Flow with Fs2 Stream"
layout: talk
lookAndFeel: purple
page_name:
  "labella"
type:
  "Presentation"
abstract:
  "<p>fs2 support for concurrency means that we can use streams to model program flow in a composable, declarative 
  fashion. This talk will introduce the main concurrency abstractions of fs2 through practical examples. </p>"
description:
  "<p>fs2 is a purely functional streaming library, with support for concurrent and nondeterministic merging of 
  arbitrary streams. Concurrency support means that we can use Stream not only to process data in constant memory, 
  but also as a very general abstraction for control flow: whilst IO gives us an excellent model for a single 
  effectfull action, assembling behaviour with it often has a very imperative flavour (pure, but still imperative). 
  This talk will introduce fs2 combinators by example, and will hopefully show how we can model control flow in a 
  declarative, high level, composable fashion. In particular, we will focus on concurrent combinators.</p>"
speakers:
-
  name:
    "Fabio Labella"
  bio:
    "<p>I’m a Senior Software Engineer based in Edinburgh, UK, working in Scala in the financial industry. 
    I also actively participate in Open Source (as SystemFw): I’m one of the maintainers of fs2, and a contributor 
    to cats, shapeless, http4s and most of the other libraries in the Scala FP ecosystem. I have a passion for 
    helping people master advanced concepts (e.g. see here or here), so hit me up on Gitter if you have a question!</p>"
  image:
    "labella.png"
---
