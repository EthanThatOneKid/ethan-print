# `Ethan:Print"Ethan";:GoTo Ethan`

How did we get to this point?

- <https://linkedin.com/in/etok>

Hi! I'm Ethan.

I'm a software engineer. My first introduction to programming was
[QB64](https://qb64.com/), an IDE for developing modern applications in BASIC.

Here is an example of some valid QB64 code:

```basic
Print "Ethan"
```

The line above will print the string "Ethan" to the console.

In BASIC, you can associate a label with a line of code. For example, let's give
this line of code a label of "Ethan".

```basic
Ethan: Print "Ethan"
```

Let's end the instruction with a semicolon.

```basic
Ethan: Print "Ethan";
```

To start a new instruction all on the same line, use a colon. For example, let's
add a `GoTo` instruction to make the code go back to the label "Ethan".

```basic
Ethan: Print "Ethan";: GoTo Ethan
```

<details>
<summary>What happens when you run the above program?</summary>

The code above will print the string "Ethan" to the console and then go back to
the label "Ethan". In other words, the code above will print the string "Ethan"
over and over again until the user forcefully exits the program.

</details>

## Reference

- [10print](https://10print.org/)
- [QB64](https://qb64.com/)
