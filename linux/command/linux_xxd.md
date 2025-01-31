# 搜尋linux 指令

```
hex to string linux
```
```
google 查詢xxd

http://manpages.ubuntu.com/manpages/trusty/zh_TW/man1/xxd.1.html
https://zhuanlan.zhihu.com/p/24883064
https://www.itread01.com/p/1382700.html
https://www.twblogs.net/a/5b833e712b71771e35c1e196
https://blog.csdn.net/jctian000/article/details/85097428
```

# CTF 詳解
```
lab@29d4cf5af0ab:~$ xxd -r -p hex.txt
BreakALLCTF{GIUWOfdsf ewfw fgeav kljerqn blgjktljn ewVwr}
```
# xxd 指令參數
```
lab@29d4cf5af0ab:~$ xxd -h
Usage:
       xxd [options] [infile [outfile]]
    or
       xxd -r [-s [-]offset] [-c cols] [-ps] [infile [outfile]]
Options:
    -a          toggle autoskip: A single '*' replaces nul-lines. Default off.
    -b          binary digit dump (incompatible with -ps,-i,-r). Default hex.
    -c cols     format <cols> octets per line. Default 16 (-i: 12, -ps: 30).
    -E          show characters in EBCDIC. Default ASCII.
    -e          little-endian dump (incompatible with -ps,-i,-r).
    -g          number of octets per group in normal output. Default 2 (-e: 4).
    -h          print this summary.
    -i          output in C include file style.
    -l len      stop after <len> octets.
    -o off      add <off> to the displayed file position.
    -ps         output in postscript plain hexdump style.
    -r          reverse operation: convert (or patch) hexdump into binary.
    -r -s off   revert with <off> added to file positions found in hexdump.
    -s [+][-]seek  start at <seek> bytes abs. (or +: rel.) infile offset.
    -u          use upper case hex letters.
    -v          show version: "xxd V1.10 27oct98 by Juergen Weigert".

```
# 我的測試報告
```

```
### 測試1
```

```

### 測試2
```

```
### 測試3
```

```
### 測試4
```

```
### 測試5
```

```




