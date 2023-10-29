# massren
rename multiple files using your favourite $EDITOR.

### usage

```
massren {files}
```

where `files` is zero or more file paths.
if no files are provided, then all files in the current directory are used.

there is no special functionality for selecting files.
shell globbing & piping should be used instead.

### deleting files
you can supply a deletion string with the `-d` flag. Any files renamed to this string will be deleted.
For example, use `massren -d '!' *.py` and change any lines to `!` and they will be deleted.
An empty string can be used as a deletion string.

### demo

<a href="https://asciinema.org/a/KSVcsdMwA3jVMIWLbUFF3961v" target="_blank"><img src="https://asciinema.org/a/KSVcsdMwA3jVMIWLbUFF3961v.svg" /></a>

