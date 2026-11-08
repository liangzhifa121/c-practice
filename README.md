# C 语言练习

华南师范大学 · 数据科学与大数据技术 · 大一

用来存放 C 语言课程练习和课后代码，按周归档。

## 目录结构

```
c-practice/
├── week01/        第 1 周
├── week02/        第 2 周
├── week03/        第 3 周
└── ...
```

每周的作业放一个文件夹，文件名直接写题号或内容，例如：

```
week08/
├── 01_array_sum.c
├── 02_bubble_sort.c
└── README.md      （可选：记一句这周学了什么）
```

## 作业索引

| 周次 | 内容 | 链接 |
|---|---|---|
| 第 1 周 | Hello World | [week01/hello.c](week01/hello.c) |

## 编译运行

```bash
cd week01
gcc hello.c -o hello
./hello
```

## 提交方式

```bash
git add .
git commit -m "第N周作业：内容简述"
git sync
```
