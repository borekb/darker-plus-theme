# Darker+ theme for VSCode

The default Dark+ theme with dark*er* backgrounds.

_Default Dark+:_

<img width="1193" alt="Default Dark+ theme" src="https://user-images.githubusercontent.com/101152/64846546-32666100-d60d-11e9-8125-634ca24a93e7.png">

_Dark**er**+:_

<img width="1193" alt="Darker+ theme" src="https://user-images.githubusercontent.com/101152/64846545-32666100-d60d-11e9-9840-7176d3fcfac4.png">

## Make it your own!

One of the points of a separate theme is that you can customize it separately. For example, if you prefer fully black backgrounds, you could do this in your `settings.json`:

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

You can then switch between Dark+ and Darker**+ easily.

_Fully black Darker+:_

<img width="1193" alt="Screenshot 2019-09-13 at 10 27 33" src="https://user-images.githubusercontent.com/101152/64848309-2ed4d900-d611-11e9-9ddc-e6104b86f57b.png">

## Motivation

I like the default Dark+ theme very much – it looks nice and importantly, doesn't suffer from usability issues so common in 3rd party themes (low contrast in "edge cases" like diff editors, weird colors for selection, etc.). So this theme is really minimal – just updates the backgrounds for late-night hours, like this (pseudocode in `settings.json`):

```json
{
  "workbench.colorCustomizations": {
    "editor.background": "#151515",
    "sideBar.background": "#202020"
  }
}
```
