---
layout: post
title: Linux Turkish Subtitle Encoding
description: How to fix Turkish character problem in Linux?
tags: linux turkish subtitle encoding iconv
---

<style>
.highlight-left {margin-left: 0}
</style>

```
iconv -f ISO-8859-9 -t UTF-8 input.srt > output.srt
```



