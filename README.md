# edn2transit / transit2edn

edn2transit reads edn and writes json+transit, transit2edn does the opposite.

Both scripts read from stdin and write to stdout

Requires [lumo](https://github.com/anmonteiro/lumo) installed

# Usage

```
$ echo '{:foo :bar}' | edn2transit
["^ ","~:foo","~:bar"]

$ echo '["^ ","~:foo","~:bar"]' | transit2edn
{:foo :bar}
```

# Installation

Copy the scripts to `/usr/local/bin`. You may need to use `sudo`.

# License

MIT

# Author

Paulus Esterhazy
