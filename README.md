# 信息类实验报告 LaTeX 模板

这是一个为信息类专业设计的实验报告 LaTeX 模板，适用于人工智能，自动化，计算机，电子信息等专业课程的实验报告和大作业撰写。模板结构清晰，样式美观，支持插图、表格、参考文献、代码等元素，适合各类工程类实验报告书写场景。

---

## �� 模板功能特色

- 默认使用 `XeLaTeX` 编译，兼容中文；
- 内置封面模板，可填写姓名、学号、课程名等基本信息；
- 自定义中文标题、目录、参考文献等字段；
- 支持公式、图表、子图、表格、代码块等常用实验内容；
- 提供 MATLAB / Python / C++ 代码块展示格式；
- 附带 `images/` 图片文件夹，用于插入实验图示；
- 可通过 `yibin.sty` 配置自定义样式（需自行补充）；
- 提供 `Overleaf` 推荐设置，方便在线编辑和预览。

---

## �� 如何将模板导入 Overleaf

### ✅ 方法一：使用 GitHub 导入

1. 打开 [Overleaf 官网](https://www.overleaf.com) 并登录账户；
2. 点击页面顶部的 `New Project > Import from GitHub`；
3. 复制粘贴你的 GitHub 仓库链接，例如：

   ```
   https://github.com/你的用户名/neu-latex-template
   ```

4. 点击导入，等待模板加载完成；
5. 编译器选择 `XeLaTeX`，点击左上角 `Recompile` 编译即可。

---

### ✅ 方法二：手动上传 ZIP 包

1. 在本项目 GitHub 页面点击绿色按钮 `Code > Download ZIP` 下载模板；
2. 打开 [Overleaf 官网](https://www.overleaf.com)，点击 `New Project > Upload Project`；
3. 选择刚刚下载的 `.zip` 文件上传；
4. 进入编辑器后，设置编译器为 `XeLaTeX`；
5. 点击 `Recompile` 编译查看效果。

---

## �� 推荐 Overleaf 设置

请在 Overleaf 中按以下方式配置项目设置：

- **Compiler（编译器）**: `XeLaTeX`  
- **TeX Live version**: `2024`  
- **Main document**: `main.tex`  
- **Spell check（拼写检查）**: `English (American)`  
- **Auto-complete**: `On`  
- **Auto-close brackets**: `On`  
- **Code check**: `On`  
- **Equation preview**: `On`  
- **Editor theme**: `textmate`  
- **Overall theme**: `Light`  
- **Font Size**: `12px`  
- **Font Family**: `Lucida / Source Code Pro`  
- **PDF Viewer**: `Overleaf`

---

## �� 文件结构说明

```text
├── main.tex               # 主文档入口
├── yibin.sty              # 自定义样式（可自行修改）
├── images/                # 存放插图资源（logo、图示等）
│   ├── logo.png           # 该文件可修改为你的学校或学院的标志
│   ├── plot.png
│   ├── image1.png
│   └── image2.png
├── README.md              # 项目说明文档（本文件）
```

---

## ✍ 使用说明

1. 打开 `main.tex`，填写封面中的基本信息；
2. 根据需要填写实验摘要、背景、方法、结果、分析和结论；
3. 若无需摘要，请注释掉相关部分；
4. 图片请放入 `images/` 文件夹，并通过 `\includegraphics` 引入；
5. 如需引用文献，请编辑文末的 `\begin{thebibliography}` 环节；
6. 编译方式建议使用 XeLaTeX，Overleaf 上直接编译预览即可；
7. **修改封面 Logo**：你可以修改 `images/logo.png` 文件，将其替换为你自己学校或学院的标志，以便个性化定制。

---

## �� 注意事项

- 本模板使用 `a4paper` 纸张设置；
- 支持中文自动换行与图表编号；
- 数学公式推荐使用 LaTeX 语法书写；
- 所有引用需配合 `\label{}` 和 `\ref{}` 语法使用；
- 如果你有自己的 `.bib` 文献库，可替换手动 `thebibliography` 环节；
- 如果在课程作业中使用此模板，请不要修改页眉内容，并注明模板来源以示尊重。模板的版权采用 [MIT License](LICENSE)，你可以自由使用、修改与传播，但请保留原作者的署名。


---

## �� 许可证（License）

本项目采用 [MIT License](LICENSE)，可自由使用、修改与传播。如在课程作业中使用，请注明模板来源以示尊重。

---

## ✨ 致谢

感谢东北大学人工智能专业课程教学团队的支持。本模板由刘艺彬编写与整理，欢迎交流与改进建议。

```

---

这样，用户可以方便地修改封面 Logo，替换为自己学校或学院的标志，同时确保在课程作业中使用时遵循必要的规定。