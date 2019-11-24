# ssb-bin

ssb cli client commands

if you understand [minimist](https://github.com/substack/minimist) syntax,
you can call the same things you could from javascript (via muxrpc)

see also [ssb-cli](https://github.com/fraction/ssb-cli)

## example

```
npm install ssb-bin -g

ssb publish --type post --text 'hello world!'
ssb query.read --filter[0]\$filter.value.content.channel=solarpunk
```

you can do any ssb command that you could do with javascript and muxrpc,
because minimist is equivalent to json, but follows traditional unix command line conventions.

## License

MIT
