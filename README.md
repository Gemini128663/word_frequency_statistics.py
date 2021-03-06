<!--
 * @Author: chang_an
 * @Date: 2019-12-19 16:30:14
 * @LastEditors  : chang_an
 * @LastEditTime : 2019-12-20 17:00:38
 * @FilePath: \textf:\桌面\word_frequency_statistics.py\README.md
 -->

# 使用Python进行txt文本词频统计

## Python版本

+ 3.7.4

## 使用库

+ [x] os
+ [x] tkinter
+ [x] jieba
+ [x] matplotlib

## 项目背景及介绍

+ 平时工作中需要完成文本词频统计分析，有时由于文本字数较多，就给统计词频带来了不小的麻烦，在此基础上，完成此程序。

## 运行程序

+ 运行此程序，会打开一个文件对话框，双击需要统计的TXT文本，等待jieba分词完成，输入统计数量，即可完成统计，且输出词频统计直方图。

## 运行注意事项

1. 第一代只能对单一TXT文本进行统计分析，且分析只有两字词语。
2. 三次内需要正确打开文本，否则，此次程序运行结束。
3. 由于程序最后会将统计结果绘制成统计图，所以如果统计数量过多，统计图X轴将无法清晰显示，如不需要统计图，可忽略。

## 下载

```python
pip install text-word
```

## 代码示例

```python

from text import words
words.statistics()
```

上述代码即可完成词频统计。

## 报错处理

如有以下错误：


![报错现象](https://github.com/Gemini128663/photos/raw/master/photos/14.png
)

将TXT文本重新保存为UTF-8模式即可。
