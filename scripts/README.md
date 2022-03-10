# json rewriter
`rewrite.lua` will rewrite `db.json` into a lua file `db.lua`, which will just return the entire json in the file

## Notes
- designed only for mime-db's json file
- if `db.lua` exists the process will fail, please remove per successful run
