# Pokemon-Go: The Programming Language

Pokemon go was designed as an extension to the [go programming language](https://golang.org) and is therefore fully backwards compatible with it. However, this project supplements go by adding alternate keywords to patch what was clearly an oversight in the original design: A lack of pokemon in the keywords of a language called "Go".

## Imports

To help you feel like a trainer, instead of simply `import`ing libraries, now you can call them back to you like pokemon with ` <libname>, come back!`.

## Assignment

Assignment, formerly possible with the `var x = y` syntax, can now be done with `I choose you, x to be y` to help you feel like the pokemon trainer you always wanted to be while you're stuck debugging the same section of code for the two thousandth time and haven't slept in 48 hours and are on the verge of a breakdown but pokemon syntax will keep you sane!

## Looping

We're all familiar with looping. As Einstein put it "The definition of insanity is doing the same thing over and over again, but expecting different results." Now you don't have to be the one driven insane by loops but can instead delegate it to your friendly pokemon, Forretress! Just tell Forretress what to do with `Forretress use <loop description> {` instead of the boring old `for (<loop description>) {`

## Conditional Statements

Ever wanted to be a pokemon? Now you can, with conditional statements in Pokemon-Go! Instead of a boring old `if <x> {} else if <y> {} else {}`, ask `What will Program do? <x> {} It wasn't very effective... Try <y> {} Gotta catch em all! {}`

## File format

Pokemon-Go files should have the `.pkmn` extension, a shortening of pokemon.

## Running programs

You need to have some sane-ly recent version of ruby installed to run this language. Simply add the `trainer` executable to your `PATH` and then call `trainer lets go <file name>` (or just run `./trainer lets go <file name>`). It will produce a `out.go` file (because `go run` can't read from STDIN, rip) and then run it.

## Example

See the test.pkmn file for an example program!
