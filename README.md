This repository applies a fix by `manthrax`[^fix] to `bgrins`'s original A-star library[^original], allowing `Graph` instances to be re-used, resulting in a major performance improvement for cases where caching is feasible, especially for large graphs!

The original read-me can be found here: https://github.com/tukkek/a-star/blob/master/README.bgrins.md

[^fix]: *Pathing randomly fails after first search*. https://github.com/bgrins/javascript-astar/issues/52.
[^original]: `javascript-astar `. https://github.com/bgrins/javascript-astar
