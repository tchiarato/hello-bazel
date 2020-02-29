# A Bazel case of study

## Bazel Build


To build the main class use the command bellow:

```
bazel build //helloworld/src/main/java/helloworld:helloworld
```

To run the main class use the command bellow:

```
bazel run //helloworld/src/main/java/helloworld:helloworld
```

## Pinning artifacts and integration with Bazel's downloader

Whenever you make changes to the list of `artifacts` or `dependencies` run the
following command to re-pin unpinned `@maven` repository.

```
bazel run @unpinned_maven//:pin
```
