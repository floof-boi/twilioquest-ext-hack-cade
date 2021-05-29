# Come On In, the Water's Fine (Hello World!)

<div class="aside">
<h3>Logbook</h3>
<ul>
  <li>Read the <strong>Introduction</strong>, <strong>Sample Code</strong>, and the <strong>Task</strong>.</li>
  <li>Once you enter your answer text for the Task, hit <em>HACK</em>.</li>
</ul>
</div>

**[STARBOARD] - Ship Log - Entry 1**
At last! I am aboard the <strong>Starboard</strong>, the mightiest ship among the stars. For many moons I attempted to track this fabled vessel - for I desire the **great treasure** rumored to lie within.

But with great treasure comes great challenge. This ship has naught to do with the dreaded **Legacy Systems** - according to legends, however, it does contain puzzles in an older, stricter, oft unforgiving language: **C**.

I am here to learn about this low-level language - I must harness its power if I am to find the treasure aboard this ship. A journey is about to begin... once I hack through this pesky laser door.

Good thing someone left some notes here.

---

## Introduction

Welcome to the **Starboard**, a legendary starship roaming the High C. The objectives aboard aim to give operators a basic grasp of the C language.

A common program used to introduce a new programming language is `Hello World`. In this objective, you will complete a C version of `Hello World`.

## Sample Code

Below is a sample program written in C:

```js
#include <stdio.h>
#include <stdlib.h>

int main(void) {

  printf("Ahoy, TwilioQuest!\n");

}
```

When executed, this program will print `Ahoy, TwilioQuest!` to the console.

- `printf()` is a C **function** that prints its input parameter to the console.
- Note that in this example, the text passed into `printf()` (and printed to the console) is contained in quotes (which don't appear on the console).
- Also note that there's a funny `\n` **inside** the quotes, after the text. This is a **newline** character - we'll explain it soon.

Some extra info on the snippet itself:

- `#include <stdio.h>` is a **preprocessor directive** that includes the C "Standard I/O" system header when compiling the program - allowing us to gain access to and use `printf()`.
- `int main(void){}` is one way of declaring and using the program's `main` function - more on this in the next objective.

## Task

Read the following example code:

```js
#include <stdio.h>
#include <stdlib.h>

int main(void) {

  ???

}
```

Based on the sample code above - in order for this new program to print `Hello World!` to the console, what line of code should replace the `???`?

Enter the one line of code into the answer box on the right, then click _HACK_ to validate your answer.

