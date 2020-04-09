# Yo New Jersey!

Jersey boys don't write "hello, world!"

A proof of concept in COBOL.

Thanks to Matt Aimonetti for reminding me how easy programming is.

# Setup

You'll need gnu-cobol to compile from source.

On MacOS with [Homebrew](https://brew.sh), you can do the following:

```shell
brew install gnu-cobol
```

On Ubuntu Linux, assuming you have build-essential already installed, it's:

```shell
sudo apt-get install gnucobol
```

# Compile

For your convenience, there is a `Makefile`.

Just `make` at the command line.

The runnable binary will appear in `bin/`.

## Running

```shell
bin/yo_new_jersey
```
