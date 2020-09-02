# sqlite-lsm1-lz4
WIP adding lz4 compression to sqlite3-lsm1 based on https://github.com/thoughtpolice/sqlite4_lsm_lz4

build like so:

export CFLAGS="-fPIC -O2"
TCCX="gcc -g -fPIC -O2" make lsm.so


note: based on https://www.charlesleifer.com/blog/lsm-key-value-storage-in-sqlite3/
