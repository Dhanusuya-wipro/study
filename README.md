# study
17_2
---
image: python:3.13
stages:
-test

test:
 stage: test
 script:
 #print every command for debugging
 -set -x
 #step 0: check environment 
 
