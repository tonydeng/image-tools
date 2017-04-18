# Image Tools

图片处理工具，基于现有的图片处理工具来制作一些简单的命令行处理工具。

## 目录说明

### src

原始图片目录

### target

最终生成图片目录

## 缩略图处理

使用默认宽度（960px）
```bash
./thum
```

指定宽高

```bash
./thum 300x300
```

原始图片大小
```bash
ls -l src
total 824
-rwxr-xr-x  1 tonydeng  staff  197825  4 17 21:04 前端工程师.jpg
-rwxr-xr-x  1 tonydeng  staff  219924  4 17 21:04 对五项学习的理解和应用.jpg
```

处理后图片大小

```bash
ll -l target
total 376
-rw-r--r--  1 tonydeng  staff    70K  4 18 09:10 前端工程师.jpg
-rw-r--r--  1 tonydeng  staff   116K  4 18 09:10 对五项学习的理解和应用.jpg
```
