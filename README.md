A simple plugin to use the [Tidal Cycles](https://tidalcycles.org/) live programming environment with kakoune.

**do not forget to open kakoune inside tmux!**

So far, it offers the following functions:

- `:tidal-start-repl <BootTidal.hs>` opens up the tidal repl in a new pane.
- `:tidal-start-superdirt` launches supercollider and superdirt in a new window
- `:tidal-send-line` sends the current line to the repl
- `:tidal-send-block` sends the current block (paragraph) to the repl
- `:tidal-hush` sends the hush command to the repl

You could bind those commands to keys such as :

```
map global normal <c-e> ':tidal-send-block<ret>'
map global normal <c-h> ':tidal-hush<ret>'
```

Have fun!
