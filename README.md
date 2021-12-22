# micropython-wasm

MicroPython for browser and node (WIP), powered by WebAssembly

## About MicroPython

Official Repo [https://github.com/micropython/micropython/tree/master/ports/javascript][0]

MicroPython implements the entire Python 3.4 syntax (including exceptions,
`with`, `yield from`, etc., and additionally `async`/`await` keywords from
Python 3.5). The following core datatypes are provided: `str` (including
basic Unicode support), `bytes`, `bytearray`, `tuple`, `list`, `dict`, `set`,
`frozenset`, `array.array`, `collections.namedtuple`, classes and instances.
Builtin modules include `sys`, `time`, and `struct`, etc. Select ports have
support for `_thread` module (multithreading). Note that only a subset of
Python 3 functionality is implemented for the data types and modules.


[0]: https://github.com/micropython/micropython/tree/master/ports/javascript
