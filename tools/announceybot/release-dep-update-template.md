```zig
.{
    .name = "My example project",
    .version = "0.0.1",

    .dependencies = .{
        // zap {tag}
        .zap = .{
            // when tagged:
            // .url = "https://github.com/zigzap/zap/archive/refs/tags/{tag}.tar.gz",
            .url = "https://github.com/zigzap/zap/archive/{tag}.tar.gz",
            .hash = "{hash}",
        },
        .paths = .{
            "",
        },
    }
}
```
