# 🐸 Fungi Frog Maze / Sprig Web Template 👾

This repository includes the open-source code for my game Fungi Frog Maze programmed using [Sprig](https://github.com/hackclub/sprig/), an open source game console, web-based game editor, and hardware development kit. This also works as a template for you to implement your own games.

## Template Quickstart 

The index.html file has everything you need to get started, just add your js sprig game in the following segment replacing my game:
> If you get lost, check how I implemented my game inside the [index.html](https://github.com/jzaleta/sprig-web-template/blob/main/index.html) file!

```html
<!-- The Sprig device's aspect ratio is 5:4  -->
<canvas width="500" height="400" id="canvas" tabindex="0"></canvas>

<script type="module">
  import { webEngine } from "https://esm.sh/sprig@1/web"

  function runGame(api) {
    // Your game code here.
  }

  const game = webEngine(document.getElementById("canvas"))
  runGame(game.api)
</script>
```
Remember, to make a Sprig game you'll need to use [Sprig's Web Editor](https://sprig.hackclub.com/~/new).
