# providerscope

A replacement for [scoped_model](https://github.com/brianegan/scoped_model).

A set of utilities that allow you to easily pass a data Model from a parent Widget down to it's descendants, optionally namespaced to a specificed "scope".

This library was originally extracted from the [topaz](https://fuchsia.googlesource.com/topaz/) repository in the Fuchsia codebase, following a similar effort at [github.com/mishudark/providerscope](https://github.com/mishudark/providerscope).

## Installation

Edit `pubspec.yaml`:

```
dependencies:
  providerscope:
      git: git://github.com/lleaff/providerscope.git
```

## Contribute

```
flutter test
```
