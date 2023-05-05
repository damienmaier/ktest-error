# ktest-error

This script calls the Klee 'ktest-tool' command on each test that resulted in an error.

## Installation

Clone this repo, cd into it and then run

```
pip install .
```

## Usage

```
ktest-error <directory>
```

Where \<directory\> is the `klee-out-N` directory where Klee has outputted its tests.
