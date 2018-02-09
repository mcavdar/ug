---
layout: post
title: Gitlab Service Start Stop
description: How to start/stop Gitlab server?
tags: linux gitlab git maintenance
---

<style>
.highlight-left {margin-left: 0}
</style>

To start:
```
sudo gitlab-ctl start
sudo systemctl start gitlab-runsvdir
```

To stop:
```
sudo gitlab-ctl stop
sudo systemctl stop gitlab-runsvdir
```

To disable:
```
sudo systemctl disable gitlab-runsvdir.service
```



