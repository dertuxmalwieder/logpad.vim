# logpad.vim

That one Notepad feature - for Vim.

## Huh?

A couple of years ago, I wrote a plug-in that would allow me to use Microsoft's [Notepad logging](https://www.howtogeek.com/258545/how-to-use-notepad-to-create-a-dated-log-or-journal-file/) from inside Vim. This is it.

## Usage

Create a new file, write .LOG as the first line and save it. Every time you reopen the file, a new line with the current timestamp is added, so you can easily maintain a chronologic log of your tasks.

By default, this plugin works the same way as the original Notepad. You can modify certain aspects of it by setting the following variables:

`let LogpadEnabled = [ 0 / 1 ]`
* enables/disables logpad
* default value: 1

`let LogpadInsert = [ 0 / 1 ]`
* automatically enables &insertmode when a new log entry is created
* default value: 0

`let LogpadLineBreak = [ 0 / 1 ]`
* adds an empty line before a new log entry
* default value: 0 (Windows Notepad behavior)

`let LogpadIgnoreNotes = [ 0 / 1 ]`
* allows adding notes before the first log entry
* default value: 0

`let LogpadIgnoreReadOnly = [ 0 / 1 ]`
* allows logpad to ignore a file's read-only flag
* default value: 0
 
## Installation

Download the `logpad.vim` file. Put it into your plugins directory. Use a package manager of your choice to load it.

## Donations (optional)

`logpad.vim` is free software by the terms of the [WTFPL](http://www.wtfpl.net/txt/copying/). As some people - including myself - like to contribute money for a good cause anyway, here are two possible options for you:

### Donate money to the nature:

Both [Kākāpō Recovery](http://kakaporecovery.org.nz/) and the [WWF](https://support.wwf.org.uk/adopt-a-panda) do a pretty good job at trying to keep species alive. You are invited to join their efforts.

### Donate money to me:

Yes, I like money as well.

[![Support via PayPal](https://cdn.rawgit.com/twolfson/paypal-github-button/1.0.0/dist/button.svg)](https://www.paypal.me/GebtmireuerGeld/)
