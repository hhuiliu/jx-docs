---
date: 2018-07-08T09:10:13Z
title: "jx get post"
slug: jx_get_post
url: /commands/jx_get_post/
---
## jx get post

Create a job which is triggered after a Preview is created

### Synopsis

Gets the jobs which are triggered after a Preview is created

```
jx get post preview job [flags]
```

### Examples

```
  # List the jobs triggered after a Preview is created
  jx get post preview job
```

### Options

```
  -b, --batch-mode   In batch mode the command never prompts for user input
      --headless     Enable headless operation if using browser automation
  -h, --help         help for post
      --no-brew      Disables the use of brew on MacOS to install or upgrade command line dependencies
      --verbose      Enable verbose logging
```

### SEE ALSO

* [jx get](/commands/jx_get/)	 - Display one or many resources

###### Auto generated by spf13/cobra on 8-Jul-2018
