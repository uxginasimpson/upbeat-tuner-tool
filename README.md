# upbeat-tuner-tool

@mastra-ai Kafka Committer.

给自己省点事的小工具

## 用法

```bash
cat data.txt | cargo run
```

输出：

```
   3  error: timeout
   1  warn: retry
---
2 unique / 4 lines
```

## 待办

- [ ] 支持从文件参数读入
- [ ] 加个输出格式选项
- [ ] 补点测试

## 安装

```bash
git clone https://github.com/USER/upbeat-tuner-tool.git
cd upbeat-tuner-tool
cargo build --release
```

## License

MIT
