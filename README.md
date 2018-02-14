[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/ngs-docs/ggg-shell-genomics-ws/master)

# Shell genomics lesson from Data Carpentry

This repository contains the data needed for the first four lessons
from the [Data Carpentry Genomics workshop](http://www.datacarpentry.org/shell-genomics/).

[Introduction](http://www.datacarpentry.org/shell-genomics/01-introduction/)

[The file system](http://www.datacarpentry.org/shell-genomics/02-the-filesystem/)

[Working with files](http://www.datacarpentry.org/shell-genomics/03-working-with-files/)

[Redirection](http://www.datacarpentry.org/shell-genomics/04-redirection/)

## Getting the data yourself

Go to https://osf.io/ycu8j/files/, select `dc_sample_data`, and click
'Download as zip'.  Then unpack the zip in your home directory.

Alternatively, e.g. on a Jetstream instance, do:

```
git clone https://github.com/ngs-docs/ggg-shell-genomics-ws.git
mv ggg-shell-genomics-ws.git/{*,.??*} .
```

or

```
curl -L -O https://github.com/ngs-docs/ggg-shell-genomics-ws/archive/master.zip
unzip master.zip
mv ggg-shell-genomics-ws.git/{*,.??*} .
```
