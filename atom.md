# atom编辑器如何全部替换页面内的空行
使用‘.*’
搜索
```
\n[\t]*\n
```
替换
```
\n
```