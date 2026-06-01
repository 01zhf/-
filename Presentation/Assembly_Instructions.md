Presentation assembly instructions

目的：把本分支中的 prompts、装饰 SVG 与示例数据合成为 12 页高审美国风手绘 PPTX（16:9）。

推荐工作流程（最快速/可重复）：
1. 使用你的图像生成器（Midjourney/Stable Diffusion/Leonardo 等）批量生成背景：
   - 在工具中逐条粘贴 Design/Slide_prompts/*.txt 的中文或英文 prompt，输出分辨率 3840x2160。
   - 生成后把文件命名为与建议文件名一致并上传到本仓库路径 Assets/Backgrounds/。

2. 在本地 PowerPoint 中打开一个空白 16:9 演示文稿：
   - 插入 > 背景图像：选择第一张背景 Slide01_Cover_bg.png 做封面，按 README 中的排版说明放置标题文本框与副标题。
   - 把装饰 SVG（Assets/Decorations/*.svg）导入为图片（或转换为 PNG）并放置在页面角落，调整透明度与大小以完成视觉统一。

3. 图表导入：
   - 打开 Data/Charts_Data.csv（或用 Excel 导入），将数据复制到 Excel 表并在 PowerPoint 中插入图表（折线/环形/柱形），应用颜色与样式（参见 Presentation/README.md 中的配色值）。

4. 字体与样式：
   - 推荐中文字体：思源宋体（标题）/ 思源黑体（正文字体）。如无思源可使用系统衬线/无衬线做替代。

5. 导出与提交：
   - 导出每页为 PNG（3840x2160）作为备份，并保存为可编辑 PPTX。把最终 PPTX 与背景 PNG 上传回本分支（Assets/Backgrounds/ + Presentation/）。

自动化选项（可选）：
- 若你希望我代为生成背景并合成 PPTX，你可以授权我使用一个图像生成 API 或授权我在本环境调用（请在安全渠道提供 API Key）。我将：
  1) 批量生成 12 张背景 PNG。  
  2) 在 headless PPTX 库中（python-pptx 或 libreoffice）把背景与文本、图表 SVG 合成到可编辑 PPTX。  

如需我代为生成并合成，请回复“授权生成并合成”，并给出你愿意使用的图像生成服务及相应授权信息（或允许我使用已配置的服务）。否则我将继续在该分支放置设计文件、prompts 与占位数据，等待你上传生成的 PNG，然后我再合成 PPTX。