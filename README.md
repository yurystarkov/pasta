# pasta

Just specify the pastebin service of choice as your first argument
and a file to share as the second. Or you can send standard input
without specifying any file.

You can change user agent used by `curl` by changing the `PASTA_UA`
variable.

Also `pasta` keeps history in a `~/.pasta_history`. Change the file
location by setting `PASTA_LOG` to something else. Or disable history
by setting `PASTA_LOG` to `/dev/null`.

If you don't want to download this script you can put the
following function in your `$SHELL`'s config:

```bash
pasta() {
  curl https://raw.githubusercontent.com/yurystarkov/pasta/main/pasta |
    sh /dev/stdin "$1" "$2"
}
```

Currently supported services:

- [0x0](https://0x0.st)
- [catbox](https://catbox.moe)
- [clbin](https://clbin.com)
- [dmca](http://dmca.gripe)
- [dumpz](https://dumpz.org)
- [iotek](https://iotek.org)
- [ix](http://ix.io)
- [lewd](https://lewd.se)
- [sprunge](http://sprunge.us)
- [termbin](https://termbin.com)
- [ttm](https://ttm.sh)
- [uguu](https://uguu.se)
