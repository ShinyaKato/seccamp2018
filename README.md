# seccamp2018

Simple C compiler developed by @ShinyaKato in Security Camp 2018

このリポジトリは純粋にセキュリティ・キャンプ2018の成果物を残しておくためのものです。  
機能追加は [sk2cc](https://github.com/ShinyaKato/sk2cc) で続けています。

## build

Run make command, then `cc` is generated.

```
$ make cc
```

## compilation

Compiler `cc` recieves source file name and generates assembly to stdout.
To generate executable, use gcc with `-no-pie` option.

```
$ ./cc examples/queen.c > queen.s
$ gcc -no-pie queen.s
```

## example

See example programs that can be compiled with `cc` in [examples](https://github.com/ShinyaKato/seccamp2018/tree/master/examples).
