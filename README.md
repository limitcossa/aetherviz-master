# AetherViz Master

<p align="center">
  <img src="https://img.shields.io/badge/version-4.0-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License">
  <img src="https://img.shields.io/badge/Three.js-r134-orange.svg" alt="Three.js">
  <img src="https://img.shields.io/badge/Tailwind-v3.4+-cyan.svg" alt="Tailwind">
</p>

<p align="center"><img width="2940" height="1596" alt="ScreenShot_2026-02-22_222904_390" src="https://github.com/user-attachments/assets/763cc0d4-3dc3-4b0b-8109-016e89d51ff2" />
<img width="2958" height="1616" alt="ScreenShot_2026-02-22_222836_162" src="https://github.com/user-attachments/assets/410c305a-c873-4013-8432-790e159bb091" />

  <strong>互动教育可视化建筑师</strong><br>
  把任意教学主题瞬间转化为沉浸式3D交互教学网页
</p>

---

## 特性

- **3D 可视化** - 基于 Three.js 的专业级 3D 场景，支持物理模拟、粒子系统、矢量可视化
- **自动学科识别** - 智能识别主题领域（物理/化学/生物/数学/天文/编程），自动切换配色主题
- **玻璃拟态 UI** - 现代化的赛博教育风格，优雅的半透明界面
- **实时交互** - 滑块实时控制参数，3D 场景即时响应
- **公式渲染** - 内置 KaTeX 支持，完美渲染数学公式
- **响应式设计** - 支持桌面端和移动端触控操作
- **零依赖** - 单 HTML 文件，无需构建工具，直接浏览器打开即可运行

---

## 快速开始

### 在线体验

访问 [AetherViz Master Demo](https://example.com) 查看在线演示（待部署）

### 本地运行

1. 克隆仓库：
```bash
git clone https://github.com/andyhu/aetherviz-master.git
cd aetherviz-master
```

2. 直接在浏览器中打开生成的 HTML 文件：
```bash
# 使用任意 HTTP 服务器
python -m http.server 8080
# 或
npx serve .
```

3. 在浏览器访问 `http://localhost:8080`

---

## 使用方式

### 通过 Claude Code 使用

1. 安装 Claude Code（如果尚未安装）
2. 启动 Claude Code
3. 输入 `/aetherviz-master` 或直接输入主题，例如：
   - 牛顿第二定律
   - 光合作用
   - 勾股定理
   - DNA复制
   - 电磁感应

系统将自动：
- 识别学科领域
- 生成对应的 3D 交互场景
- 输出完整的 HTML 文件

### 手动使用

生成的 HTML 文件可以直接：
- 保存为 `.html` 文件
- 用浏览器打开
- 分享给他人

---

## 支持的主题领域

| 学科 | 主题示例 | 配色 |
|------|----------|------|
| 物理 | 牛顿第二定律、电磁感应、相对论时间膨胀 | 蓝色渐变 |
| 化学 | 酸碱中和、光合作用、氧化还原 | 橙红渐变 |
| 生物 | DNA复制、细胞呼吸、遗传规律 | 翠绿渐变 |
| 数学 | 勾股定理、三角函数、概率论 | 金黄渐变 |
| 天文 | 行星运动定律、宇宙膨胀、黑洞 | 深蓝渐变 |
| 编程 | 算法复杂度、数据结构、设计模式 | 代码青渐变 |

---

## 技术栈

- **Three.js r134** - 3D 渲染引擎
- **Tailwind CSS v3.4+** - 样式框架
- **KaTeX** - 数学公式渲染
- **OrbitControls** - 3D 场景控制

---

## 项目结构

```
aetherviz-master/
├── README.md                 # 项目说明文档
├── LICENSE                   # MIT 许可证
└── docs/
    └── skill.md            # 技能定义文件
```

---

## 示例截图

### 牛顿第二定律
- 3D 场景展示力与加速度的关系
- 可调节质量、力的大小
- 实时显示速度、加速度矢量

### 光合作用
- 粒子系统展示光合作用过程
- 叶绿体内部结构可视化
- 氧气释放动画

### 勾股定理
- 动态几何图形
- 边长实时计算
- 交互式证明演示

---

## 常见问题

**Q: 生成的 HTML 文件可以在离线环境运行吗？**
A: 可以。HTML 文件通过 CDN 加载依赖，首次加载后浏览器会缓存。完全离线使用需下载所有 CDN 资源。

**Q: 支持手机端吗？**
A: 支持。场景支持触摸旋转、双指缩放，UI 响应式适配移动端。

**Q: 如何自定义主题色？**
A: 修改 HTML 中的 CSS 变量即可，详见 `skill.md`。

---

## 贡献指南

欢迎提交 Issue 和 Pull Request！

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/amazing-feature`)
3. 提交更改 (`git commit -m 'Add amazing feature'`)
4. 推送分支 (`git push origin feature/amazing-feature`)
5. 打开 Pull Request

---

## 许可证

MIT License - 详见 [LICENSE](LICENSE) 文件

---

## 致谢

- [Three.js](https://threejs.org/) - 优秀的 3D 引擎
- [Tailwind CSS](https://tailwindcss.com/) - 现代化的 CSS 框架
- [KaTeX](https://katex.org/) - 快速的数学公式渲染

---

<p align="center">
  用 ❤️ 打造 | 由 AetherViz Master 生成
</p>
