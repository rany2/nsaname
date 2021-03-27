# nsaname

Like petname, but for naming secret projects and tools. Same as https://github.com/rbanffy/nsaname except written in Bash

# Usage

```
$ nsaname --help
nsaname [options]
  --help           Show this help page.
  -l, --lowercase  Output in lowercase.
  -m, --no-suffix  Don't add a suffix.
  -h, --hostname   Output a sensible hostname.

$ nsaname
MaestroGhostly 9000

$ nsaname
DropoutRed 2.0

$ nsaname -l
baldscribbles ii

$ nsaname -m 
WildBank

$ nsaname -h
cut-eagle

$ nsaname -h
howler-birds
```
