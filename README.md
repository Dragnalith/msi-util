# msi-util [![Build Status](https://github.com/Dragnalith/msi-util/actions/workflows/build.yml/badge.svg)](https://github.com/Dragnalith/msi-util/actions/workflows/build.yml)

Small CLI utility to unpacks MSI packages


## Build

```bash
bazel build //:msi-util
```

Release-style binaries for all supported platforms:

```bash
bazel build --config release --config remote \
  --remote_header=x-buildbuddy-api-key="$BUILDBUDDY_API_KEY" \
  //:for_all_platforms
```

