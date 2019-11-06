# Simple FD Generator

## Motivation

This is a very simple and probably not a very good piece of software ( this was done in a very short time ). I had an Assignment in Introduction To Databases where we should find FD's (functional dependencies) in a file with 44k lines of entities. It seemed like a trivial and time-consuming assignment and is, therefore, the reason for this tools existence.

## Note

1. The program only works for tables with entities in them, i is impossible for the prorgam to detect any FD's without entitie sin the table.
2. The postgresql driver ( postgresql-42.2.8.jar ) should be added to the project through Intellij. ( can be done from the cmd line too )
	- Open project structure. ( File > Project Sructure ) or Ctrl + Alt + Shift + S
	- Add it as a library.
3. It **Should** work on any given DB.
