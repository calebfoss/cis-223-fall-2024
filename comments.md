# Comments

## Introduction

Comments are text in a code file that the computer completely ignores. That's all they are!

While that might not seem useful at first, comments are an incredibly useful part of coding. Code can become confusing and tedious to process as a human. Comments allow us to write notes to human readers to make that process much easier!

Additionally, sometimes it can be helpful to temporarily remove some code from a file. If you want to check what happens when some code is ignored, you can turn that code into a comment. If you want to restore the code, all you need to do is uncomment it.

## Syntax in JavaScript

We can tell the computer to ignore a single line in a file by starting it with `//`.

```js
// This is a single line comment
1 + 1;
```

In the example above, the computer will ignore the first line and then evaluate the expression `1 + 1`.

We can tell the computer to ignore multiple lines by starting with `/*` and ending with `*/`.

```js
/* This is a multi-line comment.
This is still part of the same comment.
So is this. */
1 + 1;
```

In the example above, the computer will ignore the comment as simply evaluate `1 + 1`.

## Shortcut in Visual Studio Code

Code editors like VSCode typically include a shortcut for marking a line as a comment.

In VSCode, select the text you want to comment out and press

- `ctrl + /` on Windows
- `cmd + /` on Mac

To uncomment text, follow the exact same steps!
