## Mac OS


### Emacs

(1) Build [emacs-mac-port](https://github.com/railwaycat/emacs-mac-port)  

```
$ git clone git://github.com/railwaycat/emacs-mac-port.git
$ brew install autoconf automake libtool
$ ./configure --with-mac --enable-mac-app
$ make && make install
```

### Keys

- [replace Capslock to Escape](http://stackoverflow.com/questions/127591/using-caps-lock-as-esc-in-mac-os-x)