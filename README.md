# Trac base image for Docker

This image contains Trac 1.2.3. Use it either to run a very basic trac
instance or as a base to extend from.

The image is created from python:2-slim and is about 320MB in size.

It contains Trac, docutils, Pygments for syntax highlighting and Babel for
trac translations.

Subversion is also preinstalled so you can fetch additional plugins from trac-hacks.org easily.
Furthermore, a postgresql client lib is packaged in this image as an alternative to sqlite.
