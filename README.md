## For Assignment 3 instructions, view this Google Doc:

https://docs.google.com/document/d/1eqM8CRp4r2J8i-yOxb2IaiI7cPYwjSeRrhRjkPW5obo/edit

  * After reading that document, your work will be done inside the file main-scene.js.  The code comments of that file should help you get started with modifying a Scene object.  Later, when you're curious you can explore the documentation of the rest of the codebase (which appears in the files themselves, as comments).

# tiny-graphics.js

This is a small, single file JavaScript utility.  It organizes WebGL programs to be object-oriented and minimally cluttered.  

Writing code with raw JavaScript and WebGL is very repetitive and tedious, whereas using frameworks like three.js creates too much separation between you and learning JavaScript and WebGL.  Unlike other frameworks, tiny-graphics.js is purpose-built for education and teaches you how it is made.

This tiny library gives your WebGL program access to linear algebra routines, useful UI controls and readouts, and the drawing utilities needed by modern shader-based graphics.  It factors away the repetitive logic of GPU communication into re-usable objects.  The objects can be seamlessly shared between multiple WebGL contexts (drawing regions) on a web page.
