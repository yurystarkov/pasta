# `pasta`

Just specify the pastebin service of choice as your first argument
and a file to share as the second. Or you can send standard
input without specifying any file.

You can change user agent used by `curl` by changing the `PASTA_UA`
variable.

Also `pasta` keeps history in a `~/.pasta_history`. Change it by
setting `PASTA_LOG` to something else. Or disable it by setting it
to `/dev/null`.
