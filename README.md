# Darker+ theme for VSCode

The default Dark+ theme with a darker background.

_Default Dark+:_

<img width="1193" alt="Default Dark+ theme" src="https://user-images.githubusercontent.com/101152/64846546-32666100-d60d-11e9-8125-634ca24a93e7.png">

_Darker+:_

<img width="1193" alt="Darker+ theme" src="https://user-images.githubusercontent.com/101152/64846545-32666100-d60d-11e9-9840-7176d3fcfac4.png">

## Make it your own!

One of the points of a separate theme is that you can target it in `settings.json`. For example, for true blacks, you can do this:

```json
{
  "workbench.colorCustomizations": {
    "[Darker+]": {
      "editor.background": "#000000",
      "sideBar.background": "#000000"
    }
  }
}
```

You can then switch between Dark+ and Darker+ easily.

_Darker+, full blacks:_

<img width="1193" alt="Screenshot 2019-09-13 at 10 27 33" src="https://user-images.githubusercontent.com/101152/64848309-2ed4d900-d611-11e9-9ddc-e6104b86f57b.png">

## Praise for Dark+

I like Dark+ very much: it not only looks good but also _doesn't_ suffer from many usability issues so common in 3rd party themes, like low contrasts in "edge cases" like diffs, weird colors for selection, etc.

If you wanted to modify Dark+ directly, this would have the same effect as using this theme:

```json
{
  "workbench.colorCustomizations": {
    "[Default Dark+]": {
      "editor.background": "#151515",
      "sideBar.background": "#202020"
    }
  }
}
```

However, you might find it useful to be able to switch between Dark+ and Darker+, say for day- and night-time coding.
