# interactor-executorch-tiling

A demo that exports one dynamic-shape model to an on-device inference runtime and runs it on the CPU over image tiles of varying size.

## What it is for

It shows that a single exported model, given bounds on its input height and width, handles a full image and every edge tile without padding and without a model per tile size. The demo times the exported model against eager execution of the same network and compares their outputs.

## Build and run

```sh
just install
just run
```

## Licence

There is no licence file, and the licence is not stated.
