First step is to compile the leveldb library.  On my ubuntu machine, I checkout the source from google code, patch it and run make.

 - `svn checkout http://leveldb.googlecode.com/svn/trunk/ leveldb-read-only`
 - <https://gist.github.com/979977> - Patch changing cstdatomic to atomic and enabling fast mode

Next step is to figure out how to bundle or depend on the source for the library.  Most people won't have it already on their system.