# Windows 虚拟终端序列

[![Go Report Card](https://goreportcard.com/badge/github.com/wzshiming/winseq)](https://goreportcard.com/report/github.com/wzshiming/winseq)
[![GitHub license](https://img.shields.io/github/license/wzshiming/winseq.svg)](https://github.com/wzshiming/winseq/blob/master/LICENSE)

在 Windows 中使用 类Unix序列

虚拟终端序列是控制字符序列，其可以在写入输出流时控制光标移动，颜色/字体模式和其他操作。
还可以响应于输出流查询信息序列在输入流上接收序列，或者在设置适当模式时作为用户输入的编码接收序列。

[文档](https://docs.microsoft.com/en-us/windows/console/console-virtual-terminal-sequences)

## 用法

``` golang

import _ "github.com/wzshiming/winseq"

```

## 许可证

软包根据MIT License。有关完整的许可证文本，请参阅[LICENSE](https://github.com/wzshiming/winseq/blob/master/LICENSE)
