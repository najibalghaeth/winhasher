Here's a brief run down of what we're planning to add in version 1.7 of WinHasher:

  * Hashing files and directories and reading and writing the output to and from files. The basic idea is to make a drop-in GUI equivalent for UN\*X style utilities like md5sum, shasum, etc. See [this feature request](https://code.google.com/p/winhasher/issues/detail?id=1) for additional details.
  * A command-line flag to turn off reading and writing to the registry. This should make running WinHasher as a portable app cleaner.
  * Support for additional cryptographic hashes, such as SHA-3, SHA-512/t, longer RIPEMD variants, GOST R 34.11-94 and other legacy digests, etc.