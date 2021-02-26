
This is a repo showing how to use [ReScript](https://github.com/rescript-lang/rescript-compiler) with 
[Deno](https://deno.land/#installation).

It assumes you are already familiar with both.

# Build
```
./node_modules/bs-platform/bsb -w # build and watch
```
# Run

```
deno run ./lib/es6_global/src/demo.js
```

Note here we only use npm as a downloader, you don't have to use npm, you can just grab the package from npmjs.com and put it in
`node_modules` directory