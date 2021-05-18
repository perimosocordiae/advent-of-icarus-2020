# advent-of-icarus-2020
Solving Advent of Code 2020 in [Icarus](https://github.com/asoffer/Icarus).

To get started:

```
git clone https://github.com/asoffer/Icarus.git
cd Icarus
bazel build -c dbg //compiler:interpret
export ICARUS_MODULE_PATH=$(realpath ./stdlib)
cd ..

git clone https://github.com/perimosocordiae/advent-of-icarus-2020.git
cd advent-of-icarus-2020
ln -s ../Icarus/bazel-bin/compiler/interpret icarus

./icarus day01.ic
```
