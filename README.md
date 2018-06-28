Javascript LinkedHashMap 
========

A utility that takes advantage on Javascript Object's power as a hashmap, and provide you insertion order.
Useful if you need to randomly access a value with a key, but need to know who are your immediate neighbours, ie. a carousel.

To test the function

```bash
docker pull node
THISFOLDER=/path/2/this/folder
# start interactive session
docker run --rm -it -v $THISFOLDER:/data node /bin/bash
```

once you're in cd into the mounted folder

```bash
root@81dd2f9c781a:~# cd /data
```

For the `import` function to work in the node REPL,
the `.js` extension has to be changed to `.mjs`.

including the js file in `src`

Additionally, node has to be run
with the `--experimental-modules`.

```
root@80dd2f9c791a:/data# node --experimental-modules test.mjs
(node:100) ExperimentalWarning: The ESM module loader is experimental.
[ 'a'  ]
```
