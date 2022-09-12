# fsab

## Bazel

To visualize the dependency graph, run
```bash=
bazel query --output graph --nograph:factored 'kind(proto_library, //...)' | dot -Tpng > graph.png
```