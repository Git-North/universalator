This is a fork of https://github.com/nanonestor/universalator 

The main difference between the original and this fork is that this fork uses a different java distribution (amazon coretto for LTS and Azul Zulu for Java 11)

The reasoning for that is Adoptium's java lacks certain features which are needed for certain mods while also having an inferior garbage collector. This fork tries to solve that problem by using different java distributions.

Another difference is that this version of universalator.bat uses Aikars jvm flags which increase performance on modded and vanilla servers, Has better automation support thanks to less inputs required to start the server, and removed code that forces online-mode and allow-flight to true
