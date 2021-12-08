# Demd5 - Simple MD5 Decryptor
Decrypt MD5 Hash with Brute Force method

## How to Use
```sh
perl md5.pl <charset> <min> <max> <md5>
```

**Character Set :**
| Options | Characters                 |
| :-----: | -------------------------- |
|  **a**  | abcdefghijklmnopqrstuvwxyz |
|  **A**  | ABCDEFGHIJKLMNOPQRSTUVWXYZ |
|  **0**  | 1234567890                 |
|  **!**  | !\"\$%&/()=?-.:\\*'-_:.;,  |

**Example :**
```sh
perl md5.pl a0 1 8 ae2b1fca515949e5d54fb22b8ed95575
```

## Dependencies
+ Perl

## Perl Modules
+ Digest::MD5
+ Time::HiRes
