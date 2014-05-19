Eightlime - [Sublime 3](https://www.sublimetext.com/3) Theme
=============================================

Inspired by Modern UI style in Windows 8.

**Note**: Currently there is only Dark theme. I will start working on Light theme if there are demands.

![Eightlime Dark - HTML](http://cdn.setyono.net/eightlime/dark-html.jpg)

![Eightlime Dark - CSS](http://cdn.setyono.net/eightlime/dark-css.jpg)

![Eightlime Dark - Markdown](http://cdn.setyono.net/eightlime/dark-markdown.jpg)

Installation
-------------------

**Download with Package Control**:

1. In [Sublime 3](https://www.sublimetext.com/3), press <kbd>Ctrl</kbd><kbd>Shift</kbd><kbd>P</kbd>.

2. Type in `Install` and select the `Package Control: Install Package`.

3. Wait a few seconds for a new popup to appear, then search for `Eightlime` and select it.

**Setting up the Theme**:

1. Change the Editor color by going to: `Preferences > Color Scheme > Theme - Eightlime > Eightlime Dark`.

2. Change the GUI by going to `Preferences > Setting - User`.

It will open the setting text file. Add the following line:

```json
    { "theme": "Eightlime Dark.sublime-theme" }
```

Overall, mine looks like this:

```json
    {
      "color_scheme": "Packages/Theme - Eightlime/Eightlime Dark.tmTheme",
      "ignored_packages":
      [
        "Vintage"
      ],
      "theme": "Eightlime Dark.sublime-theme",
    }
```

License and Credit
-------------------

Eightlime is MIT Licensed and based on:

- [Dark Eight](https://github.com/ShawnMcCool/theme-dark-eight)

- [Piatto](https://github.com/samuelrafo/piatto)

- [Monokai Extended](https://github.com/jonschlinkert/sublime-monokai-extended)

- [Railscast](http://railscasts.com/)
