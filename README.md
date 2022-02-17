# HiddenWave
Embedding secret messages in a wave audio file

# What is HiddenWave
Hiddenwave is a python based program for simple audio steganography. You can hide your secret text messages in wave audio file. you can play this audio in any media player and secretly share your private message with any one.

# Requirements
<p>This tool requires python</p>

## Installation

```
git clone https://github.com/a-bhaleghare/HiddenWave-IA-1.git
```
## Usage
<p>Hiddenwave have two python scripts. </p>
<ul>
<li><b>HiddenWave.py :</b> To hide secret information.</li>
<li><b>ExWave.py :</b> To extract secret information from wave audio file.</li>
</ul>

### Hide Secret Information in Audio file

```
python HiddenWave.py -f IA1_CSS_HELLO.wav -m "Hello, Aagman and Aditya here" -o output.wav
```
### Extract Secret Information from Audio file

```
python ExWave.py -f output.wav
```
