Description
===========
This is temporary repository for SVN checkout script.
Not intended for any practical purposes but to demonstrate a way to make a checkout from legacy VCS and do other things.

Requirements
============
(TBA)

Usage
=====
~~~
$ ruby ./script.rb <your-repo-list>
~~~
Repository list format is:
~~~
<http(s) address of SVN repository>;<revision or null>
~~~
Please make sure file 'config.json' exists before first run.
