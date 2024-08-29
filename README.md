
# sktrace
https://bbs.pediy.com/thread-264680.htm

## 功能
1. 类似 ida 指令 trace 功能
2. 统计寄存器变化，辅助分析，并且可能会有字符串产生，

## todo
1. arm32。
2. 改为 C 实现


## 用法
1. attach
```python sktrace.py -m attach -l {soName} -i {funcAddr | funcExportName} {appName} > trace.log```
2. spawn
```python sktrace.py -m spawn -l {soName} -i {funcAddr | funcExportName} {packageName} > trace.log```


