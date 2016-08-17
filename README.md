# Config

**Config** is a basic checklist I follow to set up a new development environment on a windows machine. It's heavily inspired by [mdo's version for Macs](https://www.github.com/mdo/config).

## General preparations

### 1. Setup Firefox

- Download and install latest version of [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/).
- Make sure [Firebug](http://www.getfirebug.com/) extension is installed.

### 2. Setup Git

- Download and install latest version of [Git Bash](https://www.git-scm.com/).
- Load [`.gitconfig`](/.gitconfig) contents into the global `~/.gitconfig`

**About CRLF and LF:** If you want to have only `LF` endings in your remote repository, you don't need to set the default value for line endings to `LF` in any editor or IDE, because Git replaces Windows' `CRLF` endings with `LF` endings automatically when `core.autocrlf` is set to `true` in Git's config.

## Web development

### 3. Setup XAMPP
- Download and install [XAMPP](https://www.apachefriends.org/index.html).
- Set `DocumentRoot` to `~/work` folder in Apache's `httpd.conf` (and make sure access to that directory is granted).

### 4. Setup Node.js

- Download and install latest version of [Node.js](https://www.nodejs.org/en/).

### 5. Setup Atom

- Download and install latest version of [Atom](https://www.atom.io).
- Install favourite packages:
  - [Wrap in tag](https://www.atom.io/packages/atom-wrap-in-tag)
  - [Selector to tag](https://www.atom.io/packages/selector-to-tag)
  - [EditorConfig](https://www.atom.io/packages/editorconfig)
  - [Keyboard Localization](https://www.atom.io/packages/keyboard-localization)
- Disable packages `wrap-guide` and `spell-check`.

## Java development

### 6. Setup JDK

- Make sure the latest version of [Java Development Kit](http://www.oracle.com/technetwork/java/javase/downloads/index.html) is installed.
- Make sure environment variable `JAVA_HOME` is set.

### 7. Setup Eclipse

- Download and install latest version of [Eclipse](https://www.eclipse.org).
- Change some preferences (`Window` > `Preferences`):
  - Set `Windows` theme (`General` > `Appearance`).
  - Make sure `Text Font` is set to `Consolas` (`General` > `Appearance` > `Colors and Fonts`).
  - Disable spell checking (`General` > `Editors` > `Text editors` > `Spelling`).
  - Change `Tab policy` to `Spaces only` in the currently used profile (`Java` > `Code Style` > `Formatter`).

### 8. Additional tools

- Download and install latest version of [Maven](https://maven.apache.org/).
