# My scoop bucket

[![Tests](https://github.com/Trevrosa/mybucket/actions/workflows/ci.yml/badge.svg)](https://github.com/Trevrosa/mybucket/actions/workflows/ci.yml) [![Excavator](https://github.com/Trevrosa/mybucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/Trevrosa/mybucket/actions/workflows/excavator.yml)

My bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add <bucketname> https://github.com/<username>/<bucketname>
scoop install <bucketname>/<manifestname>
```
