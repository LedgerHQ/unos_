---
title: Getting Started
subtitle:
tags: []
author: greenknot
layout: doc_sp
---

#### Sections in this article
{:.no_toc}
* TOC
{:toc}

## clang-format

clang-format is used by the CI to format C code according to a set of rules and
heuristics. The CI checks will fail if some code isn't formatted as expected by
the rules.

To ensure that the CI checks pass, please use the script `tools/clang-format.sh`
(the path to clang-format can be specified thanks to the `CLANG_FORMAT`
environment variable):

```
CLANG_FORMAT=clang-format-11 ./tools/clang-format.sh
```
