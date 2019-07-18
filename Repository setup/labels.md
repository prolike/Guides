# Label setup

**CONSTRAINT**
You need to have [GHI](https://github.com/stephencelis/ghi) installed

Download and run the following two scripts from the command line, while your current directory is in the root of the repository you mand to manipulate.

1. **Clean default GitHub labels** by running [`rm-gh-defaults.sh`](https://github.com/lakruzz/the-phlow/blob/master/rm-gh-defaults.sh) You can run it with `--help` to learn exactly what it's doing. It's save to run - it will not delete labels if they are in use
2. **Create the phlow labels** by running [`mk-phlow-defaults.sh`](https://github.com/lakruzz/the-phlow/blob/master/mk-phlow-defaults.sh) You can run it with `--help` to learn exactly what it's doing.

## Pro tip!
On Linux (or Linux-like environments such as Mac, GitBash) simply run:

```
 bash <(curl -s https://raw.githubusercontent.com/lakruzz/the-phlow/master/rm-gh-defaults.sh)
 bash <(curl -s https://raw.githubusercontent.com/lakruzz/the-phlow/master/mk-phlow-defaults.sh)
```

