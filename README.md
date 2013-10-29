# bin-scripts #

## Description ##

A bunch of scripts devoted to doing generic file parsing and such.

## Examples ##

* Open all included files in Notepad++:

```sh
$ get_includes main.c | findin "C:/" | nppopen
```

* Find common parent directory for all included files

```sh
$ get_includes main.c | findin "C:/" | common_parent
```
