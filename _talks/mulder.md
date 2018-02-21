---
title: "Regaining Control with State Monad and Friends"
layout: talk
lookAndFeel: deep-orange
page_name:
  "mulder"
type:
  "Presentation"
abstract:
  "<p>From side-effect free state modification to Finite State Machines. The State Monad 
  is immensely useful and actually - not scary at all. In this talk we’ll get comfortable 
  with the state monad from Cats, and learn how we can write functional APIs that describe 
  state transition on the type level.</p>"
description:
  "<p>A state transition can be modeled as a simple function:</p>
  
  <pre>type State[S, A] = S => (S, A)</pre>
       
  <p>In this talk we’ll see how indexed monads like the State Monad are built around this 
  simple concept.</p>

  <p>From side-effect free state modification to Finite State Machines. The State Monad is 
  immensely useful and actually - as will be shown throughout this talk, definitely, not scary at all.</p>
     
  <p>We’ll get comfortable with the state monad from the Cats library, and learn how we can write 
  functional APIs that describe state transition on the type level using indexed monads.</p>"
speakers:
-
  name:
    "Felix Mulder"
  bio:
    "<p>Former Compiler Engineer at LAMP, EPFL. Building the next generation Scala compiler - Dotty. 
    Currently lambda head at Klarna in Stockholm, building purely functional things in Scala.</p>"
  image:
    "mulder.png"
  twitter:
    "felixmulder"
---
