# CardLedger 识别词表

卡迹记账 App 截屏识别用的关键词数据（平台名、按钮、字段标签等），App 联网下载后自动生效。

- `ScreenshotVocabulary.json`：词表本体，只有数据，不含代码。
- `ScreenshotVocabulary.json.sig`：发布者的 Ed25519 签名。App 只启用签名正确、内容检查通过、版本号更高的词表。

本仓库由发布脚本自动更新，请勿手工修改文件（改动会导致签名失效、App 拒绝使用）。
