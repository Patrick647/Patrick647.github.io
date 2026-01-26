# 汪东旭个人学术网站 - 设计规范文档

## 📋 项目概览

**网站名称**: Dongxu Wang (汪东旭)  
**网站类型**: 个人学术网站  
**主题框架**: Hugo Blox (Academic Resume Template)  
**目标用户**: 学术研究人员、医疗专业人士、潜在合作者

---

## 🎨 视觉设计系统

### 配色方案

#### 主题模式
- **模式**: System (跟随系统设置)
- **主题包**: Default
- **可选**: 浅色/深色模式切换

#### 颜色配置
```yaml
主色调 (Primary): 默认主题色
次要色 (Secondary): 默认主题色
中性色 (Neutral): 灰度系统
```

#### 语义化颜色
- **背景色**: 自适应主题
- **前景色**: 自适应主题
- **头部背景**: 自适应主题
- **页脚背景**: 自适应主题

---

## 📝 排版系统

### 字体配置
- **字体系列**: Sans-serif (Inter)
- **备选方案**: 
  - Serif: Roboto Slab
  - Native: 系统字体
- **字体大小**: Medium (md)
- **可选尺寸**: sm, md, lg, xl

### 文本层级
```
标题层级:
- H1: 网站标题 "Dongxu Wang"
- H2: 区块标题 (如 "Research Focus", "Featured Publications")
- H3: 子标题
- Body: 正文内容
```

---

## 🏗️ 布局系统

### 间距设计
- **间距密度**: Comfortable (舒适)
- **可选密度**: compact, comfortable, spacious
- **默认区块间距**: 5rem

### 圆角设计
- **圆角大小**: Medium (md)
- **可选尺寸**: none, sm, md, lg, full

### 头像形状
- **形状**: Circle (圆形)
- **可选形状**: circle, square, rounded
- **尺寸**: Large

---

## 🧩 组件设计

### 1. 导航栏 (Header)

**配置**:
```yaml
样式: navbar (标准导航栏)
位置: 顶部固定 (sticky)
对齐: 居中 (center)
```

**功能模块**:
- ✅ 搜索功能
- ✅ 主题切换器
- ✅ 主题选择器
- ✅ 语言切换器
- ❌ CTA按钮 (未启用)

**导航项**:
- Home (首页)
- Publications (出版物)
- Projects (项目)
- Experience (经历)

---

### 2. 个人简介区块 (Biography Section)

**区块类型**: `resume-biography-3`

**内容元素**:
- **头像**: 大尺寸圆形头像
- **姓名**: Dongxu Wang (汪东旭)
  - 显示尺寸: Large
- **职位**: Pharmacist | Researcher | Health Communication Specialist
- **状态图标**: 💊
- **学位后缀**: MSc, RPh
- **代词**: he/him

**背景设计**:
- **渐变网格**: 启用
- **自适应**: 根据主题色自动调整

**行动按钮**:
- 文本: "Download CV"
- 链接: uploads/resume.pdf

**社交链接**:
- 📧 Email: Dongxu.2.Wang@outlook.com
- 💼 LinkedIn: linkedin.com/in/dongxu/
- 🐙 GitHub: github.com/Patrick647
- 🎓 ORCID: orcid.org/

---

### 3. 研究焦点区块 (Research Focus)

**区块类型**: `markdown`

**标题**: 🔬 Research Focus

**内容结构**:
```markdown
- **Pharmacist Competency Development** - 药师能力发展
- **Drug Information Visualization** - 药物信息可视化
- **Patient-centered Pharmaceutical Care** - 以患者为中心的药学服务
```

**布局**: 单列 (columns: 1)

---

### 4. 出版物区块 (Publications)

#### 4.1 精选出版物
**区块类型**: `collection`
- **视图**: article-grid
- **列数**: 2
- **筛选**: featured_only: true

#### 4.2 最近出版物
**区块类型**: `collection`
- **视图**: citation (引用格式)
- **引用样式**: APA

**出版物示例**:
1. **药品说明书改革研究** (Jiang 2025)
   - 标签: Drug Package Insert, Health Communication, Patient Education
   
2. **药师能力评估框架** (Wang 2025)
   - 标签: Pharmacist Competency, Delphi Method, Primary Healthcare

---

### 5. 研究项目区块 (Projects)

**区块类型**: `collection`
- **视图**: card (卡片视图)
- **列数**: 2

**项目列表**:
1. **Drug Insert Reform** - 药品说明书改革
2. **MTHFR Screening** - MTHFR基因筛查
3. **Pharmacist Competency** - 药师能力评估

---

### 6. 演讲展示区块 (Presentations)

**区块类型**: `collection`
- **视图**: card
- **内容源**: events 文件夹

---

### 7. 页脚 (Footer)

**配置**:
```yaml
样式: minimal (极简风格)
语言切换器: 启用
```

**版权信息**:
```
© {year} {name}. This work is licensed under {license}
许可证类型: Creative Commons
- 允许衍生作品: 否
- 相同方式共享: 是
- 允许商业使用: 否
```

---

## 📊 内容结构

### 个人信息

**基本信息**:
- 姓名: Dongxu Wang (汪东旭)
- 职位: Pharmacist | Researcher | Health Communication Specialist
- 机构: Wuxi Maternity and Child Health Care Hospital (无锡市妇幼保健院)
- 协会: Wuxi Pharmacists Association (无锡市药学会)

**研究兴趣**:
- Pharmacist Competency Development
- Drug Information Visualization
- Patient-centered Pharmaceutical Care
- Pharmacogenomics
- Health Communication

**教育背景**:
1. **MSc Clinical Pharmacology** - King's College London (2022-2023)
2. **Bachelor of Pharmacy** - China Pharmaceutical University (2019-2022)

**工作经历**:
1. **Pharmacist & Clinical Trial QA Officer** - Wuxi Maternity and Child Health Care Hospital (2018-至今)
2. **Committee Member & Executive Secretary** - Pharmaceutical Policy Committee, Wuxi Pharmacists Association (2024-至今)

**技能体系**:
- **实验室技能**: HPLC (5/5), Flow Cytometry (4/5), PCR (4/5), Electrochemical Sensor (4/5)
- **编程与数据分析**: R (4/5), Python (3/5), SPSS (4/5), LaTeX/Markdown (5/5)
- **多媒体制作**: Video Editing (4/5), Science Communication (5/5)

**语言能力**:
- 中文: 母语 (5/5)
- 英语: C1 熟练 (4/5)

**获奖荣誉**:
- Outstanding Reviewer of the Year (2025) - Pharmaceutical and Clinical Research
- Third Prize, 12th National Hospital Management Tools Conference (2024)
- First Prize, 9th Wuxi Municipal Hospital Pharmacy QCC Competition (2024)
- First Prize, 5th Jiangsu Provincial Hospital QCC Competition (2021)

---

## 🔧 功能特性

### 启用功能
- ✅ 搜索功能 (Pagefind)
- ✅ 主题切换 (浅色/深色)
- ✅ 语言切换
- ✅ 阅读时间估算
- ✅ 目录 (TOC)
- ✅ Google Analytics (G-018L3SJ2MG)

### 未启用功能
- ❌ 数学公式渲染
- ❌ 评论系统
- ❌ 仓库编辑链接
- ❌ 隐私模式

---

## 📱 响应式设计

### 视口适配
- **桌面端**: 完整导航栏 + 多列布局
- **平板端**: 自适应列数
- **移动端**: 单列布局 + 汉堡菜单

### 布局断点
- 出版物网格: 2列 → 1列
- 项目卡片: 2列 → 1列
- 导航栏: 完整 → 折叠

---

## 🎯 设计原则

### 1. 学术专业性
- 简洁清晰的排版
- 专业的配色方案
- 规范的引用格式 (APA)

### 2. 可访问性
- 高对比度文本
- 语义化HTML结构
- 键盘导航支持

### 3. 国际化
- 中英双语支持
- 多语言切换
- 本地化日期格式

### 4. 性能优化
- 按需加载 (Alpine.js)
- 图片优化
- 最小化CSS/JS

---

## 📐 设计规格

### 头像
- **尺寸**: Large
- **形状**: Circle
- **文件**: assets/media/authors/me.png

### 按钮
- **主按钮**: "Download CV"
- **样式**: 默认主题按钮样式
- **圆角**: Medium

### 卡片
- **阴影**: 默认主题阴影
- **圆角**: Medium
- **间距**: Comfortable

### 网格
- **列间距**: 默认主题间距
- **行间距**: 5rem (区块间)

---

## 🔗 技术栈

### 核心框架
- **静态站点生成器**: Hugo
- **主题**: Hugo Blox (Academic Resume)
- **前端框架**: Alpine.js
- **搜索引擎**: Pagefind

### 部署
- **托管平台**: Netlify (推荐)
- **域名**: 自定义域名 (CNAME)
- **SSL**: 自动配置

---

## 📝 内容管理

### 文件结构
```
content/
├── _index.md           # 首页配置
├── authors/            # 作者信息
│   └── me/
├── publications/       # 出版物
├── projects/          # 项目
├── events/            # 演讲活动
└── experience.md      # 工作经历
```

### 数据文件
```
data/
└── authors/
    └── me.yaml        # 个人详细信息
```

### 配置文件
```
config/_default/
├── hugo.yaml          # Hugo配置
├── params.yaml        # 主题参数
├── menus.yaml         # 导航菜单
├── languages.yaml     # 多语言配置
└── module.yaml        # 模块配置
```

---

## 🎨 设计资源

### 颜色参考
- 使用 Tailwind CSS 调色板
- 支持自定义十六进制颜色
- 自动生成深色模式变体

### 图标系统
- **Hero Icons**: UI图标
- **Brand Icons**: 社交媒体图标
- **Academic Icons**: 学术平台图标
- **自定义图标**: assets/media/icons/custom/

### 字体资源
- **Inter**: 主要无衬线字体
- **Roboto Slab**: 可选衬线字体
- **System Fonts**: 原生字体栈

---

## 📊 SEO优化

### 元数据
- **标题**: Dongxu Wang
- **描述**: 汪东旭 | 江南大学附属妇产医院临床药师 | Clinical Pharmacist specializing in pharmacogenomics and health communication
- **关键词**: Pharmacist, Researcher, Health Communication, Pharmacogenomics

### 结构化数据
- **类型**: Person
- **组织**: Wuxi Maternity and Child Health Care Hospital

### AI爬虫指引
- **允许**: / (所有公开内容)
- **禁止**: 无

---

## 🔄 更新日志

### 当前版本特性
- ✅ 响应式个人简介区块
- ✅ 渐变网格背景
- ✅ 出版物引用格式
- ✅ 项目卡片展示
- ✅ 多语言支持
- ✅ 主题切换功能

### 待优化项
- 🔲 数学公式支持
- 🔲 评论系统集成
- 🔲 博客功能扩展
- 🔲 课程内容展示

---

## 📞 联系方式

**网站所有者**: Dongxu Wang (汪东旭)  
**邮箱**: Dongxu.2.Wang@outlook.com  
**机构**: Wuxi Maternity and Child Health Care Hospital  

---

*本设计规范文档基于 Hugo Blox Academic Resume 模板创建，用于指导网站的视觉设计和内容组织。*

**文档版本**: 1.0  
**创建日期**: 2026-01-26  
**最后更新**: 2026-01-26
