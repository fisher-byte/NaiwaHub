# Rights and source notices / 权利与来源说明

## No blanket media license / 不授予统一媒体许可

This collection does not claim ownership of the characters or third-party works it indexes. No blanket permission to redistribute, adapt, sell or commercially exploit its media is granted. All rights remain with their respective holders. Unknown authorship or permission is recorded explicitly.

本库不主张拥有所整理的角色或第三方作品，也不统一授予再分发、改编、销售或其他商用许可。各项权利归相应权利人；作者与授权未确认时会明确标记未知。

`rightsUnknown` is a per-item indicator. `rights.status`, `rights.license`, `creator` and `sourceURLs` preserve what is established in the reviewed catalog. `sourceLicenseClaims` records statements found in source evidence; it does not turn an upstream claim into verified media permission. `repositoryLicense` concerns the source repository's stated scope and must not be assumed to license its bundled images.

`rightsUnknown`、`rights.status`、`rights.license`、`creator` 和 `sourceURLs` 逐项保留已核对的信息。`sourceLicenseClaims` 仅记录来源材料中的声明，不代表声明已被证明适用于图片。`repositoryLicense` 保留上游仓库声明的适用范围，不自动覆盖其中的图片。

## Integrity and conversion / 文件完整性与转换

Media are copied byte-for-byte and checked against the full SHA-256 recorded in the library manifest. Watermarks and in-image credits are left intact. Animated files remain one item regardless of frame count. A converted cache preview is marked `isDerivative: true`, `fileRole: "converted-preview"` and placed under `previews/`; it is not claimed to match an unavailable original GIF. Collection dates are not creation dates.

媒体按完整 SHA-256 核验并逐字节复制，保留水印和图内署名；动图不按帧计算作品数。缓存转换预览标记 `isDerivative: true`、`fileRole: "converted-preview"`，单列于 `previews/`，不冒充与不可得原 GIF 相同的文件。收录日期不等于创作日期。

## Preserved notices / 保留声明

Original license notice files from the explicitly reviewed source repositories are kept in `LICENSES/third-party/` with their original bytes and checksums. `sources.json` lists each repository URL, reviewed revision, code-license label, scope note and associated notice files. README-only or absent license statements are described as such. An image whose rights are unknown remains unknown even if a source repository has an MIT code license.

明确审核过的上游仓库许可证原文保存在 `LICENSES/third-party/`，保留原始字节与校验值。`sources.json` 记录仓库链接、核对版本、代码许可名称、范围说明和相关声明文件。只有 README 声明或没有许可证时会如实记录；代码 MIT 不会改变图片权利未知的状态。

Other source notices are retained as selected, sanitized text under each item's `sourceLicenseClaims`. If source evidence refers to an unavailable companion notice, that limitation is retained; no missing notice is invented. Public source links have credentials, query strings and fragments removed. This can remove parameters used by an external site, so follow the source page or repository revision to investigate further.

When a historical source filename has the wrong extension, the exported filename follows the detected media container. Metadata retains `sourceDeclaredFormat` and `sourceFormatMismatch`; the bytes and full SHA-256 remain unchanged. `missingCompanionNotice` marks source claims that refer to a companion notice not provided with these inputs.

其他来源声明按字段白名单、去除敏感链接后保存在 `sourceLicenseClaims`。来源提到未取得的同名声明文件时，会保留这一限制，不补造缺失文件。公开链接移除凭证、查询参数和 fragment，可能失去第三方站点所需参数；进一步核对时请从对应来源页面或仓库版本查找。

历史源文件后缀与真实容器不一致时，导出文件使用检测到的实际容器后缀，同时保留 `sourceDeclaredFormat`、`sourceFormatMismatch`；字节和完整 SHA-256 不变。`missingCompanionNotice` 标记来源提到、但本批输入未提供的同名说明文件。

## Review and removal / 核对与移除

Use the private site report form for rights or privacy concerns when available. The maintainer assesses the supplied evidence and records the actual action taken. A report is not an automatic takedown. Repository history and independently made copies may persist after a file is removed from the latest tree; removal from this archive does not delete third-party copies.

版权或隐私问题请在网站可用时使用私有投诉表单。维护者会核对证据并记录实际处理动作，投诉不会自动下架。从最新目录移除文件后，Git 历史或他人的独立副本仍可能存在；本站移除不能删除第三方副本。
