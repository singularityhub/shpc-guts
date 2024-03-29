# Singularity Registry Container Guts!

[![DOI](https://zenodo.org/badge/529103668.svg)](https://zenodo.org/badge/latestdoi/529103668)
[![DOI](https://zenodo.org/badge/529092526.svg)](https://zenodo.org/badge/latestdoi/529092526)

> Let's get some *guts* for PATHs inside containers! 🤓

The goal of this repository is to provide transparency for container guts, or
more simply, executables in containers. We will derive updated guts for
a set of core base containers nightly, and then we can diff them against
user-level containers to discover the special executables inside. We could
also do cool stuff like diffs to compare contents, if we wanted! This
uses the [singularityhub/guts](https://github.com/singularityhub/guts) action.
Guts are organized by docker namespace here.
