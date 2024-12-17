This is a fork of https://github.com/nanonestor/universalator 

The main difference between the original and this fork is that this fork uses a different java distribution (amazon coretto for LTS and Azul Zulu for Java 11)

The reasoning for that is Adoptium's java lacks certain features which are needed for certain mods while also having an inferior garbage collector. This fork tries to solve that problem by using different java distributions.

It also has some misc improvements like:
- Using Aikar's Flags
- Removal of `online-mode: true` enforcement
- Removal of `allow-flight: true` enforcement
- Support for command-line arguments (Better Automation)
- Server Launches in 25 seconds after going to the "Launch Server" screen
