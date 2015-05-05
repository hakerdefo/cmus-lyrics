# cmus-lyrics
cmus-lyrics is a simple bash script that fetches the lyrics of current song playing in cmus music player.


### Dependencies :
- Perl - Perl (Practical Extraction and Reporting Language) originally developed by Larry Wall is a family of high-level, general-purpose, interpreted, dynamic programming languages. [Perl] is available in repositories of almost every Linux distribution under the sun. Use your distribution's package manager to install it.
- curl - [curl] is a command line tool and library for transferring data with URL syntax. curl is available in repositories of almost every Linux distribution so you can install curl easily via your package manager.


### Installation :
Very easy. Download [cmus-lyrics-master.zip], extract it, and simply copy 'cmus-lyrics' file to '/usr/local/bin/' directory,
 ```sh
$ sudo cp cmus-lyrics /usr/local/bin/
```
Next make it executable,
```sh
$ sudo chmod a+x /usr/local/bin/cmus-lyrics
```


### Usage :
Run cmus-lyrics and it will fetch and print lyrics of the song currently playing in [cmus] music player.


### Credits :
[Federico Builes] - cmus-lyrics wouldn't have been possible without wonderful [makeitpersonal] created by Federico.


### License :
[![Public Domain Mark](http://i.creativecommons.org/p/mark/1.0/88x31.png)](http://creativecommons.org/publicdomain/mark/1.0/)  
This work (<span property="dct:title">cmus-lyrics</span>, by [<span property="dct:title">hakerdefo</span>](https://github.com/hakerdefo/cmus-lyrics)), identified by [<span property="dct:title">hakerdefo</span>](https://hakerdefo.blogspot.com), is free of known copyright restrictions.

[perl]:https://www.perl.org
[curl]:http://curl.haxx.se
[cmus-lyrics-master.zip]:https://github.com/hakerdefo/cmus-lyrics/archive/master.zip
[cmus]:https://cmus.github.io
[Federico Builes]:https://github.com/febuiles
[makeitpersonal]:https://github.com/febuiles/makeitpersonal
