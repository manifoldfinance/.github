---
title: ${ORG} Container Images
description: ${REPO}
version: v.0.1.0
---


# {{ title }}

{{ > Overview }}


### Supported tags and respective `Dockerfile` links

#{range $_, $v := .Versions}

#### #{$v.Version}

`#{range $_, $b := $v.Builds}`

 * `#{$b.Tag}`#{range $_, $t := $b.Base.AdditionalTags}, `#{$t}`#{end} [(#{$b.Base.Base}/Dockerfile)]($URL/#{$b.Base.Base}/Dockerfile)
#{end}#{end}

## API

Note: unlike `realpath(1)`, these functions take no options; **do not** use `--` to escape any arguments

| Function                          | Description
| --------------------------------- | -------------
| <pre>{{ container.Function}} </pre>          | {{ container.Description }}
| <pre>shell $PATH</pre>  | If `PATH` is a symlink, container `cli`
| <pre>mount:Volume</pre> | Mount file system to absolute path that `PATH` refers to, resolving any relative directories (`.`, `..`) in `PATH` and any symlinks in `PATH`'s ancestor directories



