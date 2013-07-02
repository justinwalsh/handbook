Coding Handbook
========

My personal coding style guide and development environment handbook.

>The long-term value of software to an organization is in direct proportion to the quality of the codebase. Over its lifetime, a program will be handled by many pairs of hands and eyes. If a program is able to clearly communicate its structure and characteristics, it is less likely that it will break when modified in the never-too-distant future.

>Code conventions can help in reducing the brittleness of programs.

>All of our JavaScript code is sent directly to the public. It should always be of publication quality.

>Neatness counts.

>[- Douglas Crockford](http://javascript.crockford.com/code.html)

##Editor

[Sublime Text 2](http://www.sublimetext.com/2) FTW!

###Packages

Here are the packages I use to make Sublime even more awesome. Note: Install 'Package Control' first, it will make installing any of the others alot easier.

* [All Autocomplete](https://github.com/alienhard/SublimeAllAutocomplete) - Adds autocompletion accross all open files.
* [BracketHightlighter](https://github.com/facelessuser/BracketHighlighter) - Hightlights opening and closing brackets on selection.
* [Copy File Name](https://bitbucket.org/nwjlyons/copy-file-name) - Copy the file name from the sidebar context menu.
* [Editor Config](https://github.com/sindresorhus/editorconfig-sublime) - Uses the standard .editorconfig files to control code.
* [Git](https://github.com/kemayo/sublime-text-2-git) - Adds some nice GIT features. I mostly use 'blame' to dig into changes.
* [GitGutter](https://github.com/jisaacks/GitGutter) - Adds indicators next to line numbers to signify changed or modified lines. Helps review/cleanup code changes before commiting.
* [JsFormat](https://github.com/jdc0589/JsFormat) - A great tool for formating JS or JSON code before commiting.
* [Package Control](http://wbond.net/sublime_packages/package_control) - A must have plugin for installing the rest of these plugin.
* [SFTP](http://wbond.net/sublime_packages/sftp) - Adds a full suite of FTP features to Sublime.
* [SideBarEnhancements](https://github.com/titoBouzout/SideBarEnhancements) - Adds alot of great features to the sidebar context menu.
* [Terminal](http://wbond.net/sublime_packages/terminal) - Add a 'Open a Terminal Here' option on the sidebar context menu.
* [Theme - Soda](https://github.com/buymeasoda/soda-theme/) - My prefered Sublime theme.
* [Trailing Spaces](https://github.com/SublimeText/TrailingSpaces) - Makes it easier to spot and remove trailing spaces.

##JavaScript

I spend most of my day writing JavaScript. This is how I prefer to do it.

### Code Style

I follow the general practices of the following [style guide](http://javascript.crockford.com/code.html) published by Douglas Crockford.

### General Rules

* Semicolons everywhere.
* Indentation should use 4 spaces. Tabs should never be used.
* Lines should have soft breaks at 80 characters for readability.
* Declare all vars at the begining of scope.
* Brackets go on the same line as function/if/switch statement.
* All conditionals use brackets regards of it they are required.
* Use === and !== in all conditionals.
* Don't use eval unless you fill out a TPS report.