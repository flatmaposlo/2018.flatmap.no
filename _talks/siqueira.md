---
title: "Learning cats-effect by Accident"
layout: talk
lookAndFeel: deep-orange
page_name:
  "siqueira"
type:
  "Presentation"
abstract:
  "<p>Contributing to OpenSource is great, and learning while doing so is even better. This is the 
  story of how I learned cats-effect and other tools from its ecosystem, while contributing to an 
  awesome OS project and community.</p>"
description:
  "<p>Lets talk about cats-effect, in a very specific perspective: we will go through the work done 
  to migrate the rho DSL from being tied to fs2.Task, to being effect agnostic with cats-effect. 
  Rho is a library that adds the capacity to generate swagger definitions to the http4s library, 
  and since http4s has already been ported to cats-effect, the same was required for rho, which 
  makes it a perfect case study for us. Cats-effect gives you the freedom to choose which effect 
  implementation you actually want, be it cats-effect’s own IO, monix Task, scalaz Task or 
  something else. </p>"
speakers:
-
  name:
    'Paulo "JCranky" Siqueira'
  bio:
    '<p>Paulo “JCranky” Siqueira is a Senior Software Engineer at Zalando, where he has lots of 
    fun writing functional code in Scala. He is passionate about Scala and a frequent Open 
    Source contributor.</p>
        
     <p>Paulo blogs at https://blog.jcranky.com and can be found as “jcranky” 
     both on twitter and on github.</p>'
  image:
    "siqueira.png"
  twitter:
    "jcranky"
---
