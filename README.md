# BIPsImplementation GPU
Implementation of two BIPs</br> forked from [BIPsImplementation](https://github.com/BilawalAhmed0900/BIPsImplementation)

 - BIP0039
 - BIP0044

Help page: ```BIP0039.exe -help```

```
C:\Users\BOSS>BIP0039.exe -h
Usage: BIP-0039 [options]

Optional arguments:
-h --help               shows help message and exits
-v --version            prints version information and exits
-n --num                Number of phrases to generate [required]
-s --entropy-size       Entropy size in bits [default: 128]
--db                    Database file to write to [required]
--lang                  Language to get words from [required]
```

Help page: ```BIP0044.exe -help```
```
C:\Users\BOSS>BIP0044.exe -h
Usage: BIP0044 [options]

Optional arguments:
-h --help               shows help message and exits
-v --version            prints version information and exits
-n --num-input          Number of addresses to generate, i.e., number of phrases to read from input [required]
-th --num-threads       Number of threads to use [default: 8]
-c --childs             Childs key per master key (address_index) [required]
-i --input              The input file to read from [required]
-p --pass-phrase        The pass phrase for binary seed generation [default: ""]
-o --output             The output file to write to [required]
```
