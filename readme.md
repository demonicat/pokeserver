# PokeServer

![GitHub repo size](https://img.shields.io/github/repo-size/demonicat/pokeserver)
[![GitHub](https://img.shields.io/github/license/demonicat/pokeserver)](https://github.com/demonicat/pokeserver/blob/main/LICENSE)

Based off [PokeDash by Pota](https://otland.net/threads/10-98-tfs-1-2-pokemon-pokedash-pota-v1-0.278516/)

Remember to unzip the map on `data/world`

## Compiling on Arch Linux
```sh
sudo pacman -Syu base-devel git cmake luajit boost boost-libs libmariadbclient pugixml crypto++ fmt --needed

git clone https://github.com/demonicat/pokeserver.git

cd pokeserver

cmake . -B build

make -C build -j4
```