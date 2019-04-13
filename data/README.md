### 24 May 2018
Expand tabs introduced by `fmt` in `vim`:
```
:set expandtab
:set tabstop=8
:retab
```
`fmt -l 0` eliminates this problem.

### 13 April 2019
Vim non-greedy search and replace examples:
```
:g/<ab>\_.\{-}<\/ab>/s//<ab><\/ab>/gp
:g/start.\{-}(canon)/s//start canon/gp
:g/end.\{-}(canon)/s//end canon/gp
:g/start.\{-}(inscription)/s//start inscription/gp
:g/end.\{-}(inscription)/s//end inscription/gp
:g/start.\{-}(rubric)/s//start rubric/gp
:g/end.\{-}(rubric)/s//end rubric/gp
```
