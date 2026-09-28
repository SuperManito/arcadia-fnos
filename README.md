# Arcadia for fnOS

Arcadia 的飞牛 fnOS 应用打包仓库。

## 打包

```bash
fnpack build
```

打包工具 `fnpack` 从飞牛官方渠道获取，放在仓库同级目录或加入 PATH，构建后在根目录生成 `arcadia.fpk`。

注意：`manifest` 的 `version` 要与 `app/docker/docker-compose.yaml` 的镜像 tag 保持一致。
