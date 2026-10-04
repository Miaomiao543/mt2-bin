# mt2

轻量级文件管理 CLI 工具（编译产物）。

## 下载

| 文件 | 架构 | 类型 | 大小 |
|------|------|------|------|
| `mt2_v3-arm64` | ARM64 (aarch64) | 静态可执行 | 2.5 MB |
| `mt2_v4-arm64` | ARM64 (aarch64) | 静态可执行 | 1.9 MB |
| `mt2_v3-x86_64` | x86_64 | 静态可执行 | 2.2 MB |
| `mt2_arm64.so` | ARM64 (aarch64) | 共享库 (.so) | 84 KB |
| `mt2_x86_64.so` | x86_64 | 共享库 (.so) | 136 KB |
| `mt2_arm32` | ARM 32-bit | 可执行 | 102 KB |

## 使用

```bash
chmod +x mt2_v3-arm64
./mt2_v3-arm64 --help
```

支持命令：`copy move delete list read write chmod stat grep rename replace replacedir hexdump hexwrite diff wait zip unzip`
