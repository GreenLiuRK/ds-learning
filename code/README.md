# 代码实现

按章节建子目录，每个数据结构一个文件，能独立编译运行。

## 目录约定

```
code/
├── 01-线性表/
│   ├── sqlist.c       顺序表
│   └── linklist.c     单链表
├── 02-栈与队列/
│   ├── sqstack.c
│   └── sqqueue.c
├── 03-树与二叉树/
│   ├── bitree.c
│   └── bst.c
├── 04-图/
│   ├── mgraph.c
│   └── algraph.c
├── 05-查找/
│   └── hash.c
└── 06-排序/
    └── sort.c
```

## 编码约定

- 文件名用小写英文，不要中文（跨平台更稳）
- 每个文件带 `main`，可以直接 `gcc xxx.c -o xxx` 编译
- 提交前确保能编译通过，别传半成品
- 编译产物（`.exe`、`.o`）被 `.gitignore` 忽略，不进仓库

## 编译

```bash
gcc -std=c99 -Wall -O2 -o sqlist sqlist.c
```
