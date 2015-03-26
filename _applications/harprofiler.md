---
layout: post
title: harprofiler
link: http://harprofiler.readthedocs.org/en/latest/
source: https://github.com/edx/harprofiler
license: Apache License
---

harprofiler is a python utility used for profiling web pageloads. It loads web pages and saves JSON files in HAR (HTTP Archive) format. By default, it will load a page once uncached, and then again with it cached in the browser. A HAR file for each pageload is saved locally, and optionally uploaded to a HARStorage server instance. HAR files contain a log of HTTP client/server conversation and can be used for analysis of page load performance.
