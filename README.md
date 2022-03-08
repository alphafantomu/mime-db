# mime-db
bad port of nodejs mime-db in lua

## Installation
- Make sure you have [luvit](https://luvit.io/install.html) installed
- Run the command `lit install alphafantomu/mime-db`
- `require('mime-db')` to reference the library

- There is no [LuaRocks](https://luarocks.org/) release, but only `init.lua` and `db.json` is necessary to use the library.

## Documentation
Considered a bad port of nodejs mime-db as this library doesnt have any database building capabilities, currently parses a local copy of `db.json` taken from [mime-db](https://github.com/jshttp/mime-db/blob/master/db.json) with `luv` reading the file and `json` parsing the body. In the feature, a full port would be nice but I don't have the time.

## License
This project has an [MIT license](/LICENSE)

## Contact
- Discord: `Arivistraliavatoriar#2678`
