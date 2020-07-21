**TransPlug**
=============

**I have no time to develop this plugin, so feel free to send pull request to this repo! :)**

Removed requirement to prefix language files with "locale-"

**TransPlug** is a simple plugin for JetBrains IDE (PhpStorm, WebStorm etc.)
It provides easy way to manage translation files in your project.

How to use
--
1. Prepare translation files. All translations must be in one dir with **nothing else in that dir** except translations. Filename should be like `hereLangCode.json` for example `en.json`
2. Install plugin from JetBrains plugin repository.
3. To open plugin window use key shortcut `ctrl+alt+shift+k`, or click on tab on bottom of the screen.
4. Click `settings` button and pass path for dir with translations (relative to project root).
5. Enjoy!

Features
--
* JSON files support
* All translations shown in readable table
* Incomplete translations are marked
* Translation can be added and edited

Known issues
--
* Plugin doesn't work properly when IDE has opened more then one project
