# how to install

> step by step

## download
Download using the [GitHub .zip](https://github.com/ChameleonTheme/WindowsTerminal/archive/master.zip)

## install
Start Windows Terminal and click on the down arrow symbol `˅` from menu bar. This will open a drop down menu from which select Settings option. Alternatively use `Ctrl + ,` to open Settings directly.

In the `settings.json` settings file for Windows Terminal, find the `schemes` section and paste the content of `chameleon.json`.

Example:
`
"schemes": [
    {
      "name" : "Chameleon",
      "background" : "#645d6e",
      "black" : "#030705",
      "blue" : "#4B93DC",
      "brightBlack" : "#131313",
      "brightBlue" : "#77abe0",
      "brightCyan" : "#9fecec",
      "brightGreen" : "#43d4a2",
      "brightPurple" : "#e39fd7",
      "brightRed" : "#d7726e",
      "brightWhite" : "#FFFFFF",
      "brightYellow" : "#fbe08f",
      "cyan" : "#20dbdb",
      "foreground" : "#0d1c22",
      "green" : "#01BB7B",
      "purple" : "#DD80CC",
      "red" : "#CC4E48",
      "white" : "#eeeeee",
      "yellow" : "#F7D263"
    }
]
`
Activate
Once the color scheme has been defined, it's time to enable it. Find the profiles section and add a colorScheme value to the default profile.

Example:
`
"profiles": {
    "defaults": {
        "colorScheme" : "Chameleon"
    }
}
`
