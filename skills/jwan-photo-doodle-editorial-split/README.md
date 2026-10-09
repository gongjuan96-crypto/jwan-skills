# jwan-photo-doodle-editorial-split

**Jwan 原片 × 稚拙手绘编辑海报 Skill**

一张照片，一张独立的 3:4 高级海报。上半严格保留原照片（50%），下半以暖白纸张、稚拙细线涂鸦、柔和局部色和大量留白重新讲述照片里的瞬间（50%）。右下角默认署名 `Jwan`。

## 调用

`$jwan-photo-doodle-editorial-split 处理这张照片`

或：

`用 jwan-photo-doodle-editorial-split 处理我上传的全部照片，每张单独输出；标题按照片内容自动决定。`

## 可覆盖参数

- `ratio`: 默认 `3:4`；明确指令可改为 `9:16` 或 `16:9`。
- `split`: 默认上下各 `50%`；用户明确指定时可切换左右分屏。
- `text`: 默认自动生成贴合照片的简短手写词组；用户指定时必须准确使用。
- `signature`: 默认右下角小字 `Jwan`；用户可明确要求关闭。
- `palette`: 从每张原图提取有限点睛色，也可按用户指定色系调整。

## 原片保真与示例授权

真正的“上半原图保真”应采用**保留原图像素、再合成下半插画**的实现，不应依赖模型重绘整张来冒充原照片。

出于肖像和隐私保护，当前公开版本不附带本次儿童生日照片或成品，仅提供可复现的案例 brief。后续可用作者自有、授权或不含可识别人物的素材补充视觉案例。

## 文件

- [SKILL.md](SKILL.md)：详细规则及可执行指令
- [TESTS.md](TESTS.md)：质量验收及回归测试
- [examples/README.md](examples/README.md)：3个案例 brief
- [CHANGELOG.md](CHANGELOG.md)：版本记录
- [LICENSE](LICENSE)：MIT License

Created and maintained by **Jwan**. [GitHub](https://github.com/gongjuan96-crypto)