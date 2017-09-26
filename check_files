#!/bin/bash

checksum=$(cksum update | awk '{ print $1 }')

if [ "$checksum" == "546962921" ] ; then 
    echo "Success"
else 
    echo "Failure"
    exit 1
fi
