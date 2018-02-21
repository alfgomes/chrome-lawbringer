# chrome-lawbringer
proof-of-concept extension for google chrome that will monitor tab's CPU usage individually and terminate them if they exceed a threshhold. Also experimenting with pulling all JavaScript from webpages and collecting external links to javascript in an effort to detect malicious scripts and prevent them from running.

*only works on dev build currently*

#### An Example of using CPU usage to block cryptominers based on excessive cpu usage.
![Example 1](https://i.imgur.com/VwpbG2E.png)

#### An Example of pulling all scripts inline/external from a page that we can then run against a service for detection.
![Example 2](https://i.imgur.com/uOlKBq3.png)
