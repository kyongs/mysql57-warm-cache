# Warm-Cache


- **search keyword**: `UNIV_WARM_BUF_CACHE`
- `build.sh`내 `BUILD_DIR`, `BASE_DIR`, `PASSWD` 수정 필요
- **DB size**: 54G (500WH)
- **TPCC**: ```./tpcc_start -h 127.0.0.1 -S /tmp/mysql.sock -d tpcc -uroot -p1234 -w 500 -c 40 -r 30 -l 10800 | tee ${date}-tpcc-result-warm-warmbuf.txt```
