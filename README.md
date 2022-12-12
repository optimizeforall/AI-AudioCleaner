
# Overview

Cleanaudio is a simple python script that implements [audoai](https://github.com/audo-ai/audoai-python) to clean multiple audio files at once.

It can clean multiple files at once, once cleaned, it creates a copy of file in the same directory with '_cleaned' added to the name of the file.


# Usage

```
cleanaudio ~/Downloads/1.wav ~/Downloads/2.wav ~/Downloads/3.wav
```


# Installation

1. Ensure you have python3 installed
2. pip3 install --upgrade audoai-noise-removal
3. Download cleanaudio
4. cd cleanaudio
5. chmod +x cleanaudio
6. Add cleanaudio to your path
   1. Add `export PATH=$PATH:/path/to/cleanaudio` to your .bashrc or .zshrc

Enjoy! :)