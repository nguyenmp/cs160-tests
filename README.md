cs160-tests
===========


DO ME
===========

#! /bin/bash

for file in "$@"
do
        echo "Testing $file"
        ./lang < "$file" 1> /dev/null
        echo ""
done

