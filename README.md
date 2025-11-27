# Python environment - quick setup

Quickly setup Python environments using uv for rapit prototyping and development.

Provides a `pyproject.toml` "ready to go" with a bunch of commonly used dependencies.


## Usage

Clone this repo somewhere, make sure you have [uv] installed, then run:

    uv sync --extra={repl,test,datasci,hacking,tools}

(Adjust the list of "extras" according to your needs).

Or just use: `uv sync --all-extras` to install all extras at once.


[uv]: https://docs.astral.sh/uv/getting-started/installation/


## Included dependency groups

- **repl**: IPython and stuff
- **test**: pytest plus various plugins
- **datasci**: data science stuff (numpy, pandas, ...)
- **hacking**: hacking and security related tools: pwntools, scapy, ...
- **tools**: useful libraries for building tools
- **filefmts**: libraries to access file formats
