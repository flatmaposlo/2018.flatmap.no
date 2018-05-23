---
title: "Akka: A Best Friend (Forever!) for your Backend-for-Frontend"
layout: talk
movie: https://www.youtube.com/embed/DRxLFWmvJ8A
lookAndFeel: blue
page_name:
  "geest"
type:
  "Presentation"
abstract:
  "<p>Would you like to break up a monolith into microservices? Would you like to push live data to your 
  end-users? This talk will teach you how to use the Backend-For-Frontend pattern to answer these questions. 
  PagerDuty implemented BFFs with Akka HTTP and Streams, and we’re here to share our learnings!</p>"
description:
  "<p>PagerDuty has been breaking apart a monolithic codebase and replacing it with microservices which directly 
  power customer-facing APIs. These microservices need generic edge concerns (like authentication) handled for 
  them, and they need easy ways to provide data to end-users. That data is usually delivered in response to 
  HTTP requests, but increasingly also delivered “live” via WebSockets.</p>
  
  <p>Backends-for-Frontends (BFFs) is one pattern for addressing those needs. Attendees can expect to learn 
  about the BFF pattern and how PagerDuty implemented it using Akka HTTP to proxy API requests and aggregate 
  data, and Akka Streams to deliver live data from Kafka to our end-users.</p>"
speakers:
-
  name:
    "David van Geest"
  bio:
    "<p>As a Senior Software Engineer on the Core Team at PagerDuty, David works on mad-scientist projects 
    designed to solve difficult, systemic problems experienced by other engineering teams. This means building 
    services, libraries, or other shared infrastructure, often in Scala.</p>
    
    <p>David lives in Toronto; he enjoys playing board games, cooking, and installing Linux on everything. You can 
    usually find him cycling about the west end in search of tasty food and beverages.</p>"
  image:
    "geest.png"
  twitter:
    "DWvanGeest"
---
