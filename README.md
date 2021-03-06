# quntoken

New Hungarian tokenizer based on quex and huntoken.
This tool is also [integrated](https://github.com/dlt-rilmta/hunlp-GATE)
into the [e-magyar](http://www.e-magyar.hu) language processing system
under the name [emToken](http://e-magyar.hu/hu/textmodules/emtoken).

## Requirements

* linux
* python 2.x as default python
* python 3.x
* g++ >= 4.8.2

## Install

```
git clone https://github.com/dlt-rilmta/quntoken.git
cd quntoken
make prereq
make all
```

## Usage

```
./quntoken [OPTIONS] [-f FORMAT] FILE
```
### Options

* -d: Remove division of words at the end of the lines.
* -f: Define output format. Valid formats: xml, json. Default format: xml.
* -V: Display version number and exit.
* -h: Display help and exit.

