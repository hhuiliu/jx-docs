---
date: 2018-07-08T09:10:13Z
title: "jx delete chat token"
slug: jx_delete_chat_token
url: /commands/jx_delete_chat_token/
---
## jx delete chat token

Deletes one or more api tokens for a user on a chat server

### Synopsis

Deletes one or more API tokens for your chat server from your local settings

```
jx delete chat token [flags]
```

### Examples

```
  # Deletes a chat user token
  jx delete chat token -n slack myusername
```

### Options

```
  -h, --help          help for token
  -n, --name string   The name of the git server to add a user
  -u, --url string    The URL of the git server to add a user
```

### SEE ALSO

* [jx delete chat](/commands/jx_delete_chat/)	 - Deletes one or many chat services resources

###### Auto generated by spf13/cobra on 8-Jul-2018
