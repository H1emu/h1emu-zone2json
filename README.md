# h1emu-zone2json

Based on https://github.com/psemu/forgelight-zone

Read and write .zone files for H1emu

# Installing

`npm install`

# Usage

`node zonetool.js <mode> <inPath> [<outPath>]`

| Mode    | Description                                 |
| ------- | ------------------------------------------- |
| `json`  | Export Zone data to JSON                    |
| `info`  | Print general information about Zone data   |
| `write` | Write JSON data to .zone file               |
| `test`  | Test tool integrity on zone file `<inpath>` |
