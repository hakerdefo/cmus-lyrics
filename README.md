# cmus-lyrics
cmus-lyrics is a simple bash script that fetches the lyrics of current song playing in cmus music player.


### Dependencies :
- Perl - Perl (Practical Extraction and Reporting Language) originally developed by Larry Wall is a family of high-level, general-purpose, interpreted, dynamic programming languages. [Perl] is available in repositories of almost every Linux distribution under the sun. Use your distribution's package manager to install it. Perl Module [URI::Escape] is needed.
- Wget - [Wget] is a free software package for retrieving files using HTTP, HTTPS and FTP, the most widely-used Internet
protocols. Most Linux distributions have Wget in their package repositories so you can easily install Wget via the package manager of your distribution in case it is not installed on your system.


### Installation :
Very easy.
 
Download [cmus-lyrics-master.zip]
 ```sh
$ sudo -s
$ cd /usr/local/bin
$ wget https://github.com/hakerdefo/cmus-lyrics/archive/master.zip
```
Extract it
```sh
$ unzip master.zip
```
Make it executable, and drop sudo privileges
```sh
$ chmod a+x cmus-lyrics-master
$ exit
```


### Usage :
Run cmus-lyrics and it will fetch and print lyrics of the song currently playing in [cmus] music player.


### Credits :
[Federico Builes] - cmus-lyrics wouldn't have been possible without wonderful [makeitpersonal] created by Federico.


### License :
[![Public Domain Mark](http://i.creativecommons.org/p/mark/1.0/88x31.png)](http://creativecommons.org/publicdomain/mark/1.0/)  
This work (<span property="dct:title">cmus-lyrics</span>, by [<span property="dct:title">hakerdefo</span>](https://github.com/hakerdefo/cmus-lyrics)), identified by [<span property="dct:title">hakerdefo</span>](https://hakerdefo.blogspot.com), is free of known copyright restrictions.

[perl]:https://www.perl.org
[URI::Escape]:http://search.cpan.org/dist/URI/lib/URI/Escape.pm
[Wget]:https://www.gnu.org/software/wget/
[cmus-lyrics-master.zip]:https://github.com/hakerdefo/cmus-lyrics/archive/master.zip
[cmus]:https://cmus.github.io
[Federico Builes]:https://github.com/febuiles
[makeitpersonal]:https://github.com/febuiles/makeitpersonal
