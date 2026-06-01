# University Innovation Competition — 12页国风手绘PPT 交付包（占位版）

说明：
- 本分支包含完整的设计规范、每页 AI 背景生成提示词（中/英）、示例数据（CSV）、以及矢量装饰素材（SVG）。
- 由于当前环境无法直接生成高质量二进制 PPTX/PNG 图像，我已把所有可执行的设计资源、明确的 AI prompts 与可编辑数据文件放在下列路径，便于你或其他工具（如本地/云端的图像生成器）一键生成并合成最终 PPTX。

交付清单（已包含在本次提交）：
- Design/Slide_prompts/Slide01_prompt.txt ... Slide12_prompt.txt  （每页的 AI 背景提示词，中/英双语）
- Data/Charts_Data.csv （用于生成可编辑图表的示例/占位数据）
- Assets/Decorations/Seal_Gold.svg  （金色篆刻印章矢量）
- Assets/Decorations/Cloud_Left.svg / Cloud_Right.svg（水墨云纹矢量）
- Presentation/Assembly_Instructions.md （如何用这些素材在 PowerPoint 中批量生成并排版的逐步说明）
- Presentation/University_Innovation_Competition_12Slides_placeholder.txt （关于 PPTX 的说明与下一步可选操作）

下一步建议（任选其一）：
A) 我可以把这些 prompts 用你授权的图像服务（若你提供 API/密钥或允许我使用已连通的生成器）批量生成 4K 背景并把 PNG 自动上传到本分支，然后我再合成可编辑 PPTX 并提交。  
B) 你或你的团队利用本仓库中的 prompts 在本地或通用 AI 图像服务（Midjourney/Stable Diffusion/Leonardo 等）批量生成背景图片，然后把 PNG 上传到本分支（路径：Assets/Backgrounds/）。随后我将把它们合成为最终 PPTX 并提交。  
C) 如果你希望我直接在聊天中把完整 PPTX 以 Base64 导出（体积大），请明确同意并承受会话输出非常长的文本。

说明：我会在 PR 描述中附上样片预览（封面与一页数据页）的生成说明与截图（如果你选择让我生成图片并上传，我会先上传样片供你在线审阅）。

如果你确认我现在把这些文件提交到 feat/uni-innovation-ppt 分支（并在 PR 中放置样片说明），请在回复中写“继续提交并生成 PR”。