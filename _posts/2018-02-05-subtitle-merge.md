---
layout: post
title: How to merge a subtitle with movie
description: A blog giving you some insights about how you can merge your subtitle with movie: soft and hard method.
tags: linux ffmpeg subtitle movie
---

ffmpeg -i The.Class.2008.1080p.BluRay.H264.AAC-RARBG.mp4 -strict -2 -vf "subti
tles=cikti.srt:force_style='Fontsize=24'" out3.mp4

