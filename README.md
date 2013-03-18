genm3u
=======

A node application to generate a m3u to the console given a directory full of media.


```
Usage: /Users/neal/bin/genm3u <-h|selector regex> [directory (assumes cwd)]
```

'selector regex' if specified, will filter the results by the given javascript regex.



==
genm3u relies on node-walk (https://github.com/coolaj86/node-walk)
```
npm install walk
```

