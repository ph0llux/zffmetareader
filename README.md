> This repository is archived. The tool has been completely reworked in the meantime and now has a different name - the reworked variant is now called zffanalyze and can be found at https://github.com/ph0llux/zffanalyze.

# zffmetareader

```zffmetareader``` is a command line utility to read the metadata of a zff image.

# Installation
## Prerequisites
First, you need to [install rust and cargo](https://rustup.rs/) to build or install ```zffmetareader```.

After that you still need the gcc, which you can install as follows (depends on the distribution):
###### Debian/Ubuntu
```bash
$ sudo apt-get install gcc
```
###### Fedora
```bash
$ sudo dnf install gcc
```

Then you can easily build this tool yourself by using cargo:
```bash
[/home/ph0llux/projects/zffmetareader] $ cargo build --release
```
Or you can install the tool directly from crates.io:
```bash
$ cargo install zffmetareader
```

# Usage

Use ```zffmetareader -i <YOUR_ZFF_IMAGE.z01>``` to read the metadata of a zff file.
