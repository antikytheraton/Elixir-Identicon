# Identicon

## Pipeline

* String
=>
* Compute MD5 hash of string
=>
* List of numbers based on the string
=>
* Pick color
=>
* Build grid of squares
=>
* Convert grid into image
=>
* Save Image

## How to run

```bash
$ iex -S mix

iex(1)> Identicon.main("asdf")
:ok
```