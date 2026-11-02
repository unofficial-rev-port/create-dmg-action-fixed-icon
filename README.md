# create-dmg-action-fixed-icon

Build fancy DMGs on your Github Actions workflows with just one simple action.

Started off as a fork of [QQxiaoming/create-dmg-action](https://github.com/QQxiaoming/create-dmg-action) with https://github.com/QQxiaoming/create-dmg-action/pull/128 merged.

After a couple years of having to manually dump Node dependency versions and re-compile every so often, I had Claude move the logic from a Typescript script to simple shell commands.  Behavior should be identical.

## Inputs

## `name`

**Required** DMG file name. Default `"target"`.

## `srcdir`

**Required** Source dir path. Default `"srcdir"`.

## Example usage

```
uses: unofficial-rev-port/create-dmg-action-fixed-icon@v1
with:
  name: 'target'
  srcdir: 'srcdir'
```
