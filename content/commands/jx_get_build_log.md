---
date: 2018-07-08T09:10:13Z
title: "jx get build log"
slug: jx_get_build_log
url: /commands/jx_get_build_log/
---
## jx get build log

Display a build log

### Synopsis

Display the git server URLs.

```
jx get build log [flags]
```

### Examples

```
  # List all registered git server URLs
  jx get git
```

### Options

```
  -b, --build int       The build number to view
  -f, --filter string   Filters all the available jobs by those that contain the given text
  -h, --help            help for log
  -t, --tail            Tails the build log to the current terminal (default true)
```

### SEE ALSO

* [jx get build](/commands/jx_get_build/)	 - Display one or many build resources

###### Auto generated by spf13/cobra on 8-Jul-2018
