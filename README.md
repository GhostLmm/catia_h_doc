# CATIA B30 Headers Documentation

## 项目简介

这是一个完整的 CATIA B30 头文件技术文档集合，提供了详细的 API 参考和开发指南。该项目将 CATIA B30 的所有头文件文档组织成一个易于浏览的静态网站。

## 🌐 在线访问

**网站地址**: [https://ghostlmm.github.io/catia_h_doc/](https://ghostlmm.github.io/catia_h_doc/)

## 📚 文档内容

本文档集包含以下主要模块：

- **System** - 系统核心功能
- **Mathematics** - 数学计算库
- **GeometricObjects** - 几何对象
- **GeometricOperators** - 几何操作
- **MechanicalModeler** - 机械建模
- **PartInterfaces** - 零件接口
- **ProductStructure** - 产品结构
- **Visualization** - 可视化功能
- **SketcherInterfaces** - 草图接口
- **DraftingInterfaces** - 工程图接口
- **KnowledgeInterfaces** - 知识工程接口
- **ManufacturingInterfaces** - 制造接口
- **SimulationInterfaces** - 仿真接口
- **ElectricalInterfaces** - 电气接口
- 以及更多专业模块...

## 🏗️ 项目结构

```
catia_h_doc/
├── B30_htmls/                 # 静态 HTML 文档文件
│   ├── index.html            # 主页面
│   ├── System/               # 系统模块文档
│   ├── Mathematics/          # 数学模块文档
│   ├── GeometricObjects/     # 几何对象文档
│   └── ...                   # 其他模块文档
├── .github/
│   └── workflows/
│       └── pages.yml         # GitHub Pages 自动部署配置
└── README.md                 # 项目说明文件
```

## 🚀 部署方式

本项目使用 GitHub Pages 和 GitHub Actions 实现自动部署：

1. **源码管理**: 所有文档源文件存储在 `B30_htmls/` 目录
2. **自动构建**: 当代码推送到 `main` 分支时自动触发部署
3. **静态托管**: 通过 GitHub Pages 提供在线访问

## 🔧 本地开发

如果需要在本地查看文档：

1. 克隆仓库：
   ```bash
   git clone https://github.com/GhostLmm/catia_h_doc.git
   ```

2. 进入文档目录：
   ```bash
   cd catia_h_doc/B30_htmls
   ```

3. 启动本地服务器：
   ```bash
   # 使用 Python
   python -m http.server 8000
   
   # 或使用 Node.js
   npx serve .
   ```

4. 在浏览器中访问：`http://localhost:8000`

## 📖 使用指南

1. **浏览模块**: 从主页选择感兴趣的功能模块
2. **搜索功能**: 使用浏览器内置搜索定位特定的 API
3. **导航面包屑**: 利用页面顶部的面包屑导航快速切换
4. **代码示例**: 查看各个接口的详细说明和用法示例

## 📝 更新说明

- **版本**: CATIA B30
- **最后更新**: 2025年8月
- **自动部署**: 每次代码更新都会自动重新部署网站

## 🤝 贡献

如果您发现文档中的问题或有改进建议，欢迎：

1. 提交 Issue 报告问题
2. 发起 Pull Request 贡献代码
3. 联系维护者讨论改进方案

## 📄 许可证

本项目仅供学习和技术交流使用。CATIA 是 Dassault Systèmes 的注册商标。

---

**维护者**: GhostLmm  
**仓库地址**: [https://github.com/GhostLmm/catia_h_doc](https://github.com/GhostLmm/catia_h_doc)  
**在线文档**: [https://ghostlmm.github.io/catia_h_doc/](https://ghostlmm.github.io/catia_h_doc/)