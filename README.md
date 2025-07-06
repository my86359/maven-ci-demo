#!/bin/bash

echo "// New change" >> src/Main.java
git add .
git commit -m "Modified source code"
git push origin master
