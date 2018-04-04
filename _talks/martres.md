---
title: "Integrating IDEs with Dotty, the experimental Scala compiler"
layout: talk
lookAndFeel: deep-orange
page_name:
  "martres"
type:
  "Presentation"
abstract:
  "<p>A great programming language should provide a great developer experience! This is why Dotty comes built-in 
  with IDE support that is designed to be easy to use, robust and extensible. In this talk I’ll describe the 
  technologies used to implement this as well as our future plans. </p>"
description:
  "<p>The IDE support in Dotty was developed to meet the following requirements:
      
  <ul>
      <li> It should be based on primitives that can be reused to develop other interactive tools, like REPLs.</li>
      <li>It should not be tied to a specific editor.</li>
      <li> It should be as easy to install and use as possible.</li>
  </ul>
  </p>
  
  <p>
  This lead us to develop the following components:
  <ul>
      <li> A set of APIs in the compiler designed for interactive usage.</li>
      <li> The Dotty Language Server, an implementation of the Language Server Protocol</li>
      <li> A plugin for the Visual Studio Code IDE to launch the Dotty Language Server, as well as a plugin for the 
      sbt build tool to configure and run an IDE</li>
  </ul>
  </p>
  
  <p> 
  In this talk, I’ll describe how these components were developed. I will also describe our future plans such as:
  <ul>
      <li> A powerful build tool integration based on the new Build Server Protocol</li>
      <li> Debugging support (including evaluation Scala expressions at runtime) based on the Java Debug Server</li>
  </ul>

  <p>
  Ultimately, we would like the compiler to become much better at helping you write correct programs instead 
  of just complaining when you make mistakes.</p>"
speakers:
-
  name:
    "Guillaume Martres"
  bio:
    "<p>PhD student at EPFL working on Dotty, the new Scala compiler.</p>"
  image:
    "martres.png"
---
