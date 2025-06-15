# File Organizer

## Description

A simple Python tool to organize files in a directory into categorized folders (Documents, Images, Music, etc.).

## Installation

Just run:

```sh
pip install py-file-organizer
```

Or, to install locally from source:

```sh
pip install -e .
```

**Python 3.7+ required**

## Command line synopsis

```
Usage: file-organizer
```

You will be prompted to enter the directory path to organize.

**Options:**  
(None currently; interactive prompt only)

## Basic usage example

```sh
$ file-organizer
```

Running the above command will prompt you to enter the path of the directory you want to organize. All files in the specified directory will be moved into categorized folders (e.g., Documents, Images, Music, etc.) based on their file extensions.

## Using as a Python module

```python
from file_organizer import organize_files
organize_files('/path/to/your/directory')
```

## Pull requests are welcome

## TODO

- [ ] Add CLI options (e.g., dry-run, custom categories)
- [ ] Improve code structure

## License
MIT 
