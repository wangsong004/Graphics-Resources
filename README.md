
# 图形学学习与资源总表（课程 / 代码库 / 数据库 / 会议 / 期刊 / 博客 / 视频）

> 这是一份适合长期收藏、持续增补的 **图形学资源总表**。  
> 我把内容分成：**公开课程、著名代码库、数据集/数据库、会议、期刊/杂志、博客网站、YouTube 频道** 几大块。  
> 整体偏向：**几何处理、几何建模、隐式表示、渲染、动画与仿真、工程实践**。

---

## 目录

- [1. 公开课程](#1-公开课程)
- [2. 著名代码库 / 工具链 / 标准](#2-著名代码库--工具链--标准)
- [3. 图形学相关数据库 / 数据集 / 资源仓库](#3-图形学相关数据库--数据集--资源仓库)
- [4. 会议与学术活动](#4-会议与学术活动)
- [5. 期刊 / 杂志 / 行业媒体](#5-期刊--杂志--行业媒体)
- [6. 博客 / 学习网站 / 论文索引](#6-博客--学习网站--论文索引)
- [7. YouTube / 视频频道 / 播客](#7-youtube--视频频道--播客)
- [8. 按方向给你的收藏建议](#8-按方向给你的收藏建议)
- [9. 维护建议](#9-维护建议)
- [10. 专题补充：更值得长期收藏的代码库 / 数据集 / 会议 / 期刊](#10-专题补充更值得长期收藏的代码库--数据集--会议--期刊)
- [11. 如果按“你的方向”继续精简收藏，我建议这样留](#11-如果按你的方向继续精简收藏我建议这样留)
- [12. 这份文档现在更适合拿来做什么](#12-这份文档现在更适合拿来做什么)
- [13. 几何处理 / Mesh / Implicit / Robust Geometry 专题地图](#13-几何处理--mesh--implicit--robust-geometry-专题地图)
- [14. 按任务找资源：实战入口表](#14-按任务找资源实战入口表)
- [15. 建议你单独拆出来长期维护的专题文件](#15-建议你单独拆出来长期维护的专题文件)

---

## 1. 公开课程

> 说明：这部分保留了“值得系统学一遍”的公开课程，尽量选 **官方课程页长期可访问** 的资源。  
> 其中“主讲人”以公开页面可查到的学期信息为主；部分课程不同学期会换老师。

### 1.1 入门 / 综合类

| 课程 | 主讲人 | 方向 | 资源形式 | 适合谁 | 链接 |
|---|---|---|---|---|---|
| GAMES101：现代计算机图形学入门 | 闫令琪（Lingqi Yan） | 图形学总览 | 视频 + 课件 | 中文入门首选 | [官方页](https://sites.cs.ucsb.edu/~lingqi/teaching/games101.html) |
| Stanford CS148 | 不同学期会变化；示例包含 Ron Fedkiw / Kevin Li / Sarah Jobalia | 图形学基础 / 成像 / 渲染 | 课程页 + slides | 想系统打基础 | [官方页](https://web.stanford.edu/class/cs148/) |
| CMU 15-462/662 | 不同学期会变化；示例包含 Keenan Crane / Jim McCann | 综合图形学 | 课程页 + lectures | 喜欢项目驱动学习 | [官方页](https://15462.courses.cs.cmu.edu/spring2024/) |
| UC Berkeley CS184/284A | 不同学期会变化；示例包含 Ren Ng / James O'Brien | 图形学与成像 | 课程页 + slides | 想做经典作业训练 | [官方页](https://cs184.eecs.berkeley.edu/) |
| MIT 6.837 | Wojciech Matusik / Frédo Durand | 传统图形学基础 | OCW 讲义 + 作业 | 想稳扎稳打复习一遍 | [官方页](https://ocw.mit.edu/courses/6-837-computer-graphics-fall-2012/) |
| Stanford CS248 | Kayvon Fatahalian / Doug James（示例学期） | 交互式图形学 | 课程页 + lecture materials | 想把基础图形和实时图形串起来 | [官方页](https://gfxcourses.stanford.edu/cs248/winter22) |
| Stanford CS248A | Kayvon Fatahalian（示例学期） | 渲染 / 几何 / 图像处理 | 课程页 + readings | 想学更现代的综合型 graphics 课 | [官方页](https://gfxcourses.stanford.edu/cs248a/winter23/courseinfo) |
| Utah CS4600 | Cem Yuksel / Jenny Han Lin（示例学期） | 现代图形学基础 | 官方课程页 + 预录视频 | 自学非常方便 | [官方页](https://graphics.cs.utah.edu/courses/cs4600/fall2025/) |

### 1.2 几何建模 / 几何处理

| 课程 | 主讲人 | 方向 | 资源形式 | 链接 |
|---|---|---|---|---|
| Stanford CS348A: Geometric Modeling and Processing | Leonidas Guibas（公开讲义学期） | 曲线曲面 / mesh / geometry processing | 课程资料 + slides | [Stanford Graphics Courses](https://graphics.stanford.edu/courses/) |
| Discrete Differential Geometry（DDG） | Keenan Crane | 几何处理数学基础 | 课程页 + notes + 视频 | [官方页](https://brickisland.net/ddg-web/) |
| MIT 6.8410: Shape Analysis | Justin Solomon | 形状分析 / 参数化 / 谱方法 | 课程页 + notes | [官方页](https://groups.csail.mit.edu/gdpgroup/68410_spring_2023.html) |
| MIT 2.158J: Computational Geometry | Nicholas Patrikalakis / Takashi Maekawa | CAD / CSG / 稳健几何 / 偏置 / 相交 | OCW 讲义 | [官方页](https://ocw.mit.edu/courses/2-158j-computational-geometry-spring-2003/) |

### 1.3 渲染 / 实时渲染

| 课程 | 主讲人 | 方向 | 资源形式 | 链接 |
|---|---|---|---|---|
| GAMES202：高质量实时渲染 | 闫令琪 | 现代实时渲染 | 视频 + 课件 | [官方页](https://sites.cs.ucsb.edu/~lingqi/teaching/games202.html) |
| Stanford CS348B: Image Synthesis Techniques | 不同学期会变化；示例包含 Kayvon Fatahalian / Doug James / Matt Pharr | 物理渲染 / 采样 / 光传输 | 课程页 + readings | [官方页](https://gfxcourses.stanford.edu/cs348b/spring22) |
| UCSB CS291A: Real-Time High Quality Rendering | Lingqi Yan | 专题型实时渲染 | slides + videos | [官方页](https://sites.cs.ucsb.edu/~lingqi/teaching/cs291a.html) |
| Utah CS5610/6610 | Cem Yuksel（示例学期） | OpenGL / GLSL / 实时图形编程 | 官方课程页 + 预录视频 | [官方页](https://graphics.cs.utah.edu/courses/cs6610/spring2025/) |

### 1.4 动画 / 仿真

| 课程 | 主讲人 | 方向 | 资源形式 | 链接 |
|---|---|---|---|---|
| Stanford CS348C: Animation and Simulation | Doug James | 动画 / 刚体 / 可变形体 / 流体 | 课程资料 | [官方页](https://graphics.stanford.edu/courses/cs348c/) |
| Cornell CS5643 | 不同学期会变化；示例包含 Steve Marschner / Doug James | 物理动画 | schedule + assignments | [官方页](https://www.cs.cornell.edu/courses/cs5643/2023sp/) |

### 1.5 实用补充

| 资源 | 方向 | 为什么值得看 | 链接 |
|---|---|---|---|
| libigl Tutorial | 几何处理实战 | 直接对应 C++ 工程实践，很多算法都能快速上手 | [教程](https://libigl.github.io/tutorial/) |
| Ray Tracing in One Weekend | 光线追踪入门 | 极适合快速写一个最小可用 ray tracer | [官网](https://raytracing.github.io/) |
| Scratchapixel | 图形学编程学习网站 | 解释细，适合把数学和实现连起来 | [官网](https://www.scratchapixel.com/) |

---

## 2. 著名代码库 / 工具链 / 标准

> 这部分优先选 **图形学里真正常见、长期有人用、且资料较完整** 的库。  
> 为了更好用，我按 **几何 / 渲染 / 体数据 / 标准格式 / 调试可视化** 来分。

### 2.1 几何建模 / 几何处理 / 网格方向

| 名称 | 类型 | 适合做什么 | 备注 | 链接 |
|---|---|---|---|---|
| CGAL | C++ 计算几何库 | 布尔、三角剖分、Voronoi、arrangement、mesh generation、几何鲁棒算法 | 偏“工业级 / 学术级” | [官网](https://www.cgal.org/) |
| libigl | C++ geometry processing 库 | Laplacian、参数化、变形、重建、常见网格算法原型开发 | 研究原型非常顺手 | [官网](https://libigl.github.io/) |
| geometry-central | 现代 C++ 几何处理库 | surface mesh / intrinsic geometry / 各类几何运算 | 很适合学习现代几何处理代码风格 | [官网](https://geometry-central.net/) |
| OpenMesh | 网格数据结构库 | half-edge / polygon mesh 表达与编辑 | 经典、老牌、文档成熟 | [官网](https://www.openmesh.org/) |
| OpenSubdiv | subdivision surface 库 | 细分曲面求值、动画和影视工作流 | Pixar 体系非常重要 | [官网](https://www.opensubdiv.org/) |
| TetGen | 四面体网格生成器 | tetrahedral meshing / constrained Delaunay / Voronoi | 做体网格、仿真前处理很常见 | [官网](https://wias-berlin.de/software/tetgen/) |
| Polyscope | 可视化与调试工具 | 交互查看 mesh / point cloud / scalar field / vector field | 调试几何算法特别舒服 | [官网](https://polyscope.run/) |

### 2.2 渲染 / 路径追踪 / 实时图形

| 名称 | 类型 | 适合做什么 | 备注 | 链接 |
|---|---|---|---|---|
| pbrt-v4 | 研究型渲染器 | 学习 physically based rendering / 路径追踪 / 光传输实现 | 配套书极强 | [官网](https://pbrt.org/) |
| Mitsuba 3 | 研究型渲染系统 | forward / inverse rendering、可微渲染、谱渲染 | 学术研究很常见 | [官网](https://www.mitsuba-renderer.org/) |
| Embree | 高性能 ray tracing 内核 | CPU 光线求交、BVH、离线渲染加速 | 做自研 renderer 常用 | [官网](https://www.embree.org/) |
| Vulkan Samples | 图形 API 示例工程 | Vulkan 入门与进阶示例 | 学现代 GPU API 很实用 | [官方仓库](https://github.com/KhronosGroup/Vulkan-Samples) |

### 2.3 体数据 / 隐式 / 稀疏体素

| 名称 | 类型 | 适合做什么 | 备注 | 链接 |
|---|---|---|---|---|
| OpenVDB | 稀疏体数据结构库 | fog / smoke / level set / 体素建模 / 稀疏体数据处理 | 影视工业标准级资源之一 | [官网](https://www.openvdb.org/) |
| NanoVDB | OpenVDB 的轻量 / GPU 友好版本 | 实时渲染、GPU 端体数据访问 | 对体渲染与实时方向很有用 | [官网](https://developer.nvidia.com/nanovdb) |

### 2.4 场景描述 / 材质 / 图像格式 / 色彩管理

| 名称 | 类型 | 适合做什么 | 备注 | 链接 |
|---|---|---|---|---|
| OpenUSD | 场景描述与交换标准 | 复杂 3D 场景组织、协作、跨 DCC/渲染器交换 | 现在非常重要 | [官网](https://openusd.org/) |
| MaterialX | 材质与 look-dev 标准 | 材质网络表达与交换 | 跨工具材质工作流很有价值 | [官网](https://materialx.org/) |
| Open Shading Language (OSL) | 着色语言 | 材质 / 光照 / displacement / 程序纹理 | 离线渲染体系常见 | [文档](https://open-shading-language.readthedocs.io/en/main/) |
| OpenEXR | HDR 图像格式 | 高动态范围图像、AOV、多通道输出 | 影视与高质量渲染必备 | [官网](https://openexr.com/) |
| OpenColorIO (OCIO) | 色彩管理 | 统一色彩空间与影视动画管线色彩管理 | VFX / animation 常用 | [官网](https://opencolorio.org/) |
---

## 3. 图形学相关数据库 / 数据集 / 资源仓库

> 这里把“数据库”理解为你做图形学时常会直接拿来用的数据资源。  
> 我按 **3D 形状 / 场景扫描 / 人体与动作 / 材质与环境资源** 来整理。

### 3.1 3D 形状 / CAD / 打印模型

| 名称 | 类型 | 主要内容 | 适合做什么 | 链接 |
|---|---|---|---|---|
| ShapeNet | 3D shape 数据集 | 大规模 3D 物体模型与类别层级 | shape retrieval、分类、生成、几何学习 | [官网](https://shapenet.org/) |
| ModelNet | 3D CAD 数据集 | 经典 CAD 类别数据集 | 基础 shape recognition / benchmark | [官网](https://modelnet.cs.princeton.edu/) |
| Objaverse / Objaverse-XL | 大规模 3D 对象数据集 | 海量带元数据的 3D 对象 | 3D 生成、多模态、检索、foundation model | [官网](https://objaverse.allenai.org/) |
| ABC Dataset | CAD / 曲面几何数据集 | 大规模 CAD 模型，带参数曲线曲面与几何真值 | 几何深度学习、特征检测、曲面重建 | [官网](https://deep-geometry.github.io/abc-dataset/) |
| Thingi10K | 3D 打印模型数据集 | 真实世界 3D 打印模型集合 | 网格质量分析、制造相关研究 | [官网](https://ten-thousand-models.appspot.com/) |

### 3.2 场景扫描 / 室内场景 / 三维重建

| 名称 | 类型 | 主要内容 | 适合做什么 | 链接 |
|---|---|---|---|---|
| ScanNet | RGB-D 场景数据集 | 室内扫描、相机位姿、重建与标注 | 重建、分割、室内场景理解 | [官网](https://www.scan-net.org/) |
| Matterport3D | 室内场景数据集 | 大规模真实室内空间的 RGB-D / 全景数据 | 场景重建、导航、view synthesis | [官网](https://niessner.github.io/Matterport/) |
| HM3D（Habitat Matterport 3D） | 高分辨率 3D 室内扫描集 | 大规模 building-scale 室内空间 | Embodied AI / 导航 / 场景理解 | [官网](https://aihabitat.org/datasets/hm3d/) |

### 3.3 人体 / 形变 / 动作

| 名称 | 类型 | 主要内容 | 适合做什么 | 链接 |
|---|---|---|---|---|
| FAUST | 人体表面数据集 | 高分辨率人体扫描与对应关系 | 非刚性配准、人体几何、对应学习 | [官网](https://faust-leaderboard.is.tuebingen.mpg.de/) |
| AMASS | 人体动作数据库 | 统一参数化的人体 mocap 数据 | 动画、运动建模、动作生成、SMPL 工作流 | [官网](https://amass.is.tue.mpg.de/) |

### 3.4 材质 / HDRI / 资产资源

| 名称 | 类型 | 主要内容 | 适合做什么 | 链接 |
|---|---|---|---|---|
| Poly Haven | 材质 / HDRI / 模型资源库 | CC0 材质、HDR 环境、模型 | 渲染测试、材质实验、环境光照 | [官网](https://polyhaven.com/) |
| Substance 3D Assets | 资产资源平台 | 材质、模型、灯光资产 | 产品可视化、DCC 流程、内容制作 | [官网](https://substance3d.adobe.com/assets) |

### 3.5 数据集选择建议

- **做 shape / mesh / geometry learning**：ShapeNet、ModelNet、Objaverse、ABC  
- **做网格质量 / 制造 / 真实模型分析**：Thingi10K  
- **做场景重建 / 室内扫描**：ScanNet、Matterport3D、HM3D  
- **做人体 / 非刚体 / 动作**：FAUST、AMASS  
- **做渲染测试 / HDRI / 材质**：Poly Haven  

> 备注：部分学术数据集可能需要注册、提交使用申请，或者仅限研究用途。

---

## 4. 会议与学术活动

> 这一部分我按“**综合旗舰** / **几何** / **渲染** / **动画** / **实时与交互** / **可视化与 XR**”来分。  
> 如果你只关注最核心的，先盯住 **SIGGRAPH / SIGGRAPH Asia / Eurographics / SGP / EGSR** 即可。

### 4.1 综合旗舰

| 名称 | 定位 | 你可以怎么用 | 链接 |
|---|---|---|---|
| SIGGRAPH | 图形学旗舰会议 | 看最新技术论文、课程、production、展会内容 | [官网](https://www.siggraph.org/) |
| SIGGRAPH Asia | 亚洲最重要的图形学旗舰会议之一 | 跟踪亚太区域研究与产业动态 | [官网](https://asia.siggraph.org/) |
| Eurographics | 欧洲图形学核心组织与年会 | 看欧陆 graphics 研究、课程、活动 | [官网](https://www.eg.org/) |
| Pacific Graphics | 亚太重要图形学会议 | 建模、渲染、动画、几何、应用都覆盖 | [示例官方页](https://pacificgraphics2026.github.io/) |

### 4.2 几何 / 建模 / 形状处理

| 名称 | 定位 | 链接 |
|---|---|---|
| Symposium on Geometry Processing (SGP) | geometry processing 顶级专门会议 | [示例官方页](https://sgp26.org/) |

### 4.3 渲染 / 光传输 / 图像合成

| 名称 | 定位 | 链接 |
|---|---|---|
| Eurographics Symposium on Rendering (EGSR) | 渲染方向核心会议之一 | [示例官方页](https://conferences.eg.org/egsr2025/) |

### 4.4 动画 / 物理仿真

| 名称 | 定位 | 链接 |
|---|---|---|
| Symposium on Computer Animation (SCA) | 动画、角色、仿真、时间相关现象 | [官网](https://computeranimation.org/) |

### 4.5 实时图形 / 游戏 / 交互

| 名称 | 定位 | 链接 |
|---|---|---|
| ACM SIGGRAPH Symposium on Interactive 3D Graphics and Games (I3D) | 实时 3D 图形与人机交互核心会议 | [官网](https://i3dsymposium.org/) |

### 4.6 可视化 / XR（与图形学交叉很深）

| 名称 | 定位 | 备注 |
|---|---|---|
| IEEE VIS | 可视化旗舰会议 | 如果你关心 visualization / scientific vis，很重要 |
| EuroVis | 欧洲可视化核心会议 | 与 TVCG 生态联系紧密 |
| IEEE VR | VR/AR/MR 核心会议 | 做 XR / rendering / interaction 时很值得关注 |

> 这些会议很多年会页面会按年份变动，因此长期收藏时建议同时记住“组织主页”和“当年官网”。

---

## 5. 期刊 / 杂志 / 行业媒体

### 5.1 学术期刊

| 名称 | 类型 | 适合看什么 | 链接 |
|---|---|---|---|
| ACM Transactions on Graphics (TOG) | 学术期刊 | SIGGRAPH / SIGGRAPH Asia 论文生态非常重要的一部分 | [官网](https://dl.acm.org/journal/tog) |
| Computer Graphics Forum (CGF) | 学术期刊 | Eurographics / SGP / Pacific Graphics 等生态里很常见 | [官网](https://onlinelibrary.wiley.com/journal/14678659) |
| IEEE Transactions on Visualization and Computer Graphics (TVCG) | 学术期刊 | visualization / graphics / VR / geometry 交叉研究 | [官网](https://www.computer.org/csdl/journal/tg) |

### 5.2 杂志 / 行业向出版物

| 名称 | 类型 | 适合看什么 | 链接 |
|---|---|---|---|
| IEEE Computer Graphics and Applications (CG&A) | 杂志 / 应用与桥梁型出版物 | 教程、综述、应用方向文章，比较适合扩展视野 | [官网](https://www.computer.org/csdl/magazine/cg) |
| Computer Graphics World (CGW) | 行业媒体 / 杂志 | VFX、动画、游戏、CAD、制作案例与行业动态 | [官网](https://www.cgw.com/) |
| fxguide | 行业媒体 | VFX、虚拟制作、影视图形、pipeline、制作幕后 | [官网](https://www.fxguide.com/) |

---

## 6. 博客 / 学习网站 / 论文索引

> 这一节非常重要。  
> 真正长期有用的，往往不是“某一篇文章”，而是这些可以反复回去查的资源站。

### 6.1 学习网站 / 技术博客

| 名称 | 类型 | 适合看什么 | 链接 |
|---|---|---|---|
| Scratchapixel | 系统学习网站 | 从数学到渲染实现的系统化入门 | [官网](https://www.scratchapixel.com/) |
| Ray Tracing in One Weekend | 在线书 / 学习站 | 写最小 ray tracer | [官网](https://raytracing.github.io/) |
| Real-Time Rendering Blog | 新闻 / 博客 | 实时渲染、书籍勘误、业界新动向 | [官网](https://www.realtimerendering.com/blog/) |
| Inigo Quilez | 个人技术网站 | SDF、程序纹理、距离场、创意数学图形 | [官网](https://iquilezles.org/) |
| Nathan Reed | 个人技术博客 | 图形编程、纹理、BRDF、GPU 细节 | [官网](https://www.reedbeta.com/) |
| Bart Wronski | 个人技术博客 | 实时渲染、图像处理、工程与研究落地 | [官网](https://bartwronski.com/) |
| Matt Pharr's Blog | 个人技术博客 | 采样、渲染、pbrt 相关深入讨论 | [官网](https://pharr.org/matt/blog/) |

### 6.2 论文追踪 / 资源索引

| 名称 | 类型 | 为什么重要 | 链接 |
|---|---|---|---|
| Ke-Sen Huang's Home Page / Resource for Computer Graphics | 论文索引 / 资源总表 | 收集很多 graphics 会议论文、视频、课程、海报、资源链接 | [主页](https://kesen.realtimerendering.com/) |
| ACM SIGGRAPH Conferences | 官方会议入口 | 查 SIGGRAPH / SIGGRAPH Asia 会议主页与活动 | [官网](https://www.siggraph.org/siggraph-events/conferences/) |
| Eurographics Conference Host | 官方会议入口 | 查 EGSR、Eurographics 等系列会议页 | [官网](https://conferences.eg.org/) |
---

## 7. YouTube / 视频频道 / 播客

> 这里优先放 **长期有价值** 的频道，而不是“只火一阵”的内容号。

### 7.1 YouTube 频道

| 名称 | 适合看什么 | 链接 |
|---|---|---|
| ACM SIGGRAPH | 官方会议视频、讲座、宣传片、活动内容 | [频道](https://www.youtube.com/user/ACMSIGGRAPH) |
| Inigo Quilez | SDF、shader、创意数学图形、“Painting with Maths” | [频道](https://www.youtube.com/c/InigoQuilez) |
| Freya Holmér | 数学、图形、shader、game dev 中最难讲清的部分 | [频道](https://www.youtube.com/%40acegikmo) |
| Sebastian Lague | 图形编程、可视化、shader、算法动画演示 | [频道](https://www.youtube.com/c/SebastianLague) |
| Two Minute Papers | 图形学 / AI / 生成 / 论文速读 | [频道](https://www.youtube.com/%40twominutepapers) |
| Scratchapixel | 图形学编程学习视频 | [频道](https://www.youtube.com/channel/UCN8fVZZ1vqQPSJywboQ_N7w) |
| NVIDIA | GPU、实时图形、研究展示、GTC 图形内容 | [频道](https://www.youtube.com/nvidia) |

### 7.2 值得单独记住的内容类型

- **SIGGRAPH 论文视频 / Technical Papers 相关介绍**
- **Inigo Quilez 的 SDF / raymarching / procedural 系列**
- **Freya Holmér 的 Math for Game Devs**
- **Sebastian Lague 的 shader / rendering / simulation 视频**
- **NVIDIA Research / GTC 里的图形研究演讲**

### 7.3 播客 / 行业音频

| 名称 | 适合看什么 | 链接 |
|---|---|---|
| fxpodcast / The VFXShow | 影视视效、虚拟制作、pipeline、行业制作细节 | [fxguide 播客页](https://www.fxguide.com/fxpodcasts/) |

---

## 8. 按方向给你的收藏建议

### 8.1 如果你主攻几何处理 / mesh / solid geometry / robust geometry

**课程**
- Stanford CS348A
- DDG
- MIT 2.158J
- MIT 6.8410
- libigl Tutorial

**代码库**
- CGAL
- libigl
- geometry-central
- OpenMesh
- TetGen
- Polyscope

**数据库 / 数据集**
- ShapeNet
- ABC Dataset
- Thingi10K
- FAUST

**会议 / 期刊**
- SGP
- SIGGRAPH
- Eurographics
- TOG
- CGF

**网站**
- Ke-Sen Huang
- Scratchapixel
- Inigo Quilez

### 8.2 如果你更偏隐式建模 / SDF / 体数据 / 稀疏体素

**重点收藏**
- OpenVDB
- NanoVDB
- Inigo Quilez
- pbrt-v4
- Mitsuba 3
- OpenUSD
- MaterialX
- OpenEXR

**数据资源**
- Objaverse
- ShapeNet
- Poly Haven

### 8.3 如果你想补渲染 / 实时图形

**课程**
- GAMES202
- Stanford CS348B
- UCSB CS291A
- Utah CS5610/6610

**代码库**
- Embree
- pbrt-v4
- Mitsuba 3
- Vulkan Samples
- OpenColorIO
- OpenEXR

**会议**
- SIGGRAPH
- SIGGRAPH Asia
- EGSR
- I3D

**博客 / 视频**
- Real-Time Rendering Blog
- Bart Wronski
- Nathan Reed
- ACM SIGGRAPH
- Freya Holmér
- Sebastian Lague

---

## 9. 维护建议

### 9.1 推荐你怎么使用这份 Markdown

- 把它当成 **个人图形学资源总目录**
- 每次看到好资源，只往对应分区里加
- 优先保留：
  - 官方主页
  - 官方文档
  - 官方课程页
  - 官方 YouTube
  - 官方论文索引页

### 9.2 建议你再继续拆成 4 个子文件

后面你可以把它继续拆成：

1. **graphics_courses.md**  
2. **graphics_libraries_and_datasets.md**  
3. **graphics_venues_and_publications.md**  
4. **graphics_blogs_and_videos.md**  

这样后续维护会更轻松。

### 9.3 这一版的核心价值

这一版不是只给你“看一眼”的清单，而是更像一个：

- **图形学学习地图**
- **工程资源导航页**
- **论文与社区入口页**
- **后续可持续维护的个人知识索引**

---

> 你后面如果愿意，可以继续在这份基础上再扩两个专题版：  
> **A. 几何处理 / Mesh / Implicit / Robust Geometry 专题版**  
> **B. 渲染 / Path Tracing / Realtime / Shader 专题版**


---

## 10. 专题补充：更值得长期收藏的代码库 / 数据集 / 会议 / 期刊

> 这一节是对前面内容的**增强版补充**，重点偏向：  
> **mesh / 几何处理 / implicit / robust geometry / CAD / 图形工程实践**。  
> 如果你以后还要继续扩，这一节最适合先加内容。

### 10.1 代码库 / 工具链：继续补充

#### A. 几何处理 / 网格工具

| 名称 | 类型 | 适合做什么 | 为什么值得收藏 | 链接 |
|---|---|---|---|---|
| Geogram | 几何算法库 | Delaunay、Voronoi、几何处理、参数化、数值几何 | 偏“研究成果沉淀成库”，很适合几何方向收藏 | [官网](https://brunolevy.github.io/geogram/index.html) |
| Polygon Mesh Processing Library (PMP) | C++ 网格处理库 | SurfaceMesh、简化、重网格、细分、平滑、曲率 | 风格现代、文档清楚，适合做网格原型 | [官网](https://www.pmp-library.org/) |
| MeshLab | 网格处理软件 / 工具链 | 清理、修复、简化、法线、重建、纹理、格式转换 | 做扫描数据、三角网格清洗非常常用 | [官网](https://www.meshlab.net/) |
| Open3D | 3D 数据处理库 | 点云、三角网格、重建、可视化、C++/Python 原型 | 如果你想连点云 / 深度数据 / mesh 一起做，很值得收藏 | [官网](https://www.open3d.org/) |
| Assimp | 3D 资产导入库 | 统一读写多种 3D 格式 | 图形工程里“资产导入”很常见 | [官网](https://assimp.org/) |

#### B. 渲染 / 可视化 / 工程基础设施

| 名称 | 类型 | 适合做什么 | 为什么值得收藏 | 链接 |
|---|---|---|---|---|
| OSPRay | CPU 光线追踪 / 可视化框架 | 科学可视化、体渲染、离线 / 交互式 CPU 渲染 | Intel 体系里很重要的可视化资源 | [官网](https://www.ospray.org/) |
| Blender | 开源 DCC 软件 | 建模、材质、动画、几何节点、脚本工具 | 不只是软件，也是非常重要的图形生态入口 | [官网](https://www.blender.org/) |
| OpenImageIO | 图像 I/O 工具库 | 多格式图像读取、纹理管线、AOV / HDR 图像处理 | 做渲染器和图形工具时经常会用到 | [官网](https://openimageio.readthedocs.io/) |

#### C. 图形标准 / 文件格式 / 交换生态

| 名称 | 类型 | 适合做什么 | 备注 | 链接 |
|---|---|---|---|---|
| glTF | 3D 资产传输标准 | 轻量场景 / 模型交换、Web / 引擎资产交付 | 现在非常重要的运行时 3D 资产格式 | [官方页](https://www.khronos.org/gltf/) |
| glTF Registry | 官方规范入口 | 查 glTF 2.0 规范与扩展 | 做格式兼容、导入导出时很有用 | [Registry](https://registry.khronos.org/glTF/) |
| glTF Validator | 官方验证工具 | 检查 glTF / GLB 文件合法性 | 做资产管线和格式排错很好用 | [官方工具](https://github.khronos.org/glTF-Validator/) |
| KTX 2.0 | GPU 纹理标准 | 纹理压缩与跨平台纹理传输 | 和 glTF 工作流关联很深 | [官方页](https://www.khronos.org/ktx/) |
| Draco | 几何压缩库 | mesh / point cloud 压缩 | Web / 传输 / 轻量化资产很常见 | [官网](https://google.github.io/draco/) |

### 10.2 数据集 / 数据库：继续补充

#### A. 形状 / 几何 / CAD 方向

| 名称 | 类型 | 主要内容 | 适合做什么 | 链接 |
|---|---|---|---|---|
| TOSCA | 非刚性形状数据集 | 经典非刚体形状匹配数据 | correspondence / non-rigid benchmarking | [官网](http://tosca.cs.technion.ac.il/) |
| 3D-FUTURE | 3D 家具模型数据集 | 高质量家具 CAD 模型与场景资源 | 室内场景、资产建模、生成任务 | [官网](https://3dfuture-dataset.github.io/) |
| YCB Object and Model Set | 物体模型基准 | 常见物体的 3D 模型与基准资源 | 机器人 / 6D pose / 感知 / 资产测试 | [官网](https://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/) |

#### B. 人体 / 动作 / 动态几何

| 名称 | 类型 | 主要内容 | 适合做什么 | 链接 |
|---|---|---|---|---|
| DFAUST | 动态人体 4D 数据集 | 带时间序列的高分辨率动态人体网格 | 动态配准、非刚体形变、时序几何 | [官网](https://dfaust.is.tue.mpg.de/) |
| SMPL | 参数化人体模型 | 可学习 / 可驱动的人体参数模型 | 动画、人形重建、动作研究 | [官网](https://smpl.is.tue.mpg.de/) |

#### C. 你更可能会用到的搭配方式

- **做 shape / mesh / 几何学习**：ShapeNet + ABC + TOSCA + DFAUST  
- **做制造 / 网格质量 / 真实模型问题**：Thingi10K + YCB  
- **做室内场景 / 大场景扫描**：ScanNet + Matterport3D + HM3D + 3D-FUTURE  
- **做人体 / 非刚体 / 动画**：FAUST + DFAUST + AMASS + SMPL  

### 10.3 会议：继续补充

> 前面已经列了最核心的一批。这里再补一些你以后大概率会碰到的会议。

| 名称 | 方向 | 你可以怎么理解它 | 链接 |
|---|---|---|---|
| High-Performance Graphics (HPG) | 渲染 / GPU / 高性能图形 | 更偏图形系统、GPU、加速结构、渲染性能 | [官网](https://www.highperformancegraphics.org/) |
| Computer Graphics International (CGI) | 综合图形学 | 老牌图形学会议，覆盖面较广 | [官网](https://www.cgs-network.org/cgi/) |
| Shape Modeling International (SMI) | 几何建模 / 形状分析 | 更偏 shape / modeling / geometry | [官网](https://smi2026.github.io/) |
| Computer Animation and Social Agents (CASA) | 动画 / 虚拟人 / 社会代理 | 动画与角色相关方向会碰到 | [官网](https://casa2025.github.io/) |
| ACM VRST | VR / AR / 交互式 3D | XR、交互、沉浸式图形方向常见 | [官网](https://vrst.acm.org/) |

### 10.4 期刊：继续补充

> 这一组更适合你这种会碰到 **CAD / 曲线曲面 / 几何建模 / 网格处理 / 工程图形** 的人。

| 名称 | 类型 | 更偏什么方向 | 链接 |
|---|---|---|---|
| Computer-Aided Design (CAD) | 学术期刊 | CAD、几何设计、拓扑 / 空间 / 配置设计问题 | [官网](https://www.sciencedirect.com/journal/computer-aided-design) |
| Computer Aided Geometric Design (CAGD) | 学术期刊 | 曲线曲面、几何表示、几何建模与处理 | [官网](https://www.sciencedirect.com/journal/computer-aided-geometric-design) |
| Computers & Graphics | 学术期刊 | 交互式图形、图形应用、模型、算法、可视化 | [官网](https://www.sciencedirect.com/journal/computers-and-graphics) |
| The Visual Computer | 学术期刊 | 图形学与 visual computing 的综合方向 | [官网](https://link.springer.com/journal/371) |

### 10.5 博客 / 学习网站：继续补充

| 名称 | 类型 | 为什么值得收藏 | 链接 |
|---|---|---|---|
| LearnOpenGL | 系统学习站 | 学现代 OpenGL 的经典入口，清楚、完整、工程导向强 | [官网](https://learnopengl.com/) |
| Khronos Blog | 官方博客 | glTF、KTX、Vulkan 等开放图形标准动态 | [官网](https://www.khronos.org/blog) |
| Red Blob Games | 交互式技术讲解网站 | 更偏可视化、地图、路径与交互式讲解设计；启发很好 | [官网](https://www.redblobgames.com/) |

### 10.6 视频 / 频道：继续补充

| 名称 | 类型 | 更适合看什么 | 链接 |
|---|---|---|---|
| GDC | 演讲视频生态 | 游戏图形、渲染、工具链、制作经验 | [GDC YouTube](https://www.youtube.com/@GDC) |
| Blender | 官方频道 | Blender 新功能、几何节点、艺术与技术结合 | [官方频道](https://www.youtube.com/@BlenderOfficial) |
| Khronos Group | 官方频道 | glTF、OpenXR、Vulkan、开放图形标准生态 | [官方频道](https://www.youtube.com/@KhronosGroup) |

---

## 11. 如果按“你的方向”继续精简收藏，我建议这样留

### 11.1 最该常驻浏览器书签的 12 个入口

1. [CGAL](https://www.cgal.org/)  
2. [libigl](https://libigl.github.io/)  
3. [geometry-central](https://geometry-central.net/)  
4. [Geogram](https://brunolevy.github.io/geogram/index.html)  
5. [PMP Library](https://www.pmp-library.org/)  
6. [OpenVDB](https://www.openvdb.org/)  
7. [Embree](https://www.embree.org/)  
8. [OpenUSD](https://openusd.org/)  
9. [SIGGRAPH](https://www.siggraph.org/)  
10. [SGP](https://sgp26.org/)  
11. [Computer-Aided Design](https://www.sciencedirect.com/journal/computer-aided-design)  
12. [Ke-Sen Huang Resource Page](https://kesen.realtimerendering.com/)  

### 11.2 如果你后面要单独拆专题文件，我建议拆成这 6 本

1. `graphics_courses_and_tutorials.md`  
2. `graphics_geometry_mesh_implicit.md`  
3. `graphics_rendering_realtime_shader.md`  
4. `graphics_datasets_and_assets.md`  
5. `graphics_venues_publications.md`  
6. `graphics_blogs_channels_and_news.md`  

### 11.3 我建议你以后往这份文档里继续补的内容

- **几何处理经典论文列表**  
- **隐式建模 / SDF / level set / neural implicit 资料专区**  
- **mesh 布尔 / arrangement / solid geometry 资料专区**  
- **仿真 / cloth / FEM / fluid 资料专区**  
- **开源渲染器与 shader 学习路线**  

---

## 12. 这份文档现在更适合拿来做什么

现在这份 Markdown 不只是“课程清单”，而更像一个：

- **图形学学习地图**
- **代码库 / 数据集 / 论文会议导航页**
- **几何处理与渲染的长期收藏目录**
- **后续可以不断增补的个人知识手册**

> 下一步最适合继续做的，是把它再拆出一份：  
> **《几何处理 / Mesh / Implicit / Robust Geometry 专题版》**  
> 这样你查资料时会更顺。


---

## 13. 几何处理 / Mesh / Implicit / Robust Geometry 专题地图

> 这一节专门偏向你的方向：  
> **mesh processing / robust geometry / solid geometry / implicit modeling / tetrahedral meshing / CAD 几何内核**。  
> 我尽量不做“泛泛列举”，而是按**用途**来归类。

### 13.1 先看这张总图：不同任务先从哪类资源入手

| 你要做的事 | 先看什么 | 再补什么 | 典型资源 |
|---|---|---|---|
| 三角网格基础处理 | 轻量 C++ 几何库 | 可视化 / 清理工具 | libigl / PMP / OpenMesh / MeshLab |
| 曲率、拉普拉斯、参数化、谱几何 | geometry processing 库 + 课程 | 数学补强 | geometry-central / libigl / DDG |
| 布尔、CSG、稳定实体运算 | 鲁棒几何库 / solid kernel | CAD 内核 / 体数据方案 | CGAL / Manifold / OCCT / OpenVDB |
| 表面转体网格 | 四面体网格工具 | 质量优化 / robust meshing | TetGen / TetWild / fTetWild / Gmsh |
| 扫描数据 / 点云 / RGB-D 到 mesh | 3D 数据处理库 | 清理与重建工具 | Open3D / MeshLab / ScanNet |
| 隐式建模 / SDF / functional representation | 隐式几何库 | 稀疏体素 / 神经隐式资料 | libfive / OpenVDB / NanoVDB |
| CAD / 曲线曲面 / B-rep / STEP | CAD kernel / 交换格式 | 网格化 / 有限元工具 | OCCT / Gmsh / glTF / USD |
| 大规模形状研究 / 几何学习 | 形状数据集 | benchmark / 论文会议 | ShapeNet / ABC / Objaverse / SGP |

### 13.2 重点代码库：更偏几何 / 网格 / 鲁棒几何

#### A. 轻量几何处理 / 曲面网格算法

| 名称 | 核心定位 | 适合做什么 | 什么时候优先考虑 | 链接 |
|---|---|---|---|---|
| libigl | 轻量级 geometry processing 库 | Laplacian、参数化、变形、重网格、法向/曲率、几何优化原型 | 你想快速做算法原型，且不想背太重框架 | [官网](https://libigl.github.io/) |
| geometry-central | 现代 C++ 曲面网格与几何处理库 | Surface mesh 数据结构、intrinsic / extrinsic 几何、DDG 风格算法 | 你更想要“现代接口 + 几何概念清楚” | [官网](https://geometry-central.net/) |
| PMP Library | 现代 polygon mesh 库 | 网格简化、细分、平滑、重网格、曲率分析 | 想要结构清爽、工程上也好落地 | [官网](https://www.pmp-library.org/) |
| OpenMesh | 多边形网格数据结构库 | Halfedge mesh、属性、拓扑编辑、算法基础设施 | 你需要一个成熟经典的网格数据结构底座 | [官网](https://www.openmesh.org/) |
| Geogram | 偏研究型几何算法库 | Delaunay / Voronoi、参数化、几何优化、数值几何 | 想看更“研究成果沉淀成库”的路线 | [官网](https://brunolevy.github.io/geogram/index.html) |

#### B. 鲁棒几何 / 实体 / CAD kernel

| 名称 | 核心定位 | 适合做什么 | 为什么重要 | 链接 |
|---|---|---|---|---|
| CGAL | 经典计算几何库 | 布尔、三角剖分、AABB、网格处理、点集、PMP、Nef / arrangement 等 | 功能面最广、文献基础最深 | [官网](https://www.cgal.org/) |
| Manifold | 拓扑鲁棒 triangle mesh 几何库 | manifold mesh 布尔、实体式网格操作、稳定输出 | 偏“给你可用且稳定的实体网格输出” | [官网 / GitHub](https://github.com/elalish/manifold) |
| Open CASCADE Technology (OCCT) | 开源 CAD kernel | B-rep、曲面/实体建模、STEP/IGES 交换、可视化 | 一旦你碰 CAD / B-rep / STEP，就很值得看 | [官方文档](https://dev.opencascade.org/doc/overview/html/) |
| libfive | functional representation / implicit solid kernel | 参数化程序化建模、SDF / f-rep 风格建模、脚本化 solid modeling | 做隐式建模时非常有代表性 | [官网](https://libfive.com/) |
| OpenVDB | 稀疏体素 / 体数据框架 | level set、体素化、隐式体表示、稀疏 volume 管线 | 你做隐式体、体素、体渲染、SDF 都会用到 | [官网](https://www.openvdb.org/) |

#### C. 表面转体网格 / 网格生成 / 有限元前处理

| 名称 | 核心定位 | 适合做什么 | 备注 | 链接 |
|---|---|---|---|---|
| TetGen | 四面体网格生成 | constrained Delaunay tetrahedralization、体网格生成 | 经典、学术和工程都常见 | [官网](https://wias-berlin.de/software/tetgen/) |
| TetWild | robust tetrahedral meshing | 更“野外输入”风格的鲁棒体网格 | 适合复杂、脏输入表面 | [官网](https://wildmeshing.github.io/tetwild/) |
| fTetWild | TetWild 的更快版本 | 快速 robust tetrahedral meshing | 更偏实用和性能 | [GitHub](https://github.com/wildmeshing/fTetWild) |
| Gmsh | 通用网格生成器 | 2D/3D meshing、CAD + mesh + post-processing | 工程链条里很常见 | [官网](https://gmsh.info/) |

#### D. 预处理 / 清理 / 原型验证

| 名称 | 更像什么 | 最适合用在什么阶段 | 链接 |
|---|---|---|---|
| MeshLab | GUI 工具箱 | 看模型、清理模型、格式转换、扫描后处理 | [官网](https://www.meshlab.net/) |
| Open3D | 3D 数据处理框架 | 点云 / RGB-D / 重建 / mesh 原型 | [官网](https://www.open3d.org/) |
| Blender | DCC 与可视化平台 | 快速检查几何、建小工具、Geometry Nodes 验证想法 | [官网](https://www.blender.org/) |
| Assimp | 资产导入库 | 各种模型格式导入导出前处理 | [官网](https://assimp.org/) |

### 13.3 你这种方向最有用的数据集

#### A. 形状 / CAD / 工程几何

| 名称 | 更偏什么 | 你为什么会用到 | 链接 |
|---|---|---|---|
| ShapeNet | 通用 3D 形状 | 做 shape analysis、检索、分类、几何学习的经典入口 | [官网](https://shapenet.org/) |
| ABC Dataset | CAD 模型 + 显式参数曲面/曲线信息 | 做 CAD、patch、特征线、几何学习非常合适 | [官网](https://deep-geometry.github.io/abc-dataset/) |
| Thingi10K | 真实 3D 打印模型 | 做“野外网格”问题、拓扑脏数据、打印相关处理非常好 | [官网](https://ten-thousand-models.appspot.com/) |
| Objaverse / Objaverse-XL | 超大规模 3D 对象库 | 大规模资产、3D 生成、检索、训练数据 | [官网](https://objaverse.allenai.org/) |

#### B. 场景 / RGB-D / 重建

| 名称 | 更偏什么 | 用途 | 链接 |
|---|---|---|---|
| ScanNet | 室内场景 RGB-D / reconstruction | 场景重建、实例/语义、mesh + RGB-D 研究 | [官网](https://www.scan-net.org/) |
| Matterport3D | 大尺度室内场景 | 场景理解、导航、重建、视觉与图形交叉 | [官网](https://niessner.github.io/Matterport/) |
| HM3D | 高分辨率数字孪生场景 | 大场景、 embodied AI、导航与视觉仿真 | [官网](https://aihabitat.org/datasets/hm3d/) |

#### C. 人体 / 非刚体 / 动态网格

| 名称 | 更偏什么 | 用途 | 链接 |
|---|---|---|---|
| FAUST | 静态人体对应 | non-rigid correspondence、匹配、benchmark | [官网](https://faust-leaderboard.is.tuebingen.mpg.de/) |
| DFAUST | 动态高分辨率 4D 人体 | 时序几何、非刚体变形、动态配准 | [官网](https://dfaust.is.tue.mpg.de/) |
| AMASS | 统一的人体动作数据库 | 动画、动捕、驱动网格、人体学习 | [官网](https://amass.is.tue.mpg.de/) |
| SMPL | 参数化人体模型 | 动作驱动、人体建模、动画与重建 | [官网](https://smpl.is.tue.mpg.de/) |

### 13.4 这个专题里，最值得反复翻的课程 / 书 / 教程

| 资源 | 为什么重要 | 链接 |
|---|---|---|
| Stanford CS348A | 建模 / 曲线曲面 / mesh processing 的系统课 | [课程页](https://graphics.stanford.edu/courses/) |
| DDG（Keenan Crane） | 几何处理数学基础最值得长期学的一门公开课 | [课程页](https://brickisland.net/ddg-web/) |
| MIT 2.158J Computational Geometry | CAD / CSG / 几何建模 / robustness 背景很强 | [课程页](https://ocw.mit.edu/courses/2-158j-computational-geometry-spring-2003/) |
| libigl Tutorial | 工程实践价值极高 | [教程页](https://libigl.github.io/tutorial/) |
| pbrt Book | 虽偏渲染，但这类“书 + 实现”型资源很值得模仿 | [官网](https://pbrt.org/) |

---

## 14. 按任务找资源：实战入口表

> 下面这部分尽量写得更“能直接拿来用”。

### 14.1 我想做三角网格清理、修复、查看问题
- 先看：**MeshLab**
- 再做：**Open3D / libigl / PMP**
- 如果问题特别偏拓扑或布尔：再看 **CGAL / Manifold**
- 常见任务关键词：
  - non-manifold
  - self-intersection
  - duplicate vertices / faces
  - hole filling
  - remeshing
  - decimation

### 14.2 我想做 mesh 布尔 / solid geometry / arrangement
- 先看：**CGAL**
- 想要“工程上先跑起来”：**Manifold**
- 如果你要接 CAD / STEP / B-rep：**OCCT**
- 如果你想转成隐式体再做：**OpenVDB / libfive**
- 这类问题建议长期跟：
  - SIGGRAPH / SIGGRAPH Asia
  - SGP
  - CAD / CAGD / Computers & Graphics

### 14.3 我想做 surface mesh 到 tetrahedral mesh
- 先看：**TetGen**
- 输入很脏、想更鲁棒：**TetWild / fTetWild**
- 想配合 CAD 与工程网格流程：**Gmsh + OCCT**
- 如果你后面做仿真：
  - 再补 **Stanford CS348C**
  - 再看 FEM / cloth / deformable simulation 资料

### 14.4 我想做 implicit modeling / SDF / level set
- 先看：**libfive**
- 稀疏体数据 / level set 管线：**OpenVDB**
- 如果你关心实时体数据 / GPU：再看 **NanoVDB** 与相关渲染资源
- 想把“建模 + 表达 + 可视化”结合起来：
  - Blender Geometry Nodes
  - OpenVDB
  - libfive
  - Inigo Quilez 的 SDF 讲解类资源

### 14.5 我想做 geometry processing 算法原型
- 先看：**libigl**
- 想更现代、概念更清楚：**geometry-central**
- 想补数学：**DDG**
- 想找 benchmark：
  - ShapeNet
  - ABC
  - FAUST / DFAUST
  - SGP 论文与数据集奖

### 14.6 我想做点云 / RGB-D / 扫描重建
- 先看：**Open3D**
- 数据集先下：
  - ScanNet
  - Matterport3D
  - HM3D
- 做清理与查看：**MeshLab**
- 做下游 mesh 处理：**libigl / PMP / geometry-central**

---

## 15. 建议你单独拆出来长期维护的专题文件

> 现在这份总表已经很大了。  
> 真正实用的做法，是把它拆成若干份“主题手册”。

### 15.1 我建议优先拆的 4 份

1. **`graphics_geometry_mesh_implicit.md`**  
   - 专门放：mesh、几何处理、隐式建模、robust geometry、CSG、体网格、CAD kernel

2. **`graphics_rendering_shader_realtime.md`**  
   - 专门放：渲染器、shader、OpenGL / Vulkan / path tracing / real-time rendering

3. **`graphics_datasets_assets_benchmarks.md`**  
   - 专门放：ShapeNet、ABC、Objaverse、ScanNet、人体数据、材质贴图、HDRI

4. **`graphics_venues_journals_blogs.md`**  
   - 专门放：会议、期刊、杂志、博客、YouTube、播客、论文追踪入口

### 15.2 如果你只保留一份最常查的“个人工作手册”
那我建议它至少保留下面这几个小节：

- **几何库总览**
- **按任务找库**
- **常用数据集**
- **会议 / 期刊入口**
- **博客 / 视频入口**
- **你自己的补充笔记**

### 15.3 我建议你下一步继续补的内容
- **几何处理经典论文清单**
- **mesh Boolean / arrangement / solid geometry 论文清单**
- **implicit / SDF / level set / neural implicit 清单**
- **仿真 / FEM / cloth / fluid 清单**
- **你常用 C++ 几何工具链对比表**
