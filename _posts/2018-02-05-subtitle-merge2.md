---
layout: post
title: Subtitle Merge
description: How to merge a subtitle with movie? A blog giving you some insights about how you can merge your subtitle with movie, i.e, soft and hard method.
tags: linux ffmpeg subtitle movie
---

<style>
.highlight-left {margin-left: 0}
</style>

```
ffmpeg -i The.Class.2008.1080p.BluRay.H264.AAC-RARBG.mp4 -strict -2 -vf "subtitles=cikti.srt:force_style='Fontsize=24'" out3.mp4
```



