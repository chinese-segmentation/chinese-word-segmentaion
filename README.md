# chinese-word-segmentaion
一个中文分词器

将会考虑集成多种算法，利用基于policy的设计模式结合在一起。 首先考虑能够处理UTF8,UTF16(unicode)格式的输入文本 能够处理单独的string..分词 内部统一用2bytes的unicode u16string表示，输出为UTF16

当前不考虑超过2bytes的unicode字符,不处理格式为UTF32的文本,及GBK等文本格式的文本

## License

GNU GPL v3

Automatically exported from code.google.com/p/chinese-word-segmentaion
