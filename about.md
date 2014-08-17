---
layout: page
title: About
---

This build of OpenWRT is configured to support x86\_64 systems with more
resources than the standard targets.  It fully supports multiple processors, and
all available system memory.

The image is built to fit on a 4GB storage device with room for an optional swap
partition.

Binary packages have not been built for the full package tree, with only those
packages related to routing, or configurable via LuCI, available from the
repository.

Users may build additional packages using the ImageBuilder/SDK, however it is
suggested instead for users to install the `lxc*` packages and then run their
preferred Linux distribution in a container for full software coverage.

With that said, if you feel that there is a package that should be available in
the base image (many more net drivers should be, for example), feel free to
[submit an issue]({{ site.github.repo }}/issues) to have it added.

## Maintenance
I don't expect to rigorously maintain this build, I just don't have the
available bandwidth.  If feasible, I may look at producing automated builds, but
that will require additional work, so probably don't expect it in the near
future.

If you would like to help out, please do drop me a line on [Github]({{ site.github.repo }}).
