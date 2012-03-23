 Dojo Toolkit: The Works
========================

This repo helps clone the full Dojo Toolkit from [Dojo's official GitHub
account](https://github.com/dojo), where each project is a separate repo.  

Notes
=====

- I will try to maintain branches for the major versions of Dojo, starting
  with 1.7. To update a branch:

        for dir in dojo dijit dojox util; do cd $dir && git checkout 1.7.2 && cd ..; done
