# Over-the-wire-bandit
PClub Self Assessment - Part A

- **Level 0** :
  - _Commands _:
    1. ssh bandit0@bandit.labs.overthewire.org -p 2220
  - _Password :_ bandit0
- **Level  0 -> Level 1** :
  - _Commands :_
    1. ls
    1. file *
    1. cat *
    1. ssh bandit1@bandit.labs.overthewire.org -p 2220
  - _Password :_ boJ9jbbUNNfktd78OOpsqOltutMc3MY1
- **Level 1 -> Level 2** :
  - _Commands :_
    1. ls
    2. cat ./-
    1. ssh bandit2@bandit.labs.overthewire.org -p 2220
  - _Password :_ CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
- **Level 2 -> Level 3** :
  - _Commands :_
    1. ls
    2. cat *
    3. ssh bandit3@bandit.labs.overthewire.org -p 2220
  - _Password :_ UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
- **Level 3 -> Level 4** :
  - _Commands :_
    1. ls
    2. cd inhere
    3. ls -a
    4. cat .*
    5. ssh bandit4@bandit.labs.overthewire.org -p 2220
  - _Password :_ pIwrPrtPN36QITSp3EQaw936yaFoFgAB
- **Level 4 -> Level 5** :
  - _Commands :_
    1. ls
    2. cd inhere
    3. ls
    4. find /dir/to/search -type f -print0 | xargs -0 file | grep text
    5. ssh bandit5@bandit.labs.overthewire.org -p 2220
  - _Password :_ koReBOKuIDDepwhWk7jZC0RTdopnAYKh
- **Level 5 -> Level 6** :
  - _Commands :_
    1. ls
    2. cs inhere
    3. find . -size 1033c
    4. cd maybehere07
    5. cat .file2
    6. ssh bandit6@bandit.labs.overthewire.org -p 2220
  - _Password :_ DXjZPULLxYr17uwoI01bNLQbtFemEgo7
- **Level 6 -> Level 7** :
  - _Commands :_
    1. ls
    2. cd ..
    3. cd ..
    4. find -group banidt6 -user bandit7 -size 33c
    5. cat var/lib/dpkg/info/bandit7.password
    6. ssh bandit7@bandit.labs.overthewire.org -p 2220
  - _Password :_ HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
- **Level 7 -> Level 8** :
  - _Commands :_
    1. ls
    2. grep -Rw 'data.txt' -e 'millionth'
    3. ssh bandit8@bandit.labs.overthewire.org -p 2220
  - _Password :_ cvX2JJa4CFALtqS87jk27qwqGhBM9plV
- **Level 8 -> Level 9** :
  - _Commands :_
    1. ls
    2. cat data.txt | sort | uniq -c -u
    3. ssh bandit9@bandit.labs.overthewire.org -p 2220
  - _Password :_ UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
- **Level 9 -> Level 10** :
  - _Commands :_
    1. ls
    2. strings data.txt | grep ===
    3. ssh bandit10@bandit.labs.overthewire.org -p 2220
  - _Password :_ truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk
- **Level 10 -> Level 11** :
  - _Commands :_
    1. ls
    2. base64 -d data.txt
    3. ssh bandit11@bandit.labs.overthewire.org -p 2220
  - _Password :_ IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
- **Level 11 -> Level 12** :
  - _Commands :_
    1. ls
    2. cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
    3. ssh bandit12@bandit.labs.overthewire.org -p 2220
  - _Password :_ 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu
- **Level 12 -> Level 13** :
  - _Commands :_
    1. ls
    2. 
