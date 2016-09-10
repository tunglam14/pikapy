Pikabin Python Client
=====================

```bash
$ ./pika.py -h
Usage: echo "blah blah" | pika.py [options]

Options:
  -h, --help            show this help message and exit
  -e EXPIRED_AT, --expired-at=EXPIRED_AT
                        Set expiration, in minute
  -s SYNTAX, --syntax=SYNTAX
                        Coloring syntax, see more: http://goo.gl/nLFqyB
  -t TITLE, --title=TITLE
                        Title
```

Usage
-----

Read from stdin.

Full options:

```bash
$ cat pika.py |./pika.py -t Test -e -1 -s python
https://pikab.in/8f3a69166d101536741542fafd2c0fd71e829
```

Simple:

```bash
$ cat pika.py |./pika.py
https://pikab.in/8f3a69166d101536741542fafd2c0fd71e829
```
