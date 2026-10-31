# NaiwaHub / 奶娃 Hub 素材索引

An independent community archive of Naiwa-related memes. This is not an official character collection. Creators and other rights holders retain their rights; inclusion does not establish authorship, permission or commercial-use rights.

这是独立的奶娃相关社区素材整理，不代表官方。作品与角色的权利仍归各权利人；收录不等于已确认作者、再分发授权或商用许可。

## Browse / 浏览

Open `index.html` locally, or serve this folder with any static server. The index has English/Chinese labels, text search, series and media filters. It makes no external network requests. GitHub's file view does not execute an HTML page; GitHub Pages must be enabled separately if a hosted index is wanted.

本地打开 `index.html`，或使用静态文件服务。索引支持中英切换、搜索、系列和媒体筛选，不调用外部服务。GitHub 文件页面不直接运行 HTML；在线索引需要另行启用 GitHub Pages。

## Contents / 文件

- `originals/<series>/<stable-id>.<format>`: byte-for-byte copies of the original media already in the verified public library. No frames are counted as separate works; watermarks remain intact.
- `previews/<series>/...`: explicitly marked converted previews. These are not represented as the original files.
- `metadata.json`: bilingual titles, tags and descriptions; stable IDs; type, mood, series and storyline; sanitized source URLs; creator and rights status; SHA-256 and file size.
- `SHA256SUMS`: hashes for all distributed media and imported license notices.
- `LICENSES/`: original source license notices, scoped to the source repository or other stated scope. They do not silently license third-party images.
- `sources.json`, `RIGHTS.md`, `CONTRIBUTING.md`: source context, rights boundaries and contribution guidance.
- `EXPORT-RECEIPT.json`: deterministic counts, source-snapshot hashes and inventory checksum for this export. It contains no private upload/report data.

`originals/` 按角色系列保存已核验的媒体字节，不裁剪水印、不拆帧计数；转换预览单列于 `previews/`。作品作者或许可未确认时，元数据保留 `null`、`unknown` 和 `rightsUnknown: true`。

## Reuse / 使用

Read `RIGHTS.md` and the individual source before reuse. No blanket media license is granted by this repository. An upstream code license does not establish rights to character imagery, photographs, watermarks, audio, trademarks or likenesses. Source URLs are provenance locators, not a promise that every external page remains available.

使用前请阅读 `RIGHTS.md`、逐条来源及其许可。本站不对媒体授予统一许可证；上游代码的许可证不证明角色、图片、水印、声音、商标或肖像的使用权。来源链接仅用于追溯，不承诺第三方页面持续可用。

## Corrections / 更正

For public factual corrections, open a GitHub issue referencing the stable ID and source. Do not post private contact details or identity documents. Rights or privacy concerns should use the site's private `/report` form when available; a report is reviewed by a person and does not automatically remove an item. If the site is unavailable, a public issue should identify the affected ID only, without sensitive evidence. No automatic email response or review deadline is offered.

公开事实更正可通过 GitHub issue 注明永久 ID 和来源，请勿公开联系方式、证件或私人证据。版权或隐私问题应在网站可用时通过其 `/report` 私有表单提交，由人工核对；投诉不会自动删除素材。网站不可用时，公开 issue 仅注明受影响 ID，不上传敏感证据。没有自动邮件回复或固定处理时限。

## Reproducibility / 可重复导出

The website project maintains `scripts/export-public-archive.mjs`. It reads the latest approved public manifest, verifies full SHA-256 and byte counts, exports only listed media, and builds this folder. `--dry-run` checks inputs without writing; `--verify` checks a staged export. Rebuilding preserves an existing `.git` directory or file. Uploads, complaint queues, credentials, private logs, raw chat records, source ZIPs and video transcripts are outside this export.

导出脚本由网站项目维护，每次读取最新的公开清单，逐份核验完整 SHA-256 和字节数，仅复制清单中的媒体。`--dry-run` 不写入文件，`--verify` 核验 staging；重建会保留现有 `.git`。私有投稿、投诉、凭证、日志、聊天记录、源 ZIP 和视频转录不进入该仓库。
