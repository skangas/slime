SLY News
--------

## SLY 1.0-Alpha (21-08-2014)

### On par with SLIME 2.9

### Completely redesigned REPL (sly-mrepl)

### Regexp-capable M-x sly-apropos

### More consistent interface with buttons

### Multiple inspectors (TODO)

### Uses ASDF to load contribs by default

### Merged outstanding SLIME pull requests

  https://github.com/slime/slime/pull/175
  https://github.com/slime/slime/pull/145

### Other miscelaneous enhancements over SLIME

Faces have been revised.

SLY is intrudes less than SLIME in the Emacs namespace, and uses more
standard idoms. Macros like `with-struct` and `sly-define-keys` have
been removed.

Buffer names have been consolidated: every buffer name related to SLY
obeys the same structure, stating the type, connection name and any
pertinent additional info.







