# pasta

Just specify pastebin service of choice as your first argument and
file to share as the second. Otherwise you can send standard input
without specifying input file.

You can change user agent used by curl by changing the `PASTA_UA`
variable.

Also `pasta` keeps a log of links in file difined by `PASTA_LOG`.
You can change it to your liking or disable it by setting the
variable to `/dev/null`.
