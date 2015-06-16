# experiment on clojurescript & cordova development

FIXME

## Prerequisites

You will need [boot][1] and [cordova][2] installed.

[1]: https://github.com/boot-clj/boot
[2]: https://www.npmjs.com/package/cordova

## Development

- www/: include resource files and home page.
- src/cljs/: include clojurescript source files.

## Running

```bash
#change resource or html files
cordova prepare

#change cljs files
boot dev

#browser open http://localhost:3000

```

## License

Copyright © 2015 chptx
