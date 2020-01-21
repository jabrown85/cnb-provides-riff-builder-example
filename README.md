# What

This is an example builder of how we might could invert the dependency of riff's buildpacks. This would also allow buildpacks to provide Riff with metadata to change the buildpack behavior.

```
# cd examples/java or examples/node
pack build --builder riffbuilder -v --no-pull -e "RIFF=1" output
```
