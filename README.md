# googletra
通过python3 调用谷歌的翻译接口

## 环境安装
```bash
pip install PyExecJS
pip install requests
```

## 模块接口
`tran_word(word, proxies=None)`
#### 参数含义
- word 需要翻译的单词, 这里使用自动识别语言,
- proxies 是否需要设置代理, 尽可能设置代理, 因为默认走的不是中国的谷歌接口, 所以还是需要登天梯
- 接口只有这么简单的一个,默认自动翻译成中文

> 接口是借鉴的论坛上某位大神的, 至于怎么用看你们咯
