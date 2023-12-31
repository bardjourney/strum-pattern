# strum-pattern

Utility to generate common strumming diagrams for both guitars and ukuleles.

## System Requirements

* A recent [LilyPond](http://lilypond.org/)
* A recent [Ruby](https://www.ruby-lang.org/)

## Usage

Invoke the following command to generate its strumming diagram:

```shell
$ strum-pattern D-DU-_U-DU
```

You will get *D-DU-_U-DU.png* in your working directory.

## Strumming Notation

* `D-D-D-D`
* `D-D-DU-DU`
* `RU-RU-RU-RU` (rest)
* `D-D-D-_` (half note)
* `D_DU-DU-D_DU-DU` (sixteenth note)
* `D-DU-_U-DU` (tie)
* `D_U-D_U-D_U-D_U` (swing)

## Command-Line Parameters

* `-v` or `--version` to show version info and exit
* `-h` or `--help` to show help message and exit
* `-o` or `--output` to specify the output file name
* `-s` or `--size` to specify the size of a fretboard diagram
* `-ly` or `--lilypond` to generate the corresponding LilyPond code instead

## Limitation

To simplify its usage, the program merely support common strumming patterns. If you want something more complex, generate its LilyPond code for further modification by yourself.

## Contribute

Welcome to package the program into some installable format like a Chocolatey package or a Homebrew package.

Other contributions are welcome as well.

## Copyright

The program itself is licensed under MIT.

You keep your own strumming diagrams or LilyPond code generated by the program in any license you prefer.
