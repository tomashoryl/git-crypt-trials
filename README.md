# git-crypt-trials

```sh
$ git diff --name-only origin/main
encrypted/enctext.txt
src/plaintext.txt
src/updated.txt

$ git diff origin/main encrypted/enctext.txt
$

$ git show origin/main:encrypted/enctext.txt
^@GITCRYPT^@<D1> <C1>><91><EE><89><D3>@<B2><9B>w<8A>
```
