# Monitor and auto execute single script after modify

support go, python, c++, c.
filename endswith .py .c .cpp .go

[zh_cn] 自动执行修改后的脚本

## install

```bash
pip install seeing
```

## use

```bash
seeing hello.py
seeing -s 3 hello.go  # execute script after hello.go modified 3 seconds.
seeing hello.cpp      # it will run g++ hello.cpp && ./a.out
seeing hello.c        # same as cpp
```
