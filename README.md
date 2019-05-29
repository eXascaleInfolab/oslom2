# OSLOM2, version 2.5
The fastest version of OSLOM2 clustering algorithm with slightly extended I/O for the benchmarking under [Clubmark](https://github.com/eXascaleInfolab/clubmark). The original sources of [OSLOM2 v2.5](http://www.oslom.org/code/OSLOM2.tar.gz) are taken from http://www.oslom.org/software.htm. The algorithm description with the respective paper `Finding statistically significant communities in networks, A. Lancichinetti, F. Radicchi, J.J. Ramasco and S. Fortunato, PLoS ONE 6, e18961 (2011)` are available on the original website: http://www.oslom.org/.  
The modifications are made by `Artem Lutov <artem@exascale.info>`, [eXascale Infolab](http://exascale.info/) and are available under [Apache License Version 2](https://www.apache.org/licenses/LICENSE-2.0.html).

Compilation for the undirected and directed input networks respectively:
```sh
$ g++ -o oslom_undir ./main_undirected.cpp -O3 -Wall
$ g++ -o oslom_dir ./main_directed.cpp -O3 -Wall
```
