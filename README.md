# cmus-lyrics
**cmus-lyrics** is a simple bash script that fetches the lyrics of current song playing in [CMus] (C* Music Player).


### Dependencies :
- Perl - [Perl] (Practical Extraction and Reporting Language) originally developed by Larry Wall is a family of high-level, general-purpose, interpreted, dynamic programming languages. `Perl` is available in repositories of almost every Linux distribution under the sun. Use your distribution's package manager to install it. Perl Module [URI::Escape] is also needed.

- Wget - [Wget] is a free software package for retrieving files using HTTP, HTTPS and FTP, the most widely-used Internet protocols. Most Linux distributions have Wget in their package repositories so you can easily install `Wget` via the package manager of your distribution in case it is not installed on your system.


### Installation :
Very easy.

Obtain sudo privileges and download [cmus-lyrics-master.zip],

```sh
sudo -s
wget --content-disposition https://github.com/hakerdefo/cmus-lyrics/archive/master.zip
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


### Bonus :
You can enable a few more lyrics providers by installing following optional dependencies,
- curl - [curl] is a tool to transfer data from or to a server, using one of the supported protocols (DICT, FILE, FTP, FTPS, GOPHER, HTTP, HTTPS, IMAP, IMAPS, LDAP, LDAPS, POP3, POP3S, RTMP, RTSP, SCP, SFTP, SMB, SMBS, SMTP, SMTPS, TELNET and TFTP). `curl` is available in repositories of almost every linux distribution. You can easily install it from your package manager.

- jq - [jq] is like sed for JSON data. You can use jq to slice and filter and map and transform structured data with the same ease that sed, awk, grep and friends let you play with text. `jq` is available in the repositories of Debian, Ubuntu, Fedora, openSUSE, Arch (AUR), FreeBSD (FreshPorts), Solaris (OpenCSW), OS X (Homebrew). Linux and OS X binaries are also available from the Download section of jq website. If you decide to use the jq binary directly from the jq website you will have to rename it after downloading from `jq-linux64` or `jq-linux32` to simply `jq`. In case of OS X rename it to `jq` from `jq-osx-amd64`.

- Glyr - [Glyr] is a search engine for music related metadata. It comes as a command-line interface tool & a C library. **cmus-lyrics** requires glyrc, which is the command-line interface to libglyr. You can install `glyrc` via your package manager. If your distribution doesn't have it in its repository, you can compile it your self following this [instructions].


### Support :
If you like **cmus-lyrics**, please consider supporting it, even the smallest contribution goes a long way. It is easy & quick via Coindrop,  
<a href="https://coindrop.to/hakerdefo" target="_blank"><img src="https://coindrop.to/embed-button.png" style="border-radius: 10px;" alt="Coindrop.to me" style="height: 57px !important;width: 229px !important;" ></a>


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
[curl]:http://curl.haxx.se
[jq]:https://stedolan.github.io/jq/
[Glyr]:https://github.com/sahib/glyr
[instructions]:https://github.com/sahib/glyr/wiki/Compiling
[Federico Builes]:https://github.com/febuiles
[makeitpersonal]:https://github.com/febuiles/makeitpersonal
