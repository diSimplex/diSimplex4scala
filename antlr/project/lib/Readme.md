# SBT plugins

## sbt-antlr4

This project makes use of the sbt-antlr4 plugin which can be found at:

> https://github.com/ihji/sbt-antlr4

At the moment this project does not (yet?) publish its plugin as a 
Maven/Ivy accessible archive. Until they do I have cloned the project, 
built the required sbt-antlr4-0.7.jar file and then placed it into this 
directory.

# Adding jar based plugins (from GitHub?) 

1. Obtain the required jar file.

1. Place the jar to this project/lib directory

1. You do NOT need the addSbtPlugin command

1. You MAY need some additional configuration options in your build.sbt