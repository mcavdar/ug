---
layout: post
title: Schedule command **at**
description: How to schedule download a video from Youtube?
tags: at schedule youtube-dl download linux
---

<style>
.highlight-left {margin-left: 0}
</style>

Create a file contains:
```
youtube-dl -f bestvideo+bestaudio youtube-video-link
```

and add a job by using at command:
```
at now + 2 hours < file
```




