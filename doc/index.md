---
title: Home
layout: home
---

Space Battle Arena
============

Space Battle Arena is a ‘[Programming Game](http://en.wikipedia.org/wiki/Programming_game)‘ where you must write code (in Java) to autonomously control a space ship to accomplish specified objectives.  

This has been a final project used in an Advanced Placement High School Computer Science course since 2012.  Students have been enthusiastic, excited, challenged, and engaged with learning to control a ship in a physical environment and comparing strategies against their fellow students in a fun competition.

The question of why ‘Space Battle’ over an existing platform (like [Robocode](http://robocode.sourceforge.net/)) was brought up during our [Reach for the Stars](http://www.mikeware.com/2012/09/reach-for-the-stars-educating-the-next-generation-using-games/) talk.  The answer is that most programming games are built around a specific objective.  This means that while there may be varying strategies, eventually the problem can be solved and solutions available.  

In addition, it means the challenge is fixed and always the same.  For an educational context specifically, where this is most students first exposure to a 'third-party' library.  We wanted a system which could ease them into new concepts that build on what they had learned throughout the course of the year.  

Finally, allowing the system to be extensible and configurable, means that challenges and difficulty can be directly geared to a specific group of students abilities which can fluctuate from class to class.  Space Battle was our test bed and has proved successful with the multiple different challenges we have run over the past few years.

Space Battle Arena is [licensed](LICENSE) under the GPLv2.  [Gson](https://github.com/google/gson) is licensed under the Apache license and provided for convenience in the [bin](bin/) directory.

Student Environment
-------------------------
It is expected that students have completed a full year of Java programming in high school or just over a semester of programming at the college level.

We use [jGRASP](http://www.jgrasp.org/) as our IDE of choice when working with High School students, but any Java IDE can be used that is capable of adding a jar to a classpath and executing a class from within the jar as the main class.

Documentation
------------------
* [Client Setup](client/index.html) - [jGRASP](client/jGRASP/index.html), Eclipse
    * Add both GSon and SpaceBattle jars to classpath
    * Create a Ship which implements the Spaceship interface.
    * Execute the TextClient class of the SpaceBattle.jar file with two arguments:
        1. IP address of the server
        2. name of the Ship class
* Server Setup
    * Use the run.bat with the name of a config file
* Server Configuration Notes
* Server GUI Controls
* Lesson Outlines
    * Introduction and Setup
    * 'Find the Middle'
    * Shapes in Space
    * Intro to Radar
    * Finite State Machines
* Guides
    * World Coordinates and Rotations
    * Objects
    * Coding Call/Response
    * Your Ship's 'Computer'
* Competitions
    * Bauble Hunt
    * Asteroid Miner
    * Bauble Hunt SCV
    * King of the Bubble
        * King of Space (Variant using King of the Bubble game parameters)
* Talks
    * [You Have Died of Dysentery: Games in Education Are Still Alive - PAXDev 2014](http://www.mikeware.com/2014/08/you-have-died-of-dysentery-games-in-education-are-still-alive/)
    * [Reach for the Stars - PAXDev 2012](http://www.mikeware.com/2012/09/reach-for-the-stars-educating-the-next-generation-using-games/)
* [Development](dev/index.html) - Extend Space Battle Arena
