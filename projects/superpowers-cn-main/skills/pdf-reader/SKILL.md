---
name: pdf-reader
description: >
  Read and analyze PDF documents. Use this skill when the user says "/pdf", "read a PDF", "analyze PDF", "extract text from PDF", wants to understand the contents of a .pdf file, or needs to extract/translate/summarize PDF content. Also use when the user provides a path to a PDF file and asks what it contains. Supports reading specified page ranges and providing structured analysis. Do NOT use for non-PDF documents or creating PDF files.
---

# PDF Reader

## 概述

这个 skill 让 Claude 能够读取和分析 PDF 文件。使用内置的 Read 工具处理 PDF，并对内容进行结构化呈现。

## 触发方式

用户可以说：
- "/pdf <文件路径>"
- "帮我读一下这个 PDF"
- "分析这份 PDF 文件"
- "提取 PDF 中的内容"
- "这份 PDF 讲了什么"

## 工作流程

1. 确认用户提供的 PDF 文件路径是否存在
2. 使用 Read 工具读取文件（指定 pages 参数）
3. 根据用户需求呈现内容

## 注意事项

- 单次读取最多 20 页，大文件需要分多次
- 遇到扫描件（图片类 PDF）告知用户提取效果可能受限
- 对于长文档，先读取目录或前几页，让用户选择需要深入的部分
