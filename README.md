# scoop-bucket

[![Excavator](https://github.com/kettlehead1/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/kettlehead1/scoop-bucket/actions/workflows/excavator.yml)

Personal bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## Installation

```powershell
scoop bucket add kettlehead1 https://github.com/kettlehead1/scoop-bucket
scoop install kettlehead1/paq8px
```

## Apps

| App | Description |
| --- | --- |
| [paq8px](https://github.com/hxim/paq8px) | Experimental lossless data compressor and entropy estimator (command line, portable) |

Versions are updated automatically: the `Excavator` workflow runs `checkver` once a day and commits new manifest versions.

## Adding a new app

1. Create `bucket/<name>.json` with `checkver` and `autoupdate` fields.
2. Commit and push.
