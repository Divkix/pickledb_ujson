<p align="center">
<a href="https://pypi.org/project/pickledb-ujson/"><img src="https://img.shields.io/pypi/v/pickledb-ujson" alt="PyPI"></a>
<a href="https://github.com/Divkix/pickledb_ujson/actions"><img src="https://github.com/Divkix/pickledb_ujson/workflows/CI%20%28pip%29/badge.svg" alt="CI (pip)"></a>
<a href="https://pypi.org/project/pickledb-ujson/"><img src="https://img.shields.io/pypi/pyversions/pickledb-ujson.svg" alt="Supported Python Versions"></a>
<a href="https://pepy.tech/project/pickledb-ujson"><img src="https://pepy.tech/badge/pickledb-ujson" alt="Downloads"></a>
</p>

# pickleDB
pickleDB is lightweight, fast, and simple database based on the
[ujson](https://github.com/ultrajson/ultrajson) module.
And it's BSD licensed!


## pickleDB is Fun
```python
>>> import pickledb_ujson as pickledb

>>> db = pickledb.load('test.db', False)

>>> db.set('key', 'value')

>>> db.get('key')
'value'

>>> db.dump()
True
```

## Easy to Install
```python
$ pip install pickledb-ujson
```

## Links
* [website](https://patx.github.io/pickledb)
* [documentation](https://patx.github.io/pickledb/commands.html)
* [pypi](http://pypi.python.org/pypi/pickledb_ujson)
* [github repo](https://github.com/divkix/pickledb_ujson)
