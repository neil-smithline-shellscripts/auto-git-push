#!/bin/sh

PATH="~/bin:/sbin:/bin:/var/sbin:/var/bin:/usr/local/bin:$PATH"

cd "$1"
git add -A .
git commit -q -m 'automated update'
git push -q
