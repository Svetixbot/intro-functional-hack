---
title: Document Center
---

Introduction to functional programming with Scala
=========

##Setup, Install and download all the things:

###Install SBT

* Install sbt with brew if you are on MacOs:
        $ brew install sbt

* If you are on Windows:

    [Download and install it](https://dl.bintray.com/sbt/native-packages/sbt/0.13.6/sbt-0.13.6.msi)


###Clone the repo:
        $ git clone https://github.com/Svetixbot/calculator.git
        

###Run sbt and compile the project:
        $ cd calculator
        $ sbt
            > compile
            > test


###Install IDE of your choise

####IntellijIdea
* [Download and install it if you don't have it yet](http://confluence.jetbrains.com/display/IDEADEV/IDEA+14+EAP)
* [Install Scala plugin](http://confluence.jetbrains.com/display/SCA/Getting+Started+with+IntelliJ+IDEA+Scala+Plugin)
* IntelliJIDEA should be able to open the project by File/Open (dont forget to install Scala Plugin)

####Eclipse
* [Download and install Eclipse aka Scala IDE](http://scala-ide.org/)
* To open a project in Eclipse you need to run special command:
        $ sbt eclipse
* After its done go to Eclipse and do File/Import -&gt; Existing Projects into workspace


####Sublime
* Install SublimeRepl and SublimeSBT plugins using package control

