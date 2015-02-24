# ~/bin

Storing here a part of my bin directory.

### Tools

#### ascii
Got tired of searching Google for ASCII tables. Calling it with no parameter shows a table of 7-bit ASCII. (Ruby)

Three parameter formats are accepted to get information about a specific character:
- 0x##: an hexadecimal ASCII value
- 0d##: a decimal ASCII value
- x: a single ASCII character

#### calc
Super cheap calc script. Passes the argument to Python's eval. (Python)

#### diff-summary
Short script which, when piped a diff, shows a summary of changes in number of lines and characters. Only tested with svn. (Bash)

#### ebnf
Quick Extended Backus-Naur Form (EBNF) syntax reference. Got tired of checking Wikipedia or a print of it. (Ruby puts)

#### ltable
LightTable launch script. Must unpack LightTable besides. (Bash)

#### md5diff
Directory diff utility. (Perl, md5sum)

#### svn-hist
SVN file history retriever. Shows all diffs for a file. Not from me, but still sometimes very handy. (Bash, svn)

#### timesheet
Calculates time durations from intervals in org-mode (self-designed) timesheet. (Perl)

#### top2
Gives quick overall CPU usage percentage. (Bash)

#### vcs-up
Script to update multiple repositories. Mainly used with svn so far. (Perl, svn, git)

The content of my .repos file is currently
```
~/Sandbox/*
```
which indicates to update all repositories in Sandbox. Any number of entries may be added. # will comment a line.
