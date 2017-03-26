# cmus-lyrics
**cmus-lyrics** is a simple bash script that fetches the lyrics of current song playing in [CMus] (C* Music Player).


### Dependencies :
- Perl - Perl (Practical Extraction and Reporting Language) originally developed by Larry Wall is a family of high-level, general-purpose, interpreted, dynamic programming languages. [Perl] is available in repositories of almost every Linux distribution under the sun. Use your distribution's package manager to install it. Perl Module [URI::Escape] is needed.
- Wget - [Wget] is a free software package for retrieving files using HTTP, HTTPS and FTP, the most widely-used Internet
protocols. Most Linux distributions have Wget in their package repositories so you can easily install Wget via the package manager of your distribution in case it is not installed on your system.


### Installation :
Very easy.

Obtain sudo privileges and download [cmus-lyrics-master.zip],

```sh
sudo -s
wget https://github.com/hakerdefo/cmus-lyrics/archive/master.zip
```

Extract it,

```sh
unzip cmus-lyrics-master.zip
```

Make **cmus-lyrics** executable and copy it to **/usr/local/bin/** directory,

 ```sh
chmod 755 cmus-lyrics-master/cmus-lyrics
cp cmus-lyrics-master/cmus-lyrics /usr/local/bin/
```

And finally clean up the leftovers and drop sudo privileges,

```sh
rm cmus-lyrics-master.zip
rm -rf cmus-lyrics-master/
exit
```


### Usage :
Run **cmus-lyrics** and it will fetch and print lyrics of the song currently playing in CMus.


### Credits :
_[Federico Builes] - cmus-lyrics wouldn't have been possible without wonderful [makeitpersonal] created by him._


### License :
[![Public Domain Mark](http://i.creativecommons.org/p/mark/1.0/88x31.png)](http://creativecommons.org/publicdomain/mark/1.0/)  
This work (<span property="dct:title">cmus-lyrics</span>, by [<span property="dct:title">hakerdefo</span>](https://github.com/hakerdefo/cmus-lyrics)), identified by [<span property="dct:title">hakerdefo</span>](https://hakerdefo.blogspot.com), is free of known copyright restrictions.

[perl]:https://www.perl.org
[URI::Escape]:http://search.cpan.org/dist/URI/lib/URI/Escape.pm
[Wget]:https://www.gnu.org/software/wget/
[cmus-lyrics-master.zip]:https://github.com/hakerdefo/cmus-lyrics/archive/master.zip
[CMus]:https://cmus.github.io
[Federico Builes]:https://github.com/febuiles
[makeitpersonal]:https://github.com/febuiles/makeitpersonal
