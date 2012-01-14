smvn
====

Execute Maven commands from sub directories of Maven projects.

When executing Maven commands that require the POM (most do), you
normally need to change to the directory that contains the pom.xml
file, or specify the `-f` option.

With smvn, you can execute Maven commands from any sub directory of
your project, it will find the POM for you.

Installation
------------

[Download the script](https://raw.github.com/fhd/smvn/master/smvn),
put in on your `$PATH` and make it executable.

    cd ~/bin
    wget https://raw.github.com/fhd/smvn/master/smvn
    chmod +x smvn

Usage
-----

Just execute Maven commands like you normally would, using `smvn`
instead of `mvn`.
