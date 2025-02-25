[`docs/`](./docs/) folder generated with:
```console
./inkwell/target/debug/inkwell generate content/ docs/
```

but I have to write the rest of this readme.

## By the way
The only reason I made [Inkwell](https://github.com/PolyLogic64/inkwell) a submodule, is because the source **is** in the [`inkwell/`](./inkwell/) folder. And not some separate repo I have to track as well. If I do any changes to Inkwell, I just do a `git add -A` and done. <sub>Well I don't know if that's the default behavior</sub>