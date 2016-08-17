# Config

**Config** is a basic checklist I follow to set up a new development environment on a windows machine. It's heavily inspired by [mdo's version for Macs](https://www.github.com/mdo/config).

## General preparations

### 1. Setup Firefox

- Download and install latest version of [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/).
- Make sure [Firebug](http://www.getfirebug.com/) extension is installed.

### 2. Setup Git

- Download and install latest version of [Git Bash](https://www.git-scm.com/).
- Load [`.gitconfig`](/.gitconfig) contents into the global `~/.gitconfig`

## Web development

### 3. Setup XAMPP
- Download and install [XAMPP](https://www.apachefriends.org/index.html).
- Set `DocumentRoot` to `~/work` folder in Apache's `httpd.conf` (and make sure access to that directory is granted).

### 3. Setup Node.js and XAMPP

- Download and install latest version of [Node.js](https://www.nodejs.org/en/).

### 4. Setup Atom

- Download and install latest version of [Atom](https://atom.io)
- Install favourite packages:
  - [Wrap in tag](https://atom.io/packages/atom-wrap-in-tag)
  - [Selector to tag](https://atom.io/packages/selector-to-tag)
  - [EditorConfig](https://atom.io/packages/editorconfig)

## Java development

### 5. Setup JDK

- Make sure the latest version of [Java Development Kit](http://www.oracle.com/technetwork/java/javase/downloads/index.html) is installed.
- Make sure environment variable `JAVA_HOME` is set.

### 6. Setup Eclipse

- Download and install latest version of [Eclipse](https://www.eclipse.org).
- Change some preferences (`Window` > `Preferences`):
  - Set `Windows` theme (`General` > `Appearance`).
  - Make sure `Text Font` is set to `Consolas` (`General` > `Appearance` > `Colors and Fonts`).
  - Disable spell checking (`General` > `Editors` > `Text editors` > `Spelling`).
  - Change `Tab policy` to `Spaces only` in the currently used profile (`Java` > `Code Style` > `Formatter`).

### 7. Additional tools

- Download and install latest version of [Maven](https://maven.apache.org/).
