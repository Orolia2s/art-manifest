# Atomic Reference Time Manifest

This project contains the manifest to build the ART daemon and its libraries

## Release workspace (release versions)

```bash
repo init -u ssh://git@github.com/Orolia2s/art-manifest.git -b main -m art_release.xml
repo sync
make
```


## Moving workspace (dev versions)

```bash
repo init -u ssh://git@github.com/Orolia2s/art-manifest.git -b main -m art_moving.xml
repo sync
make
```

## Default

```bash
repo init -u ssh://git@github.com/Orolia2s/art-manifest.git -b main
repo sync
make
```
