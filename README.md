
# OCaml

* [公式サイト](https://ocaml.org)
* [Types and Programming Languages](https://www.cis.upenn.edu/~bcpierce/tapl/)

## Mac

4.10だとだめで、4.09.1でコンパイルできた。

```sh
brew install opam
brew install gpatch
opam switch create 4.09.1
eval $(opam env)
wget https://www.cis.upenn.edu/~bcpierce/tapl/checkers/arith.tar.gz
tar -xf arith.tar.gz
cd arith
make
```
