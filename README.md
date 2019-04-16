# Path of Building Winepak

This is pretty barebone and is the somewhat minimal flatpak definition that
allowed me to have Path of Building actually start and be usable. More work
needs to go into this. Bug reports and contributions are most welcome!

Happy theorycrafting!

## How to use

```
$ flatpak-builder --user --force-clean --install build com.github.com.pathofbuilding.yml
$ flatpak run com.github.com.pathofbuilding
```
