#!/bin/sh
sed "s/^\[.*$//g;s/<.*>//g;s/^0.*$//g;/^$/ d;/^\s$/ d" $1 | awk '!visited[$0]++'
