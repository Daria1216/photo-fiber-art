# photo-fiber-art

将用户上传的原照片与解构式纤维刺绣组成上下拼接的竖版作品。上半部使用原照片，下半部以柔雾羊毛、针脚、线结、布条、薄纱与透布水彩重新表现主体，并以完整的竖针和 X 针连接两层。

本仓库就是一个独立的 Codex skill。入口文件是根目录的 [`SKILL.md`](SKILL.md)，制作提示词和合成规范在 [`references/`](references/) 中。公开版本不包含用户上传的照片或成品参考图。

## 使用

在 Codex 中发送：

> 请从 https://github.com/Daria1216/photo-fiber-art 安装 photo-fiber-art skill。

安装后上传照片，并发送：

> 使用 $photo-fiber-art，把这张照片做成“摄影 × 解构式纤维刺绣”的竖版 2:3 作品。上半部保留原照片，下半部生成刺绣，并让针脚自然跨越接缝。
