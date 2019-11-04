# Code Blocks
If we wanted to add code blocks (blocks of code) to a markdown project, which is something that's **extremely likely** for me and most developers, then we have 2 ways of doing that.<br>

The first way is to select the block of code we want setup in a snippet and simply indent it. VSC (and most code editors setup for markdown editing) will recognize that the text is code and put it in a code snipped/block automatically.

Here is the latest code for the mentioned snippet:

    let x = 100;
    const name = "Jacob";

    $age = 36;
    $sex = male;
    echo strToUpper($name);

There is a second and 'cleaner'/better organized way of doing it and that is to apply tripple 'back-ticks' (``` ` ```) [non-shift tilde key] before and after the code block, keeping in the markdown language key.

```

let x = 100;
const name = "Jacob";

$age = 36;
$sex = male;
echo strToUpper($name);

```
We can apply line-breaks before and after the actual code block to give more 'breathing room' for the code block, and adds some black/grey space around the code itself for better visual presentation.

Another great trick for code blocks is that if we apply an abbreviation after the initial back ticks (html, css, php, js, etc.) then VSC (or whatever code editor is being used) will recognize what language you're code belongs too and apply colorization and so forth to the code snippet with can add a lot of visual kick, not to mention readability.

For example, a simple JavaScript snippet:

```js

let asawa = "Melgine";
let sis1 = "Ame";
let sis2 = "Ares";

if (asawa == "Melgine") {
    console.log("I love " + $asawa + "!");
} else {
    console.log("Oh, hello my gwapa sister-in-law!";
}

```

We can also stick code snippets inline with other text without adding an entire 'code-block'. This way it is easy to separate the code itself from the other text but it doesn't break it off into it's own block as seen above Check it out:<br>

"Hey man, did you try `let x = 250;`, like I suggested?"

***

Another cool trick we have with code snipets is that we can display added and removed lines (or suggested add/remove lines) by apply a + or - within the code snippet, and setting the 'language' (mentioned above) as seen below:

```diff
let name = "Jacob";
let x = 100;
- var y = 200;
+ var y = 365;
```