# 五十铃 D-Max Hi-Lander 2WD 与丰田 Hilux Revo Prerunner 2WD —— 底盘工程与大梁结构强度深度对比分析

---

## 执行摘要（Executive Summary）

基于可核实的原厂（OEM）工程手册——具体包括**五十铃 D-Max 改装厂指南（Body Builders Guide，文档编号 `IMITPPD-BBG-GE-20001`）**、**2020–2025 款五十铃 D-Max 车身维修手册（Body Repair Manual）**、**丰田第 8 代 Hilux 车身维修手册（`BM3250E`）**以及**丰田 Hilux 新车技术特性手册（New Car Features Manual，`NM3250E`）**——**两款车型均不存在无条件的、全方位的底盘绝对压倒性优势**。相反，原厂工程文件揭示了由同一家泰国一级（Tier-1）车架冲压供应链体系（**Thai Summit PK Corporation / 日本 Press Kogyo 株式会社合资**）制造、但在结构工程取向上截然不同的两种日系非承载式车架设计哲学：

1. **丰田 Hilux Revo Prerunner 2WD（`GUN135`，AN120/AN130）具备更强文献证据优势的领域 —— 纵梁主材钢材等级与极限超载抗屈服裕度：**
   - **OEM 官方确认的 590 MPa 纵梁主材：** 丰田官方车身维修手册（`BM3250E`，章节 `RM100000000TR7F`，图号 `K123547C01.png`）明确证实：双排座（Double Cab）Pre-Runner 高底盘两驱与四驱车架的**整个中段及后段主纵梁**（从前悬架减振器塔座下折处一直延伸至后保险杠末端，包括内侧 C 型槽钢与外侧 C 型槽钢）均采用 **590 MPa 级高强度钢**（对应 JIS G 3134 `SPFH590` 级别；最小抗拉强度 $R_m \ge 590\text{ MPa}$，典型屈服强度 $R_{eL} \approx 420\text{–}450\text{ MPa}$）冲压成形，并配合可单独切割更换的 **440 MPa 级**前纵梁吸能延伸段（`SIDE RAIL EXTENSION ASSEMBLY`）以及横梁与纵梁连接处的**全周满焊工艺（"All-Round Welding"）**（`NM3250E`，章节 `NM100000000NEGS`）。
   - 相比之下，五十铃官方改装厂指南（`IMITPPD-BBG-GE-20001`，第 3-5-1 节，第 23 页）明确规定：第 3 代 D-Max（RG）的纵梁与横梁材料牌号为 **`SAEJ1392050YLK`**（即 `SAE J1392 050YLK` 低合金高强度热轧钢 [HSLA]；最小屈服强度 $R_{eL} \ge 345\text{ MPa}$ [50 ksi]，最小抗拉强度 $R_m \ge 415\text{ MPa}$ [60 ksi]，相当于日标 JIS G 3113 `SAPH440` 级别）。
   - **工程学推论：** 在相同的闭合箱型截面壁厚与抗弯截面模量（$Z_x$）条件下，Hilux Revo 的 **590 MPa 级**主纵梁具备高出约 **22% 至 30% 的材料屈服应力阈值**，在极端静态超载或恶劣路面剧烈垂向冲击下，对永久塑性弯曲变形（大梁折弯/塌腰）具有更高的安全裕度。

2. **2026 款五十铃 D-Max Hi-Lander 2WD（`TFR41` / `TFR40`，RG）具备更强文献证据优势的领域 —— 横梁拓扑架构、车身悬置支座冶金等级与高速稳定几何：**
   - **OEM 官方确认的 590 MPa 剪切式车身悬置支座与 8 横梁架构：** 尽管五十铃在主纵梁上选用了碳当量更低、电弧焊热影响区（HAZ）韧性与抗疲劳延展性更优异的 `SAEJ1392050YLK`（345 MPa 屈服 / ~440 MPa 抗拉级别），但五十铃将第 3 代 RG D-Max 的**驾驶室/货厢悬置支座（Body Mount Brackets）升级为 `JSH590Y`（590 MPa 抗拉强度级热轧高强钢）**（`IMITPPD-BBG-GE-20001`，第 23 页；而 Hilux Revo 的驾驶室悬置支座为 **440 MPa** 级），引入了**剪切式驾驶室悬置衬套（Shear-type Body Mounts）**，将单根闭合箱型纵梁宽度扩展至 **84 mm**（`IMITPPD-BBG-GE-20001`，第 9 页）、后段车架外宽扩展至 **1,080 mm**，并在全系布置了 **8 根横梁**（Hilux Revo 为 7 个主横梁工位），使车架整体抗扭刚度较第 2 代 RT D-Max 提升 **+20% 至 +23%**，纵向抗弯刚度提升 **+26%**。
   - 此外，2026 款 D-Max Hi-Lander 2WD 拥有**长出 40 mm 的轴距**（3,125 mm vs. 3,085 mm）、**更宽的前后轮距**（1,570/1,570 mm vs. 1,540/1,550 mm）、**更高的最小离地间隙**（235–240 mm vs. 217 mm）、**高位前双叉臂上控制臂支座（High-mounted Upper Control Arm Towers）**，以及经过**温态应力喷丸强化（WSSP）**的 3 片式后钢板弹簧。

3. **现有公开证据的核心局限性：**
   - **未公开的板材壁厚（$t$）与完整纵向截面高度分布函数（$h(x)$）：** 五十铃与丰田均未在任何公开宣传册、改装厂指南或车身维修手册中公布大梁前、中、后各分段内外层冲压槽钢的精确毫米级壁厚（$t$）。由于弹性抗弯刚度（$EI_x$）与弹性抗扭刚度（$GJ$）**完全取决于钢材杨氏模量（$E \approx 206\text{ GPa}$，所有牌号碳钢与高强钢均完全相同）以及截面几何尺寸（$b, h, t$）**——而**与钢材的 MPa 强度等级完全无关**——仅凭公开 OEM 文件无法从数学上绝对证明哪一款裸车架具有更高的绝对弹性抗弯刚度（$\text{N}\cdot\text{m}^2$）或抗扭刚度（$\text{N}\cdot\text{m}/\text{deg}$）。
   - **澄清网络流言：** 网络上广泛流传的“D-Max 大梁厚 4.8 mm（`3/16 英寸`）、Hilux 仅厚 3.6 mm（`9/64 英寸`）”的说法，溯源后证实源自 2016 年以前澳洲论坛（`ozisuzu.com.au` / `4x4earth.com`）针对老款车型的无根据英制分数换算传言；而泰文社交媒体上出现的“4.5 mm、5.0 mm、6.0 mm”大梁厚度说法，则是将原厂单层板厚（约 2.3–3.2 mm，或在双层 C 型槽钢搭接焊接翼缘处测得的 4.6–6.4 mm 双层叠加厚度）与泰国后市场超载改装车的**大梁外贴补强钢板（`เหล็กดามแชสซี`）**、越野护板厚度以及**泰国超级皮卡锦标赛（Thailand Super Pickup）后桥大梁C型切口必须补强 5 mm 钢板**的赛事规则混为一谈。
   - **切勿混淆驾驶室白车身与大梁的 980 MPa / 1,500 MPa 钢材：** 五十铃宣传的 **980 MPa** 及 **1,500 MPa** 超高强度钢**仅用于乘员舱白车身（BIW）立柱与门槛结构**，绝未用于底盘梯形大梁。

---

## 车型界定与规格核实（Vehicle Identification）

### 研究范围界定与年款更迭说明
- **车型 A（2026 款泰国市场五十铃 D-Max Hi-Lander Double Cab 四门高底盘 2WD）：** 直接核实自五十铃泰国总代理 Tri Petch Isuzu Sales Co., Ltd. 官方发布的 **2026 款 4-Door 产品手册（印刷编码 `PR0226`，2026 年 2 月版；2025 年 10 月正式上市）**及 **2026 款五十铃 D-Max 用户手册**。在 2026 款（MY2026）中，五十铃泰国已**在泰国本土全系车型中彻底停产了 1.9 Ddi（`RZ4E-TC`）发动机**；所有 2026 款 Hi-Lander 四门 2WD 车型均搭载全新的 **2.2 Ddi MaxForce（`RZ4F-TC`）** 发动机（匹配 `MVL6K` 6 速手动或 `L-B500` 8 速自动变速箱）或 **3.0 Ddi MaxForce（`4JJ3-TCX E5`）** 发动机（匹配 `AWR6B45` 6 速自动变速箱）。
  - *文献引用：* Tri Petch Isuzu Sales Co., Ltd.，《Isuzu D-Max 4-Door Brochure (MY2026, Print Code PR0226)》，2026 年 2 月，第 6 页（"SPECIFICATION รายละเอียดทางเทคนิค"），`https://assets.isuzu-tis.com/4_door_brochure_2026_be4df560bb.pdf`；《Isuzu D-Max Owner's Manual 2026》，第 8 章（"ข้อมูลและข้อกำหนดที่สำคัญ"），第 8-1 至 8-13 页（PDF 第 593–605 页），`https://assets.isuzu-tis.com/d_max_owner_manual_2026_58baae5400.pdf`。**置信度：** 高（High）。**证据分级：** 1（OEM 官方文件确认）。
- **车型 B（最新可核实的泰国市场丰田 Hilux Revo Prerunner Double Cab 四门高底盘 2WD —— MY2024/2025 最终欧 5 规格）：**
  - **年款限制明确声明：** 泰国市场不存在“2026 款”Hilux Revo Prerunner Double Cab 2WD。**2025 年 11 月 10–11 日**，丰田泰国（Toyota Motor Thailand）正式全球首发了第 9 代 **Toyota Hilux Travo**（包含 `Prerunner`、`4TREX`、`Overland` 及纯电 `Travo-e`），全面停产并替代了所有高底盘 **Hilux Revo Prerunner、4x4 及 Rocco** 车型，仅在单排商用货车（`Standard Cab`）和低底盘两驱车型（`Z-Edition`）上保留了 `Hilux Revo` 命名。严格遵循任务书第 2 节要求（*“不得用 4WD 车型、低底盘 2WD 车型、单排商用版或新款 Toyota Hilux Travo 替代 Revo。若无法核实 2026 款 Revo Prerunner 规格，须明确说明泰国市场最新可核实的年款并解释该限制”*），本报告采用 **Hilux Revo Prerunner Double Cab 2WD 在泰国市场的最终核实规格：MY2024 欧 5 版（2024 年 3 月 20 日上市，销售至 2025 年 11 月停产切换）**。在 2020–2025 改款周期内，泰国市场所有双排座（Double Cab）Prerunner 2WD（`2x4`）配置（`Entry`、`Mid`、`High` 及 `Rocco`）均**唯一搭载 2.4L `2GD-FTV (High)` 欧 5 柴油发动机**（2.8L `1GD-FTV` 204 PS / 500 Nm 发动机在双排高底盘车型上仅限 4x4 四驱版搭载）。
  - *文献引用：* Toyota Motor Thailand Co., Ltd.，*"TOYOTA launches the new HILUX REVO 2024"*（2024 年 3 月 20 日），`https://www.toyota.co.th/en/news/Toyota-Motorshow2024`；*"World Premiere of the New 'TOYOTA HILUX TRAVO'"*（2025 年 11 月 10 日），`https://www.toyota.co.th/en/news/HILUX-TRAVO-AND-HILUX-TRAVO-e`；官方《Hilux Revo Prerunner & 4x4 MY2024 Euro 5 Brochure》，2024 年 3 月，第 9–10 页，`https://toyotasummit.co.th/assets/images/newcar/brochure/18b4655c-68e8-4118-ba55-665f75d13c39/hiluxrevo-prerunner-4x4-2024-65ff9db103811942741600.pdf`。**置信度：** 高（High）。**证据分级：** 1（OEM 官方文件确认）。

### 泰国市场两款车型核心技术规格并列对比表

| 参数项目 | **车型 A：2026 款五十铃 D-Max Hi-Lander 4-Door (Cab 4) 2WD** | **车型 B：MY2024/2025 丰田 Hilux Revo Prerunner Double Cab 2WD（最终欧 5 规格）** |
| :--- | :--- | :--- |
| **代际与底盘代号** | 第 3 代（RG01 改款）：**`TFR41`**（2.2L）/ **`TFR40`**（3.0L）<br>*(MY24–25 的 1.9L 代号为 `TFR87`，已于 2025 年 10 月停产)* | 第 8 代（AN120/AN130 改款）：**`GUN135`**<br>*(已于 2025 年 11 月 10 日被 Hilux Travo 替代)* |
| **车身与驱动形式** | 四门双排座（`Cab 4`），前置后驱 2WD（`4x2`），原厂高底盘（`Hi-Lander`） | 四门双排座（`Double Cab`），前置后驱 2WD（`2x4`），原厂高底盘（`Prerunner`） |
| **泰国官方配置等级与售价（泰铢 THB）** | • `2.2 Ddi L 6MT`: 885,000 THB<br>• `2.2 Ddi L 8AT`: 924,000 THB<br>• `2.2 Ddi Z 6MT`: 952,000 THB<br>• `2.2 Ddi Z 8AT`: 991,000 THB<br>• `X-Series 2.2 Ddi 6MT / 8AT`: 1,002,000 / 1,041,000 THB<br>• `2.2 Ddi M 8AT`: 1,157,000 THB<br>• `3.0 Ddi M 6AT`: 1,184,000 THB | • `2.4 Entry 6MT`: 881,000 THB<br>• `2.4 Entry 6AT`: 931,000 THB<br>• `2.4 Mid 6MT`: 931,000 THB<br>• `2.4 Mid 6AT`: 981,000 THB<br>• `2.4 High 6MT`: 1,022,000 THB<br>• `2.4 High 6AT`: 1,072,000 THB<br>• `Rocco Prerunner 2.4 6AT`: 1,136,000 THB |
| **发动机型号与动力参数** | **1) 主力标配：** `RZ4F-TC`（2.2 Ddi MaxForce），2,164 cc（83.0 × 100.0 mm），压缩比 15.9:1，E-VGS 电控可变截面涡轮，欧 5（DPF，无需尿素）：**120 kW (163 PS) @ 3,600 rpm**，**400 Nm @ 1,600–2,400 rpm**<br>**2) 旗舰（`M`）：** `4JJ3-TCX E5`（3.0 Ddi MaxForce），2,999 cc（95.4 × 104.9 mm），压缩比 16.3:1，VGS 涡轮，欧 5（DPF）：**140 kW (190 PS) @ 3,600 rpm**，**450 Nm @ 1,600–2,600 rpm** | **双排 Prerunner 2x4 全系标配：** `2GD-FTV (High)`，2,393 cc（92.0 × 90.0 mm），压缩比 15.6:1，VN 可变喷嘴涡轮增压中冷，i-ART 喷射，欧 5（DPF，无需尿素）：**110 kW (150 PS) @ 3,400 rpm**，**400 Nm @ 1,600–2,000 rpm** *(6MT 与 6AT 均为 400 Nm)*<br>*(注：2.8L `1GD-FTV` 204 PS / 500 Nm 在双排高底盘车型上仅限 4x4 四驱搭载)* |
| **变速箱与齿比/主减速比** | • **6MT（`MVL6K`，2.2L）：** 4.508 / 2.449 / 1.474 / 1.000 / 0.726 / 0.578 / R 4.193（主减速比：**4.100**）<br>• **8AT（`L-B500`，2.2L）：** 4.903 / 3.120 / 2.166 / 1.597 / 1.312 / 1.000 / 0.776 / 0.651 / R 4.050（主减速比：**3.583**）<br>• **6AT（`AWR6B45`，3.0L）：** 3.600 / 2.090 / 1.488 / 1.000 / 0.687 / 0.580 / R 3.732（主减速比：**3.727**） | • **6MT（`High` 配 iMT）：** 4.784 / 2.423 / 1.443 / 1.000 / 0.777 / 0.643 / R 4.066（主减速比：**3.583**）<br>• **6AT（`AC60E` 带顺序换挡）：** 3.600 / 2.090 / 1.488 / 1.000 / 0.687 / 0.580 / R 3.732（主减速比：**4.100**） |
| **整车外廓长 × 宽 × 高** | • `L` 等级：**5,280 × 1,870 × 1,785 mm**<br>• `Z`、`M`、`X-Series` 等级：**5,280 × 1,870 × 1,790 mm** | • MY2024 欧 5 全系（`Entry`、`Mid`、`High`、`Rocco`）：**5,325 × 1,900 × 1,815 mm** *(2020–2023 非 Rocco 款车宽为 1,855 mm)* |
| **轴距（Wheelbase）** | **3,125 mm** | **3,085 mm** |
| **前后轮距（Track F/R）** | **1,570 mm / 1,570 mm** | **1,540 mm / 1,550 mm** |
| **最小离地间隙** | • `L` 等级（255/65R17 轮胎）：**235 mm**<br>• `Z`、`M`、`X-Series`（265/60R18 轮胎）：**240 mm** | **217 mm**（双排 Prerunner 全系） |
| **货厢内部长 × 宽 × 高** | **1,495 × 1,530 × 490 mm** | **1,555 × 1,540 × 480 mm** |
| **整备质量（Kerb Weight）** | • `2.2 L 6MT`: **1,835 kg** \| `2.2 L 8AT`: **1,870 kg**<br>• `2.2 Z 6MT`: **1,855 kg** \| `2.2 Z 8AT`: **1,885 kg**<br>• `2.2 M 8AT`: **1,895 kg** \| `3.0 M 6AT`: **1,950 kg**<br>*(由 `isuzu-tis.com/compare` 官方数据库核实)* | **泰国消费者宣传册未公开印制**<br>*(东盟/出口认证 `GUN135` 双排 Prerunner 整备质量为 **~1,940–2,030 kg**)* |
| **最大总质量（GVW）与额定载质量** | **泰国消费者宣传册未公开印制。** 五十铃泰国（IMIT）针对泰产双排 Hi-Lander 4x2 的东盟乘用税率认证标称 **GVW 为 2,650 kg**（名义载重约 700–815 kg；出口版 4x2 高底盘结构认证 GVM 达 **3,000–3,100 kg**）。 | **泰国消费者宣传册未公开印制。** 东盟/出口版 `GUN135` 双排 Pre-Runner 认证 **GVW 为 2,810–2,910 kg**（名义载重约 850–950 kg；澳洲版 Hi-Rider `GUN125/135` 认证 GVM 为 **3,000 kg**）。 |
| **转向系统与最小转弯半径** | 齿轮齿条式：**液压助力转向**（`L`、`Z`、`X-Series`）/ **EPS 电动助力转向**（`2.2 M` 与 `3.0 M`）；最小转弯半径：**6.1 m** | 齿轮齿条式：全系标配**带 VFC（可变流量控制）的液压助力转向**；最小转弯半径：**6.4 m** |

---

## 车架材质与厚度对比（Chassis Material Comparison）

### 核心区分：乘员舱白车身（BIW）钢材 vs. 非承载式梯形大梁钢材
两家制造商均在宣传材料中强调高强度钢的应用，但原厂维修手册与救援指南（Rescue Sheet）清晰地划定了**电阻点焊乘员舱白车身（BIW）**与**电弧焊梯形大梁（Ladder Frame）**之间的严格冶金界限：
1. **五十铃 D-Max（RG，2020–2026）：**
   - **技术论断：** 宣传中提到的 **980 MPa** 与 **1,500 MPa** 超高强度钢（以及 >390 MPa 钢材占比从 30% 提升至 46%）**100% 仅用于乘员舱白车身（BIW）外壳**；而梯形大梁的纵梁与横梁采用的是 **`SAEJ1392050YLK`**（最小屈服强度 $\ge 345\text{ MPa}$ / 抗拉强度 $\ge 415\text{–}440\text{ MPa}$），车身悬置支座采用的是 **`JSH590Y`**（590 MPa 抗拉强度级热轧高强钢）。
   - **来源与发布日期：** (1) 五十铃汽车有限公司（日本）全球新闻公报，2019 年 10 月 11 日；(2) 五十铃国际运营（泰国）有限公司（IMIT），《ISUZU D-MAX For General Export BODY BUILDERS GUIDE》，2020 年 4 月版（文档编号 `IMITPPD-BBG-GE-20001`）；(3) 五十铃汽车有限公司，《Isuzu D-Max (2020-) Rescue Sheet》（文档编号 `MPA-TF-RSE-2001AU-01`，Version 01，2020 年）。
   - **直接 URL 链接：** `https://www.isuzu.co.jp/world/newsroom/details/20191011_01.html`；`https://www.scribd.com/document/563840714/BBG-D-MAX-single-cab`（互联网档案馆快照：`http://web.archive.org/web/20251230051818/https://www.scribd.com/document/563840714/BBG-D-MAX-single-cab`）；`https://www.isuzu.co.jp/world/ci/rescue/pdf/australia_en_2020.pdf`。
   - **精确页码 / 章节 / 原文引述：**
     - `IMITPPD-BBG-GE-20001`，第 3-5-1 节（"Chassis Frame Material"），第 23 页：*"Isuzu D-MAX features a box section frame chassis with cross members for added strength and durability. Material specification of the chassis is **SAEJ1392050YLK** and the body mounts are **JSH590Y**."*（五十铃 D-Max 采用带横梁的箱型截面车架以提升强度和耐久性。车架大梁材料规范为 **SAEJ1392050YLK**，车身悬置支座材料规范为 **JSH590Y**。）
     - 五十铃新闻公报（`20191011_01.html`），"Vehicle body" 章节：*"In addition to developing a lean, rational assembly structure for the new D-MAX, the use of 980 MPa high-tensile steel plates and other things have made it possible to achieve stronger body rigidity while keeping it lightweight. The application of higher than 390 MPa high-tensile steel plates has increased from 30% to 46%."*
     - 五十铃救援指南（`MPA-TF-RSE-2001AU-01`），第 3 页，第 4 节（"Detail of high strength steel zones used in the vehicle"）：将 **590 MPa、780 MPa、980 MPa 及 1,500 MPa**（热成型硼钢）全部标注于驾驶室 A/B 柱、门槛梁与车顶加强筋，未标注于车架大梁。
   - **置信度：** 高（High）。**证据分级：** 1（OEM 官方文件确认）。

2. **丰田 Hilux Revo Prerunner（`GUN135`，AN120/AN130，2015–2025）：**
   - **技术论断：** Hilux Revo 的 **FIRM（*Frame with Integrated Rigidity Mechanism*）** 梯形大梁在**整个中段与后段主纵梁**（内外两侧 C 型槽钢）上全部采用 **590 MPa 级高强度钢**（`SPFH590` 级别），并在前纵梁吸能延伸段、前螺旋弹簧/减振器塔座及外侧纵梁补强板（Pre-Runner 与 4WD 专属）、第 1 横梁（前副横梁）、第 3 横梁（变速箱横梁）、后横梁、1–3 号驾驶室悬置支座及后钢板弹簧吊耳支座上采用 **440 MPa 级高强度钢**（`SAPH440` / `SPFH440` 级别）。与此同时，其 GOA 驾驶室白车身则采用 **590 MPa**、**440 MPa** 与 **340 MPa** 级钢材。
   - **来源与发布日期：** 丰田汽车公司，《Toyota Hilux Body Repair Manual (`BM3250E`)》，章节 `RM100000000TR7F` / `RM100000000M5US`（*General > INTRODUCTION > ABOUT THIS VEHICLE > STRUCTURAL OUTLINE*），2015–2023；《Toyota Hilux New Car Features Manual (`NM3250E`)》，章节 `NM100000000NEGR` & `NM100000000NEGO`，2015；日本新日铁技术报告第 88 期（Nippon Steel Technical Report No. 88，*"Development of High Strength Steels for Automobiles"*，2003 年 7 月）。
   - **直接 URL 链接：** `https://gitlab.com/ToyotaManuals/n00148/-/raw/main/N00148/manual/brm/contents/RM100000000TR7F.html`；`https://gitlab.com/ToyotaManuals/n00148/-/raw/main/N00148/manual/ncf/contents/NM100000000NEGR.html`；`https://cargeometry.org/toyota/2532-toyota-hilux-gun125-2017-2023-rh-japanese-market-body-dimensions.html`；`https://www.nipponsteel.com/en/tech/report/nsc/pdf/n8802.pdf`。
   - **精确页码 / 章节 / 原文引述：**
     - `BM3250E`，章节 `RM100000000TR7F`，工程图 `K123547C01.png`（`*A: for 4WD and Pre-Runner` 双排座车架）：将从前悬架塔座后方直至后保险杠末端的整条主纵梁（含内外层槽钢）标注为图例 `K108836.png`（点状阴影 = **`590 MPa High Strength Steel`**），并将前吸能延伸段、前端盖板、前弹簧塔座及外侧纵梁补强板、第 1 横梁、第 3 横梁、后横梁、1–3 号驾驶室悬置支座及后板簧吊耳支座标注为图例 `K108850.png`（深灰实心填充 = **`440 MPa High Strength Steel`**）。
     - `BM3250E`，章节 `RM100000000NO8Z`（"PRECAUTIONS FOR REPAIRING BODY STRUCTURE"）：*"PROHIBITION OF HEAT REPAIR FOR BODY FRAME PARTS: a. Rustproof high strength steel sheets are used for the body frame. Therefore, if these parts are heat repaired using an acetylene torch or equivalent, the crystalline structure changes, causing the strength of the steel sheets to decrease."*（禁止对车架大梁部件进行加热校正修复：车架采用防锈高强度钢板制造，若使用乙炔炬等加热修复，其晶体组织会发生改变，导致钢板强度显著下降。）
   - **置信度：** 高（High）。**证据分级：** 1（OEM 官方文件确认）。

### 车架材质、力学性能与截面几何并列对比表

| 车架特征 / 参数 | **2026 款五十铃 D-Max Hi-Lander Double Cab 2WD (`TFR41` / `TFR40`)** | **MY2024/2025 丰田 Hilux Revo Prerunner Double Cab 2WD (`GUN135`)** | **支持文献来源与证据分级** |
| :--- | :--- | :--- | :--- |
| **车架平台架构名称** | **Isuzu Dynamic Drive Platform**（全闭合箱型梯形大梁） | **FIRM**（*Frame with Integrated Rigidity Mechanism*，全闭合箱型梯形大梁） | OEM 宣传册与新闻资料包（**第 1 级**，高置信度） |
| **主纵梁（中段与后段）—— 材料牌号** | **`SAEJ1392050YLK`**（`SAE J1392 050YLK` 低碳铝镇静硫化物形态控制热轧低合金高强钢 HSLA；对应日标 JIS G 3113 `SAPH440` / JFS `JSH440`） | **`590 MPa High Strength Steel`**（丰田 `BM3250E` 官方分级；对应日标 JIS G 3134 **`SPFH590`** 汽车结构用改善成形性热轧高强度钢板） | 五十铃：`IMITPPD-BBG-GE-20001` 第 23 页<br>丰田：`BM3250E` `RM100000000TR7F` (`K123547C01.png`) 及新日铁报告 No. 88 第 5 页（**第 1 级**，高置信度） |
| **主纵梁 —— 最小屈服强度（$R_{eL}$ / $\sigma_y$）** | **$\ge$ 345 MPa (50 ksi)** *(由 SAE J1392 050YLK 中的 `050` 代码直接规定)* | **`BM3250E` 未单独公开屈服强度数值** *(根据 JIS G 3134 `SPFH590` / JFS `JSH590R/Y` 标准推导：标准要求 **355–455 MPa**，典型出厂值 **~420–450 MPa**)* | 五十铃：**第 1 级**（高置信度）<br>丰田屈服强度：**第 3 级**（基于 JIS G 3134 标准推导，中高置信度） |
| **主纵梁 —— 极限抗拉强度（$R_m$ / $\sigma_u$）** | **$\ge$ 415 MPa (60 ksi)** *(SAE J1392 下限，日系钢厂实际供货通常为 **440 MPa** 级)* | **$\ge$ 590 MPa** *(由丰田 `BM3250E` `RM100000000TR7F` 明确标注)* | 五十铃与丰田 OEM 官方手册（**第 1 级**，高置信度） |
| **前部碰撞吸能区 / 延伸纵梁 —— 材质与强度** | **`SAEJ1392050YLK`**（$\ge 345\text{ MPa}$ 屈服 / $\ge 415\text{–}440\text{ MPa}$ 抗拉），冲压有轴向溃缩诱导筋 | **`440 MPa High Strength Steel`**（`SIDE RAIL EXTENSION ASSEMBLY` 与前端盖板，按 `RM100000000MUPM` 允许在弹簧塔座前方切割更换） | 五十铃：`IMITPPD-BBG-GE-20001` 第 23 页<br>丰田：`BM3250E` `RM100000000TR7F` & `RM100000000MUPM`（**第 1 级**，高置信度） |
| **各横梁材质等级** | 全系横梁采用 **`SAEJ1392050YLK`**（$\ge 345\text{ MPa}$ 屈服 / $\ge 415\text{–}440\text{ MPa}$ 抗拉） | • **第 1（前副横梁）、第 3（变速箱横梁）及后横梁：** **`440 MPa High Strength Steel`**<br>• **第 2（前悬架下摆臂横梁）：** 标准结构钢（~270–370 MPa），在 Pre-Runner/4WD 上配有 **`440 MPa` 外侧加强角板**<br>• **货厢下方中间横梁：** 标准热轧钢（~270–370 MPa） | 五十铃：`IMITPPD-BBG-GE-20001` 第 23 页<br>丰田：`BM3250E` `RM100000000TR7F` (`K123547C01.png`)（**第 1 级**，高置信度） |
| **驾驶室 / 货厢悬置支座 —— 材质与抗拉强度** | **`JSH590Y`**（抗拉强度 **$\ge$ 590 MPa**，屈服强度 315–455 MPa，符合 JFS A 1001；相比第 2 代 RT D-Max 的 400 MPa `JSH 400J-P` 大幅升级） | • **1、2、3 号驾驶室悬置支座：** **`440 MPa High Strength Steel`**<br>• **双排货厢支座：** 标准热轧钢 *(单排货车使用高耸的 `440 MPa` 重载货厢支座)* | 五十铃：`IMITPPD-BBG-GE-20001` 第 23 页及 I-CAR NZ *PanelTalk* 2012 年 5/6 月刊第 46 页<br>丰田：`BM3250E` `RM100000000TR7F`（**第 1 级**，高置信度） |
| **悬架与板簧安装支座 —— 材质与局部补强** | 高位前双叉臂上控制臂塔座；带内外加强筋的后板簧吊耳 *(`IMITPPD-BBG-GE-20001` 中辅助车架支座规定采用 $t = 4.5\text{ mm}$ 钢板)* | • **前螺旋弹簧/减振器塔座及纵梁外侧补强板（Pre-Runner 与 4WD 专属）：** **`440 MPa High Strength Steel`** *(低底盘 2WD 取消了这块 440 MPa 外侧补强板！)*<br>• **后板簧吊耳支座：** **`440 MPa High Strength Steel`** | 五十铃：`IMITPPD-BBG-GE-20001` 及全球公报 `20191011_01.html`<br>丰田：`BM3250E` `RM100000000TR7F` (`K123547C01.png` 对比 `K123544C01.png`)（**第 1 级**，高置信度） |
| **纵梁闭合箱型截面成型工艺** | 全闭合矩形箱型截面：外侧 C/帽型冲压槽钢 + 内侧 C 型冲压槽钢，通过机器人连续 MAG 电弧焊缝拼接（遵循企业标准 `ISC-C52-001`） | 全闭合矩形箱型截面：外侧 C 型冲压槽钢套入内侧 C 型冲压槽钢，上下水平翼缘双层搭接并连续满焊（`NM3250E` `V113717C01.png`） | 五十铃：`IMITPPD-BBG-GE-20001` 第 23 页<br>丰田：`NM3250E` `NM100000000NEGS` (`V113717C01.png`)（**第 1 级**，高置信度） |
| **纵梁截面尺寸（宽 $b$ × 高 $h$）** | • **单根纵梁宽度（$b$）：** **84 mm**（`IMITPPD-BBG-GE-20001` 第 9 页官方确认）<br>• **车架外宽（前段 / 后段）：** **857 mm / 1,080 mm**（第 9 页确认）<br>• **中段纵梁截面高度（$h$）：** **未公开验证** *(推导中段肚部高约 ~145–165 mm；RT 后桥处高度为 114.8 mm)* | • **最前端盖板处箱型截面周长：** **277 mm**（即 $h + b \approx 138.5\text{ mm}$，`BM3250E` `RM100000000M834`）<br>• **前延伸段拼接处内壁垂直高度：** **146 mm**（外层搭接焊缝长 **172 mm**，`RM100000000MUPM`）<br>• **中段纵梁高度（$h$）：** 相比 Vigo 增大 **+20 mm**（泰版宣传册 `B10303T-18090` 第 5 页；欧版资料包第 26 页称截面扩大达 +30 mm）；精确毫米表**未公开验证**（中段约 ~75–85 mm 宽 × ~160–180 mm 高） | 五十铃：`IMITPPD-BBG-GE-20001` 第 9 页（**第 1 级**）<br>丰田：`BM3250E` `RM100000000M834` & `RM100000000MUPM`、TMT 宣传册第 5 页（**第 1 级**；中段精确尺寸**未公开验证**） |
| **纵梁各分段标称板材壁厚（$t$，单位 mm）** | **OEM 手册未公开验证。**<br>*(基于工程与拆解推导：前吸能区约 ~1.8–2.0 mm；中段箱型壁厚约 ~2.3–2.8 mm；后桥上拱及板簧支座区约 ~3.0–3.2 mm；双层搭接边约 ~4.6–5.6 mm；重载支座为 4.5 mm)* | **OEM 手册未公开验证。**<br>*(丰田全球新闻室确认“增加了车架纵梁板材厚度”；拆解与卡尺推导：590 MPa 中后段单层壁厚约 ~2.3–3.2 mm，加强区约 ~3.2–3.6 mm，上下双层 C 型翼缘搭接处总厚约 ~6.0–6.4 mm)* | 官方数值壁厚表：**未公开验证（Not publicly verified）**。<br>丰田定性增厚说明：**第 1 级** (`global.toyota/en/newsroom/toyota/44397819.html`)。<br>分区壁厚推导：**第 3 级 / 第 4 级**（中等置信度）。 |
| **2WD 高底盘、4WD 四驱与 2WD 低底盘车架结构差异** | **2WD Hi-Lander（`TFR` 高底盘）**与 **4WD V-Cross（`TFS`）**共享高位前上摆臂支座、加宽 1,570 mm 轮距及桥上置后板簧支座（BRM 图纸 `dmax_11.jpg` 确认），仅省去前差速器与分动箱安装耳。**低底盘 2WD（`Cab 4`）**使用低位前摆臂支座与桥下置后板簧。 | **2WD Pre-Runner（`GUN135`）**与 **4WD（`GUN125/126`）**共享**完全相同的车架蓝图与高强钢分布图**（`BM3250E` `K123547C01.png`、`RM100000000M5V2` / `M5V3`），包含深下沉式前悬架横梁与 **440 MPa** 前弹簧塔座外侧补强板（仅省去前差速器支座）。**低底盘 2WD**（`K123544C01.png`、`RM100000000M5UX`）使用浅前横梁且无 440 MPa 外侧塔座补强板。 | 五十铃：2020MY D-Max BRM (`1686954101_isuzu-d-max-2020-2025_razmeri_kuzova_07.jpg`) 及全球公报 `20191011_01.html`<br>丰田：`BM3250E` `RM100000000TR7F` & `RM100000000M5V2`（**第 1 级**，高置信度） |

### 网络流传大梁厚度数据（3.2 mm、3.6 mm、4.0 mm、4.8 mm、5.0 mm、6.0 mm）的溯源与证伪
根据任务书第 4A 节要求，以下对网络上流传的各类厚度数值的原始出处、测量位置、适用年款及真实性进行逐一核查：
1. **“D-Max 大梁厚 4.8 mm vs. Hilux 厚 3.6 mm”流言溯源：**
   - **原始出处：** 直接溯源至澳大利亚论坛 `ozisuzu.com.au`（`topic,2139.0.html`，于 2016 年 7 月 27 日被完整引述于 `4x4earth.com` 帖子第 61 楼）：*"The Hilux has a chassis of folded 9/64th (3.6mm) steel plate, whilst the DMax chassis is 3/16th (4.8mm) steel plate... and a 1/2" further advantage."*
   - **核查结论：** 这是针对**老一代车型（2020 款之前的 RT D-Max 与第 7 代 KUN26 Hilux Vigo）**的无证据论坛传言，直接将粗略的英制分数（$3/16\text{ 英寸} = 4.76\text{ mm}$；$9/64\text{ 英寸} = 3.57\text{ mm}$）换算成了公制毫米。事实上，五十铃与丰田均从不使用英制分数设计车架，而是采用公制 JIS 热轧卷板规格。此外，许多外行用游标卡尺在闭合箱型纵梁外露的**双层搭接焊接折边（Flange Lip）**或带加强板的支架边缘测量，测得的是**两层钢板叠加厚度加上电泳漆膜与间隙**（例如 $2 \times 2.3\text{ mm} = 4.6\text{ mm}$），并将其误认为单层大梁壁厚。
   - **文献引用：** `4x4earth.com`，主题帖 *"Another Bent Chassis Discussion"*，第 4 页，第 61 楼（2016 年 7 月 27 日），`https://4x4earth.com/forum/index.php?threads/another-bent-chassis-discussion.40039/page-4`。**置信度：** 高（流言出处完全锁定）。**证据分级：** 4（未经证实的传言——作为 OEM 单层板厚已被证伪）。
2. **泰国网络上“4.0 mm、4.5 mm、5.0 mm、6.0 mm”数值的真实来源：**
   - **来源一 —— 泰国重载改装车后市场“大梁补强钢板（`เหล็กดามแชสซี`）”厚度：** 在泰国，大量将单排或一排半皮卡改装为全浮式后桥（`เพลาลอย`）以拉载 3–5 吨货物的车主，会在大梁鹅颈处与后桥拱形区外侧焊接激光切割的扁钢或槽钢补强板（`เหล็กดามแชสซี`）。泰国底盘强化商铺（如 Rakuda Thailand、Pantip 及 YouTube 改装厂）公开售卖的补强钢板标准厚度恰好为 **3.2 mm、4.0 mm、4.5 mm、5.0 mm 和 6.0 mm**。
   - **来源二 —— 泰国超级皮卡锦标赛（Thailand Super Pickup）技术规则的 5.0 mm 强制补强条款：** 《2025 泰国超级皮卡技术规则》第 **B.4.2.7** 条（第 5 页）明确规定：当为降低车身而在后桥上方对底盘大梁下翼缘进行 C 型切口（Notching，不超过 50%）时，*“必须在底盘大梁两侧使用厚度至少为 5 mm 的钢板进行补强”*（`จะต้องเสริมความแข็งแรงด้วยแผ่นเหล็ก ที่มีความหนาอย่างน้อย 5 มม. ทั้งสองข้างของ Chassis`）。
   - **来源三 —— 五十铃 N 系列（Elf）轻卡大梁与后市场越野护板/拖车杠厚度：** 五十铃 N 系列（`NLR/NMR`）4 轮轻卡采用单层开放式 C 型槽钢大梁，其单层壁厚为 4.5–5.0 mm；同时丰田官方选装铝合金底盘护板厚度为 **4.0 mm**，泰国后市场钢制护板与重型拖车杠（如 Giant 4x4 Towbar）广泛标称 **4.5 mm、5.0 mm、6.0 mm** 钢板。
   - **文献引用：** RAAT《2025 Technical Regulations TH Super Pickup》，2025 年 5 月，规则 B.4.2.7，第 5 页，`https://www.thailandsuperseries.net/wp-content/uploads/2025/05/2025-Technical-Regulations-TH-Super-Pickup.pdf`；Pantip 帖子 43886696，`https://pantip.com/topic/43886696`。**置信度：** 高。**证据分级：** 2 & 4（非原厂厚度数值的真实来源已确认）。

---

## 结构工程力学分析（Structural Engineering Analysis）

### 1. 闭合箱型截面几何、抗弯截面模量（$Z_x$）及弯曲刚度与扭转刚度对比

2026 款五十铃 D-Max Hi-Lander 与丰田 Hilux Revo Prerunner 均在整条纵梁全长范围内采用**全闭合矩形箱型截面（Closed Rectangular Box Section）**（不同于北美皮卡后段或老款日产 Navara D22 / 三菱 Triton 曾使用的开放式 C 型截面）。

```
     五十铃 D-Max (RG) 箱型纵梁截面            丰田 Hilux Revo (FIRM) 箱型纵梁截面
       （对接/折边焊缝闭合箱型截面）         （内外双 C 型槽钢上下翼缘搭接截面, V113717C01）
              b = 84 mm                                 b ≈ 75–85 mm
         +-----------------+                         +---------+-------+
         |        t        |                         |   t_w   |===t===| <-- 上下水平翼缘处
         |                 |                         |         |       |     双层钢板搭接满焊
       h | t             t | h                     h | t       |       | t   （有效翼缘增厚！）
         |                 |                         |         |===t===|
         +-----------------+                         +---------+-------+
```

#### 核心结构力学控制方程
设薄壁闭合矩形箱型截面的外宽为 $b$，外高为 $h$，两侧垂直腹板壁厚为 $t_w$，上下水平翼缘有效厚度为 $t_f$（对于单层翼缘 $t_f = t_w$；对于如图 `V113717C01.png` 所示内外 C 型槽钢水平翼缘重叠搭接的结构，$t_f = \alpha t_w$，其中 $1 < \alpha \le 2$）：

1. **绕水平弯曲主轴的截面惯性矩（$I_x$，单根纵梁）：**
   $$I_x = \frac{b h^3 - (b - 2 t_w)(h - 2 t_f)^3}{12}$$
2. **弹性抗弯截面模量（$Z_x$，单根纵梁）：**
   $$Z_x = \frac{I_x}{h / 2} = \frac{b h^3 - (b - 2 t_w)(h - 2 t_f)^3}{6 h}$$
3. **纵向弹性抗弯刚度（$K_{\text{bend}}$，左右双纵梁）：**
   $$K_{\text{bend}} \propto 2 E I_x$$
   其中钢材的杨氏模量 **$E \approx 206\text{ GPa}$（$206,000\text{ MPa}$）对于 `SAEJ1392050YLK`（345 MPa 屈服）与 `SPFH590`（590 MPa 抗拉）完全相同**。
   > [!IMPORTANT]
   > **基本固体力学原理：** 将车架钢材的抗拉强度从 440 MPa（`SAPH440` / `SAEJ1392050YLK`）提升至 590 MPa（`SPFH590`），**不会使车架的弹性抗弯刚度（$EI_x$）或弹性抗扭刚度（$GJ$）提高哪怕 1%**！因为所有碳素结构钢与低合金高强钢的弹性模量（$E \approx 206\text{ GPa}$）和剪切模量（$G \approx 79.3\text{ GPa}$）均为物理常数。载重下的弹性下挠量与交叉轴路况下的弹性扭转变形量**100% 取决于截面几何尺寸（$b, h, t$）、纵梁跨距及横梁布置**。更高 MPa 等级的高强钢提升的是**屈服极限弯矩容量（$M_y = \sigma_y Z_x$）**——即大梁发生永久塑性折弯（不可逆变形）的临界载荷——或者允许工程师在保持同等抗屈服强度的前提下减薄板厚 $t$ 以实现轻量化。
4. **圣维南纯扭转常数（Saint-Venant Torsional Constant $J$，单根闭合箱型纵梁）：**
   根据薄壁闭合截面 Bredt 第二公式，设中线围成面积 $A_m = (b - t_w)(h - t_f)$：
   $$J = \frac{4 A_m^2}{\oint \frac{ds}{t}} = \frac{2 (b - t_w)^2 (h - t_f)^2}{\frac{h - t_f}{t_w} + \frac{b - t_w}{t_f}}$$
   由于 $J$ 与**闭合包络面积的平方（$A_m^2 \approx b^2 h^2$）成正比**，闭合箱型纵梁的抗扭刚度是同尺寸开放式 C 型槽钢的 **50 至 100 倍**。

#### 明确假设条件下的参数化对比计算
由于五十铃公开了纵梁外宽（**$b = 84\text{ mm}$**，`IMITPPD-BBG-GE-20001` 第 9 页）与最小屈服强度（**$\sigma_y \ge 345\text{ MPa}$**），而丰田公开了前拼接处内壁垂直高度（**146 mm**，`BM3250E` `RM100000000MUPM`）、上下翼缘搭接箱型结构（`V113717C01.png`）及 **590 MPa** 抗拉强度等级（`SPFH590` 典型屈服强度 **$\sigma_y \approx 420\text{–}450\text{ MPa}$**），我们可以在**驾驶室下方中段主纵梁腹部截面**建立边界清晰的参数化对比模型（设定 D-Max 中段典型截面高度 $h = 160\text{ mm}$、宽度 $b = 84\text{ mm}$；Hilux Revo 中段典型截面宽度 $b = 80\text{ mm}$、高度 $h = 165\text{ mm}$，并在三种合理的单层板材壁厚 $t \in \{2.6\text{ mm}, 3.0\text{ mm}, 3.2\text{ mm}\}$ 下进行核算）：

| 参数化工况（驾驶室下方中段单根纵梁截面） | 外廓尺寸 ($b \times h$, mm) | 腹板/翼缘有效壁厚 ($t_w / t_f$, mm) | 截面惯性矩 $I_x$ ($\text{cm}^4$) | 抗弯截面模量 $Z_x$ ($\text{cm}^3$) | 材料最小屈服应力 $\sigma_y$ (MPa) | **单根纵梁标称屈服弯矩 $M_y = \sigma_y Z_x$ ($\text{kN}\cdot\text{m}$)** | **单根纵梁抗扭常数 $J$ ($\text{cm}^4$)** |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **工况 1A：D-Max Hi-Lander**（标准箱型，$t = 2.8\text{ mm}$） | $84 \times 160$ | $2.8 / 2.8$ | $414.5\text{ cm}^4$ | **$51.8\text{ cm}^3$** | $345\text{ MPa}$ (`050YLK`) | **$17.87\text{ kN}\cdot\text{m}$** | **$317.8\text{ cm}^4$** |
| **工况 1B：D-Max Hi-Lander**（加厚壁厚，$t = 3.2\text{ mm}$） | $84 \times 160$ | $3.2 / 3.2$ | $468.8\text{ cm}^4$ | **$58.6\text{ cm}^3$** | $345\text{ MPa}$ (`050YLK`) | **$20.22\text{ kN}\cdot\text{m}$** | **$360.2\text{ cm}^4$** |
| **工况 2A：Hilux Revo Prerunner**（590 MPa，减薄壁厚 $t = 2.6\text{ mm}$，$1.5\times$ 搭接翼缘 $t_f = 3.9\text{ mm}$） | $80 \times 165$ | $2.6 / 3.9$ | $471.2\text{ cm}^4$ | **$57.1\text{ cm}^3$** | $430\text{ MPa}$ (`SPFH590`) | **$24.56\text{ kN}\cdot\text{m}$** (较 1A 高 +37%) | **$318.4\text{ cm}^4$** |
| **工况 2B：Hilux Revo Prerunner**（590 MPa，同等壁厚 $t = 3.0\text{ mm}$，$1.5\times$ 搭接翼缘 $t_f = 4.5\text{ mm}$） | $80 \times 165$ | $3.0 / 4.5$ | $536.4\text{ cm}^4$ | **$65.0\text{ cm}^3$** | $430\text{ MPa}$ (`SPFH590`) | **$27.96\text{ kN}\cdot\text{m}$** (较 1B 高 +38%) | **$363.5\text{ cm}^4$** |

- *参数化模型的核心工程学结论（证据分级：第 3 级 —— 基于已核实的 OEM 材料与几何输入按材料力学推导）：*
  1. **极限超载抗屈服折弯能力（$M_y$）：** 由于丰田 `NM3250E`（`V113717C01.png`）的截面设计将内外两个 C 型槽钢的水平翼缘在纵梁顶部与底部重叠搭接（恰好将双层金属厚度集中在弯曲正应力 $\sigma = My/I_x$ 最大的上下极值纤维 $y = \pm h/2$ 处），**并且**采用了 **590 MPa（`SPFH590`）** 钢材，即使 Hilux Revo 的单层槽钢壁厚比 D-Max 薄 0.2–0.4 mm，其主纵梁的屈服弯矩（$M_y$）仍然显著高于 D-Max。反过来，如果 D-Max 的 `SAEJ1392050YLK`（$\sigma_y = 345\text{ MPa}$）纵梁想要在屈服弯矩上追平壁厚 $t_w = 2.8\text{ mm}$ 的 `SPFH590`（$\sigma_y = 430\text{ MPa}$）Hilux 搭接纵梁，D-Max 的单层板厚必须达到 **$t \approx 3.8\text{–}4.0\text{ mm}$**（这会导致裸车架质量突破 Press Kogyo 公布的 189–252 kg 范围，且与 D-Max 轻出约 80–100 kg 的整备质量相矛盾）。
  2. **抗扭刚度（$GJ$）与整车车架抗扭转表现：** 单根纵梁的扭转常数 $J$ 极为接近（~$318\text{–}363\text{ cm}^4$），因为五十铃更宽的 **84 mm** 截面宽度弥补了单层翼缘的差异。而在整车梯形车架层面，整体抗扭刚度主要由**左右纵梁跨距与横梁剪切格栅约束**决定：五十铃凭借 **8 根横梁**与加宽至 **1,080 mm** 的后车架外宽，实现了较上一代 RT 车架 **+20% 至 +23% 的抗扭刚度提升**（与丰田 Revo FIRM 车架较 Vigo 提升 **+20% 抗扭刚度**处于同一水平）。

### 2. 横梁布置架构、连接工艺与局部补强设计

1. **横梁数量、位置与几何形态：**
   - **五十铃 D-Max Hi-Lander（RG）：** 官方确认全系配备 **8 根横梁**（《Isuzu UTE Australia 24MY Specification Sheet》，第 2 页，`https://admin.i-motor.com.au/ssl/CMS/files_cms/98007_isuzu-d-max_specification-sheet-24my.pdf`，**第 1 级**，高置信度）。依次涵盖前散热器/保险杠横梁、前悬架下摆臂前后横梁、螺栓连接式变速箱支撑横梁、传动轴中间吊架/油箱前横梁、后板簧前吊耳横梁、后桥上方减振器横梁以及后备胎/尾部横梁。
   - **丰田 Hilux Revo Prerunner（`GUN135`）：** 官方图纸确认共 **7 个主要横梁工位**（若将前悬架下摆臂的前、后两道下沉式横梁分开单独计数，则为 8 根横向构件，见 `BM3250E` 图 `K123547C01.png` 与 `NM3250E` 图 `V113718C01.png`，**第 1 级**，高置信度）：
     1. 第 1 横梁（前副横梁，**440 MPa** 闭合箱型梁）。
     2. 第 2 横梁（前悬架下控制臂前、后下沉式托架横梁，标准钢材配合 Pre-Runner/4WD 专属的 **440 MPa** 外侧加强角板）。
     3. 第 3 横梁（变速箱支撑横梁，**440 MPa**，螺栓可拆卸连接）。
     4. 驾驶室后方/货厢前部中间横梁。
     5. 后板簧前吊耳横梁（端部呈喇叭口扩口过渡的闭合箱型横梁，采用**全周满焊 "All-Round Welding"** 与纵梁连接，见 `NM3250E` `V113718C01.png` 中的标注 `*a`）。
     6. 后减振器上支座/后桥前横梁。
     7. 后横梁（**440 MPa** 宽幅平板冲压横梁，承载备胎升降器与车尾模态刚度）。

2. **焊接与螺栓连接节点、应力集中控制与局部补强：**
   - **丰田的横梁端部全周满焊工艺（"All-Round Welding"）：** 在 `NM3250E` 章节 `NM100000000NEGS`（`https://gitlab.com/ToyotaManuals/n00148/-/raw/main/N00148/manual/ncf/contents/NM100000000NEGS.html`，图 `V113718C01.png`，**第 1 级**，高置信度）中，丰田明确指出：*"The crossmember and side rail connectivity is strengthened and a highly rigid frame structure is created by using all round welding at each crossmember and side rail welding spot."*（通过在每个横梁与纵梁连接点采用全周满焊，强化了横梁与纵梁的连接刚度。）配合横梁端部的喇叭形扩口，有效分散了交叉轴扭转时的翘曲双力矩（Bimoment），避免了断续焊缝端点的剪切疲劳开裂。
   - **丰田 Pre-Runner / 4WD 专属的前减振器塔座外侧 440 MPa 补强板：** 在 `BM3250E` 图 `K123547C01.png`（**第 1 级**，高置信度）中，丰田在所有 **4WD 与 Pre-Runner** 车架的高耸 **440 MPa** 前螺旋弹簧/减振器塔座正下方的纵梁外侧腹板上，额外贴焊了一块大面积 **440 MPa 高强度钢外侧补强板**（而在低底盘 2WD 车架图 `K123544C01.png` 中则没有这块 440 MPa 补强板），直接增强了前轮满载落坑冲击下的纵梁抗剪切与抗局部屈曲能力。
   - **五十铃的 `JSH590Y` 剪切式驾驶室悬置（Shear Body Mounts）：** 根据 `IMITPPD-BBG-GE-20001` 第 23 页与五十铃全球公报 `20191011_01.html`（**第 1 级**，高置信度），五十铃将驾驶室悬置支座升级为 **`JSH590Y`（590 MPa）** 钢材，并用**剪切式橡胶悬置（`シアーマウント`）**取代了传统的纯压缩式胶垫，大幅改善了大梁与驾驶室之间的高频振动隔离与支座抗撕裂疲劳寿命。

3. **裸车架总成质量（Frame Mass）：**
   - **一级供应商官方确认数值：** 为两家车企在泰国生产皮卡车架的 **Press Kogyo 株式会社**（通过泰日合资 **Thai Summit PK Corporation** 制造）在其官方网站公布了 *"Weld Frame for Pickup Truck & SUV"* 的量产参数：长度 **4.5–5.1 m**，宽度 **1.4 m**（含外伸支座），裸焊装车架总成质量为 **189–252 kg**（视驾驶室与驱动形式而定）。
   - *文献引用：* Press Kogyo Co., Ltd.，*Automotive Chassis Parts — Weld Frame for Pickup Truck & SUV*，`https://www.presskogyo.co.jp/en/products/car/chassis/`。**置信度：** 高。**证据分级：** 1（OEM 一级制造商官方文档确认）。

---

## 耐腐蚀性与长期耐久性分析（Corrosion and Long-Term Durability）

### 1. 疲劳寿命、开裂机理与真实世界结构失效案例

#### A. 严格区分五十铃 D-Max 的“前轮拱内衬钣金撕裂（`ซุ้มล้อหน้าฉีก`）”与梯形大梁本身的结构完整性
在泰国和澳大利亚皮卡社群中，常有人提及 D-Max 存在“前部开裂（`ซุ้มล้อหน้าฉีก`）”。严谨的工程核查证明，必须按**车型代际**与**结构子系统**将其彻底区分开来：
1. **第 2 代五十铃 D-Max（RT，2012–2019）—— 驾驶室白车身前机舱内衬裙板（Inner Fender Apron）薄钣金疲劳撕裂（并非梯形大梁开裂）：**
   - **技术论断：** 在 2012–2019 款第 2 代 RT 平台的 D-Max 与 MU-X 上，确实发生过机舱内电瓶托盘附近及前水箱框架悬置上方的 **0.8–1.0 mm 驾驶室白车身内翼子板裙板钣金（Inner Guard / Apron）**疲劳开裂，但**绝非下方的 `SAEJ1392050YLK` 梯形大梁纵梁开裂**。其根本原因是前水箱框架橡胶悬置与防火墙之间的相对挠曲变形，且在加装重型双电瓶或前部沉重的竞技牛栏杠（Bullbar）形成前悬悬臂梁载荷后被显著加剧。
   - **来源与发布日期：** Drive.com.au，*"Isuzu D-Max and MU-X inner guard cracking issue emerges"*，2019 年 2 月 25 日；4x4Earth 论坛主题帖 *"Dmax cracked engine bays"*，2017–2020。
   - **直接 URL 链接：** `https://www.drive.com.au/news/isuzu-d-max-and-mu-x-inner-guard-cracking-issue-emerges/`；`https://4x4earth.com/forum/index.php?threads/dmax-cracked-engine-bays.43211/`。
   - **置信度：** 高。**证据分级：** 2（独立维修车间检查与原厂维修案例确认）。
2. **第 3 代五十铃 D-Max（RG，2020–2026）—— 机舱裙板撕裂问题的解决与泰文社群 `ซุ้มล้อฉีก` 的真实含义：**
   - **技术论断：** 在第 3 代 RG D-Max（2020–2026）上，五十铃重新设计了前机舱内衬冲压件，将驾驶室 >390 MPa 高强钢比例提升至 46%，车架刚度提升 +20–26%，并改用 `JSH590Y` 剪切式车身悬置，彻底消除了原厂状态下的 RT 代机舱金属裙板撕裂问题。在泰国 2020–2025 款 RG D-Max 车友群中，高频出现的 `ซุ้มล้อฉีก` 一词实际上绝大多数是指车主改装加大尺寸轮胎（如 265/65R18 或 275/55R20）蹭胎导致的**塑料轮拱内衬撕裂（`พลาสติกซุ้มล้อฉีก`）**；而早期 RG D-Max 真正存在的前桥机械缺陷是**前悬架颠簸转向（Bump-steer）引发的前轮偏磨吃胎**（五十铃已于 2022 底/2023 年通过升级前转向节/羊角零件号解决）。
   - **来源与发布日期：** CarExpert Australia，*"Isuzu D-Max, MU-X steering parts updated amid tyre wear complaints"*，2023 年 11 月。
   - **直接 URL 链接：** `https://www.carexpert.com.au/car-news/isuzu-d-max-mu-x-steering-parts-updated-amid-tyre-wear-complaints`。
   - **置信度：** 高。**证据分级：** 2（独立汽车媒体调查与 OEM 零件更新确认）。

#### B. 重载、拖挂与加装后桥气囊下的梯形大梁折弯与开裂（`แชสซีร้าว / แชสซีงอ`）
- **技术论断：** 在原厂额定总质量（GVW 2,650–3,000 kg）范围内正常使用时，无论是第 3 代 D-Max Hi-Lander（RG）还是第 8 代 Hilux Revo Prerunner（`GUN135`），均不存在系统性的梯形大梁疲劳开裂或折弯缺陷。**目前没有任何具有统计学意义的对比故障率数据表明这两款原厂未改装的 2WD 双排座车架中哪一款的失效率更高。** 两款车型在真实世界中记录在案的大梁折弯（"Banana-ing"）或开裂，几乎全部发生在以下两类极端改装或严重超载滥用场景中：
  1. **后悬重心过度后移超载 + 加装后桥辅助空气弹簧（Airbags）：** 拆掉原厂渐进式缓冲块、在后桥壳与纵梁上拱段之间加装高压辅助气囊，会将原本应由后钢板弹簧分散传递至前吊耳和后吊耳支座的垂向载荷，变成直接顶在后桥前方纵梁截面过渡区的集中点载荷。当配合沉重的后尾箱高盖、水箱以及 3.0–3.5 吨重型拖挂在搓板路高速冲击时，极易在后桥前方的纵梁上拱过渡处引发塑性屈服折弯或焊缝热影响区（HAZ）疲劳裂纹。
  2. **泰国商用极端超载（`รถคอกซิ่ง` / 载重 2–4 吨）与违规大梁打孔/横焊：** 当皮卡被超载至 2.5–4.0 吨且未安装合规副车架，或后市场改装店违反 OEM 改装指南（五十铃 `IMITPPD-BBG-GE-20001` 第 24 页；丰田 `BM3250E` `RM100000000NO8Z`）在丰田 **590 MPa**（`SPFH590`）纵梁或五十铃 **`SAEJ1392050YLK`** 纵梁的上下受拉翼缘上垂直施焊时，焊缝热影响区晶粒粗化与局部马氏体脆化会在焊趾（Weld Toe）处诱发疲劳裂纹。
- **疲劳与超载的冶金学权衡（Trade-Off）：**
  - 根据日本新日铁技术报告第 88 期（第 3.3 节，第 5 页），电弧焊车架结构的高周疲劳寿命主要受控于**焊趾缺口几何应力集中系数（$K_t$）与焊接残余拉应力**，而非母材的静态抗拉强度。因此，将母材从 440 MPa 级（`SAEJ1392050YLK`）提升至 590 MPa 级（`SPFH590`）虽然大幅提升了**抵抗静态超载大梁弯曲的屈服极限**，但对焊接工艺质量控制（如丰田的全周满焊与严禁火焰加热修复）提出了更严苛的要求，以防止高强钢对缺口敏感的 HAZ 疲劳开裂。
- **来源与发布日期：** Outback Travel Australia，*"Bent Dual Cab Utes — Why They Happen"*，`https://outbacktravelaustralia.com.au/4wd-mods-general-mods/bent-dual-cab-utes-why-they-happen/`；Nippon Steel TR No. 88，2003 年 7 月，第 5 页，`https://www.nipponsteel.com/en/tech/report/nsc/pdf/n8802.pdf`；RepairCert NZ Technical Bulletin #04-2024（*"The Effects of Repairing High Strength Steels"*），`https://www.repaircert.nz/storage/Technical-Bulletin_04-2024-The-Effects-of-Repairing-High-Strength-Steels.pdf`。
- **置信度：** 高。**证据分级：** 2 & 3（独立工程失效分析与冶金学原理确认）。

---

### 2. 泰国湿热多雨及洪涝环境下的耐腐蚀性能（`สนิมแชสซี`）

#### A. 原厂车架防腐涂装工艺对比（两车高度同源）
- **技术论断：** 泰产五十铃 D-Max（RG）与泰产丰田 Hilux Revo（`GUN135`）的梯形大梁均在泰国本土生产（核心供应商同为 **Thai Summit PK Corporation**，北榄府/罗勇府工厂），并采用完全相同的工业级防腐涂装基准工艺：碱性脱脂清洗、**磷酸锌转化膜预处理（Zinc-Phosphate Pretreatment）**，以及全浸式**阴极电泳涂装（C-EDP / E-coat）**并在 ~170–180°C 下烘烤固化（标准干膜厚度通常为 **20–35 $\mu\text{m}$**）。两款车架在原厂出厂时**均未采用热浸镀锌（Hot-Dip Galvanizing）**，且**纵梁内部腔体均未喷注原厂空腔防锈蜡（Cavity Wax）**。丰田在其第 8 代 Hilux 工程资料包中额外声明，其车架腐蚀裕度与电泳标准按 **“20 年耐腐蚀寿命（20-years corrosion resistance）”** 目标设计。
- **来源与发布日期：** Toyota Motor Europe 第 8 代 Hilux Press Kit，2016 年 5 月，第 27 页（*"achieve a 20-years corrosion resistance"*），`https://newsroom.toyota.eu/a-new-era-for-the-pick-up-but-every-inch-a-hilux/`；丰田 `BM3250E` 章节 `RM100000000NO8Z`（*"Rustproof high strength steel sheets are used for the body frame"*），`https://gitlab.com/ToyotaManuals/n00148/-/raw/main/N00148/manual/brm/contents/RM100000000NO8Z.html`；Thai Summit Group / TSPK 电泳涂装产线说明，`https://www.thaisummit.co.th/en/manufacturing/`。
- **置信度：** 高。**证据分级：** 1 & 2（OEM 官方文件与一级供应商制造规范确认）。

#### B. 为什么两款车在泰国均在提车数月内出现焊缝表面浮锈（`สนิมตามรอยเชื่อมแชสซี`）
- **技术论断：** 无论是五十铃 D-Max（2020–2026）还是丰田 Hilux Revo（2015–2025），在泰国提车后 **1 至 12 个月内**，均普遍在机器人 MIG/MAG 焊接焊缝边缘、冲裁支架锐边及悬架吊耳处出现红褐色表面浮锈，这一现象在泰国 Pantip 论坛与车主俱乐部中有大量实拍记录。
- **电化学与涂装物理根源：**
  1. **焊缝硅酸盐玻璃渣岛（Silica Slag Islands / `เกาะซิลิกา`）：** 机器人 MAG 气保焊使用富硅/锰脱氧焊丝（如 `ER70S-6` / JIS `YGW12`）时，会在焊趾表面析出微米级的玻璃态**不导电二氧化硅（$\text{SiO}_2$）渣岛**。若浸槽前未经 100% 彻底抛丸清理，磷酸锌晶核与阴极电泳漆无法在不导电的硅渣表面沉积，形成微米级针孔，在泰国常年 70–85% 的高相对湿度下迅速产生点状红锈。
  2. **烘烤表面张力边缘缩边效应（Edge Pull-Back / `ฟิล์มสีหดตัวตามขอบคม`）：** 在 180°C 电泳漆烘烤流平过程中，液态树脂受表面张力影响会从 `JSH590Y` / `440 MPa` 冲裁支架的 90° 锋利切口边缘和凸起的焊波峰顶轻微回缩，导致锐边处漆膜厚度仅剩 5–10 $\mu\text{m}$（而平坦腹板处为 25–30 $\mu\text{m}$）。
- **来源与发布日期：**
  - 五十铃 D-Max（RG）泰国车主实拍报告：Pantip 帖子 **41249204**（*"ออกรถป้ายแดงมา 6 เดือน สนิมขึ้นแชสซี ปกติไหมครับ"*，2022 年 2 月），`https://pantip.com/topic/41249204`；Pantip 帖子 **42517505**（*"สนิมที่คัสซี และช่วงล่าง D-max 2023"*，2024 年 2 月），`https://pantip.com/topic/42517505`。
  - 丰田 Hilux 泰国车主实拍报告：Pantip 帖子 **31255063**（*"สนิมใต้ท้องรถกระบะป้ายแดง"*，2013 年 11 月），`https://pantip.com/topic/31255063`。
- **置信度：** 高。**证据分级：** 3 & 4（电化学机理基于汽车涂装工程原理推导 [第 3 级]；实车表面焊缝浮锈由大量泰国车主实拍记录证实 [第 4 级]）。

#### C. 泰国气候下 5–10 年长期防腐表现：闭合箱型纵梁积泥/积水与劣质底盘装甲陷阱
- **闭合箱型纵梁内部的积水与淤泥滞留：** 由于两款车架均为全闭合箱型截面，并在侧面和底部设有工艺定位孔与排水孔（例如丰田 `BM3250E` `RM100000000M5V2` 标注的 `16 × 16 mm` 内侧槽钢基准孔与 `φ13 mm` 外侧槽钢基准孔），在经历泰国雨季内涝涉水或泥泞农田行驶后，细小的黏土淤泥极易沉积在纵梁下腹部及后板簧前吊耳前方的截面抬升过渡区。一旦排水孔被淤泥堵塞——或被后市场喷涂的厚重黑色沥青/橡胶型底盘装甲（`พ่นกันสนิมสีดำแบบยางมะตอย`）意外封死——滞留的湿泥将引发严重的**由内向外湿敷电化学腐蚀（Poultice Corrosion）**。
- **泰国 5–10 年二手车实车证据：** 在泰国内陆及中部地区（包括曼谷雨季涉水工况），车龄 5 至 10 年的 Hilux Revo（2015–2020）与 D-Max（RT/RG）车架主要表现为焊缝、后桥壳与板簧吊耳处的表面浮锈，**均未出现 2.3–3.2 mm 纵梁母材锈穿孔洞的结构性失效**。10 年内发生结构性锈穿的案例仅见于长期在泰国南部沿海高盐雾环境或海鲜运输盐水浸泡下作业、且外覆开裂剥落的厚层沥青底盘装甲锁死盐水的车辆。
- **针对泰国用车的工程养护建议：** 切勿在已有浮锈或潮湿的车架表面喷涂厚重硬化的黑色沥青/橡胶涂层（切勿以涂层看起来多黑多厚来评判防锈能力）；正确做法是在涉水后用高压水枪通过纵梁侧面孔洞冲洗内部泥沙，并向闭合箱型纵梁内腔及外部焊缝喷注**渗透性羊毛脂（Lanolin）或低粘度空腔防锈蜡（符合 JIS K 2246 标准）**。

---

## 悬架系统与底盘防护对比（Suspension and Underbody Comparison）

**2026 款五十铃 D-Max Hi-Lander Double Cab 2WD** 与 **丰田 Hilux Revo Prerunner Double Cab 2WD** 均采用**原厂高底盘（与 4WD 四驱版同姿态）**的底盘布局，这与低底盘两驱皮卡（`D-Max Cab 4 Low-Rider` 及 `Hilux Revo Z-Edition`）存在本质结构差异。

| 子系统 / 部件 | **2026 款五十铃 D-Max Hi-Lander Double Cab 2WD (`TFR41` / `TFR40`)** | **MY2024/2025 丰田 Hilux Revo Prerunner Double Cab 2WD (`GUN135`)** | **耐久性与车架载荷传递影响分析** |
| :--- | :--- | :--- | :--- |
| **前悬架形式与车架安装点设计** | 独立双叉臂配螺旋弹簧、充气减振器及横向稳定杆。车架纵梁上焊有**高位上控制臂安装塔座（High-Mounted Upper Control Arm Towers）**（`20191011_01.html`）。 | 独立双叉臂配螺旋弹簧、充气减振器及加粗横向稳定杆（`Mid`/`High`/`Rocco` 标配 `SuperFlex` 舒适调校）。车架配有**440 MPa 高耸弹簧塔座 + 440 MPa 纵梁外侧补强板**（`BM3250E` `K123547C01.png`）。 | 五十铃更高的上摆臂支座减小了上控制臂工作倾角，优化了侧倾中心并降低了制动/过弯时传递至车架塔座的水平弯矩；丰田则在所有 Pre-Runner/4WD 车架的前弹簧塔座外侧纵梁腹板上额外焊接了 **440 MPa** 补强钢板。 |
| **前转向节（羊角）、球头与轮毂轴承** | **锻造铝合金（Forged Aluminium Alloy）**转向节/直立柱（降低非簧载质量；2023 年更新了转向节几何以消除早期 RG 颠簸转向吃胎问题）；密封一体化前轮毂轴承单元；加大尺寸可单独更换球头。 | **重载锻造钢（Forged Steel）**转向节/直立柱；4 螺栓法兰盘密封一体化前轮毂轴承总成；重载上下球头。 | 五十铃的锻造铝合金转向节减轻了簧下质量，提升了铺装路面响应与滤振；丰田的锻造钢转向节在长期重载撞击深坑或非铺装路硬冲击下具备更高的抗屈服变形裕度。 |
| **后钢板弹簧设计与车桥布置形式** | **3 片式渐进钢板弹簧，采用 WSSP（*温态应力喷丸强化*）工艺**，**置于后桥上方（`แหนบวางบนเพลา` / Overslung）**；加宽了左右板簧横向跨距（`リーフトレッド拡大`，`20191011_01.html`）。 | **3 片式钢板弹簧（2020–2025 款 `Mid`/`High`/`Rocco` 标配 *SuperFlex Suspension*；早期或重载版为 5 片）**，**置于后桥上方（`แหนบวางบนเพลา` / Overslung）**；长度加长 **+100 mm**（达 **1,400 mm**），左右板簧横向跨距加宽 **+50 mm** 并向车架外侧外移（泰版宣传册第 5 页；TME 资料包第 28 页）。 | 两款高底盘 2WD 均采用**板簧置于后桥上方（`แหนบเหนือเพลา`）**布局，无需增高垫块即可获得高离地间隙（代价是轮胎接地点到板簧卷耳的垂直力臂大于桥下置板簧，在 400–450 Nm 大扭矩起步时桥壳扭转力矩略大）。五十铃的 **WSSP 温态喷丸工艺**在板簧表层引入深层残余压应力，在降低弹簧刚度提升舒适性的同时有效防止长期载重塌屁股。 |
| **后减振器安装几何位置** | 双筒充气减振器布置于**车架纵梁内侧（Inboard）**，左右两根均朝前倾斜平行布置，且安装倾角较第 2 代 RT **更趋垂直 7 度**（`20191011_01.html`）。 | 双筒充气减振器布置于**车架纵梁内侧（Inboard）**第 6 横梁上，**左右两根均朝前倾斜平行布置**（`NM3250E` `V113718C01.png`；TME 资料包第 27 页——取代了 Vigo 时代一前一后的交叉布置 `โช้คไขว้`）。*(注：仅宽体版 2023+ Hilux GR Sport II / Rogue 将后减振器移至车架纵梁外侧)*。 | 两款标准高底盘 2WD 皮卡均将后减振器以平行前倾方式安装在**纵梁内侧**。五十铃将减振器倾角立直 7°，提高了垂向阻尼做功效率（$\cos\theta$ 更接近 1.0）。 |
| **原厂底盘护板防护（Skid Plates）** | • **前部发动机/水箱下方：** 水箱与前横梁下方配有冲压钢制下护板 + 发动机下方复合材料/高分子护板。<br>• **变速箱下方：** 敞开式（由高位横梁保护）。<br>• **燃油箱（76 L 高密度聚乙烯 HDPE 工程塑料）：** 位于左侧纵梁内侧，配有模压高分子防石击护盾与钢制吊带。 | • **前部发动机/水箱下方：** 冲压钢制前发动机/水箱下护板，螺栓固定于第 1 与第 2 横梁。<br>• **变速箱下方：** 敞开式。<br>• **燃油箱（80 L 高密度聚乙烯 HDPE 工程塑料）：** 深藏于左侧纵梁内侧上方，配有模压树脂护板与钢制固定带。 | 由于两款车均为 2WD 后驱，前桥下方均无脆弱的前差速器壳体或四驱分动箱凸出。两车均采用永不生锈的 **HDPE 塑料燃油箱**，并受到高截面左侧主纵梁的侧面遮挡保护。 |
| **最小离地间隙与底盘暴露度** | **235 mm**（`L` 配 255/65R17）/ **240 mm**（`Z`、`M`、`X-Series` 配 265/60R18），测量点位于后桥差速器壳体最低点（`4_door_brochure_2026_be4df560bb.pdf` 第 6 页）。 | 双排 Prerunner 全系均为 **217 mm**（`hiluxrevo-prerunner-4x4-2024-65ff9db103811942741600.pdf` 第 9 页），测量点位于较大的后桥差速器壳体最低点。 | D-Max Hi-Lander 在后桥差速器壳体处拥有**高出 +18 至 +23 mm 的最小离地间隙**，在通过深车辙或泰国雨季积水漂浮物时，后桥壳体托底风险更低。 |

*悬架与底盘防护表文献引用：* 五十铃全球公报 `20191011_01.html`（`https://www.isuzu.co.jp/world/newsroom/details/20191011_01.html`）；五十铃 2026 款产品手册（`https://assets.isuzu-tis.com/4_door_brochure_2026_be4df560bb.pdf`，第 6 页）；丰田 MY2024 产品手册（`https://toyotasummit.co.th/assets/images/newcar/brochure/18b4655c-68e8-4118-ba55-665f75d13c39/hiluxrevo-prerunner-4x4-2024-65ff9db103811942741600.pdf`，第 9 页）；丰田 `NM3250E`（`NM100000000NEGS`，`V113718C01.png`）；Toyota Motor Europe 2016 Hilux Press Kit（第 27–28 页，`https://www.scribd.com/document/408363159/2016-toyota-hilux-dpl-en-1-pdf`）。**置信度：** 高。**证据分级：** 1（OEM 官方文件确认）。

---

## 独立安全与碰撞测试证据（Independent Safety Evidence）

### 1. 正面与侧面碰撞载荷路径：为什么“更厚/更硬的大梁”并不等同于更高的碰撞安全性
在非承载式（Body-on-Frame）皮卡中，正面碰撞安全性取决于**前段大梁纵梁受控、渐进的轴向手风琴式溃缩与向下折弯变形**以耗散碰撞动能（$E_k = \frac{1}{2} m v^2$），降低传递至乘员舱的减速度峰值，同时依靠高刚性的**乘员舱生存空间（BIW）**抵抗侵入变形。
- **丰田 Hilux Revo 的前部大梁三阶段受控屈曲吸能机制（`NM3250E` `NM100000000NEGO`，图 `V113699C01.png`）：**
  - 丰田《新车技术特性手册》明确图解了为什么 Hilux Revo 将车架钢材从主纵梁的 **590 MPa** 阶梯降级为前吸能延伸段（`SIDE RAIL EXTENSION ASSEMBLY`）的 **440 MPa**：
    - **第 1 阶段（`*c`）：** **440 MPa** 前延伸段发生轴向手风琴式塑性压溃（`*f`），吸收初始碰撞能量。
    - **第 2 阶段（`*d`）：** 前悬架弹簧塔座正后方的纵梁预设了向内/向下折弯诱导点（`*j`, `*g`），使前段车架向下弯曲下潜，避免直接向后顶穿防火墙。
    - **第 3 阶段（`*e`）：** 驾驶室地板下方的纵梁下折点（`*i`, `*h`）吸收残余能量，同时由 **590 MPa / 440 MPa GOA 高刚性驾驶室**保持乘员生存空间。
  - *文献引用：* 丰田 `NM3250E`，章节 `NM100000000NEGO`（*SAFETY FEATURES > Collision Safety Body*），图 `V113699C01.png`，`https://gitlab.com/ToyotaManuals/n00148/-/raw/main/N00148/manual/ncf/contents/NM100000000NEGO.html`。**置信度：** 高。**证据分级：** 1（OEM 官方文件确认）。
- **五十铃 D-Max（RG）在 ANCAP 移动渐进可变形壁障（MPDB）测试中的碰撞相容性罚分：**
  - 在 **ANCAP（2020/2022）** 采用 50 km/h 移动渐进可变形壁障（MPDB）正面偏置碰撞规程测试时，第 3 代五十铃 D-Max 的乘员舱保持了**稳定（Stable）**（成人乘员保护得分率 `86%`，获评 **5 星**），其 **980 MPa / 1,500 MPa** 驾驶室立柱有效防止了座舱坍塌。然而，ANCAP 对 D-Max 扣除了**最高上限的 4.00 分碰撞相容性罚分（Compatibility Penalty）**，原因是 D-Max 坚硬的前纵梁对迎面碰撞测试壁障造成了局部穿透，意味着在与轻型家用轿车发生对向碰撞时对对方车辆具有较高的结构侵略性。
  - *文献引用：* ANCAP Technical Report，《Isuzu D-Max (Jul 2020 – onwards)》，第 2 页（"Frontal Offset (MPDB) — Penalty for structure/compatibility: -4.00 points"），`https://cdn.ancap.com.au/app/public/assets/3e7ebc8e1bc3c20a4e84f4e9ada644776148d6d0/original.pdf?1761112583`。**置信度：** 高。**证据分级：** 2（独立碰撞测试机构报告确认）。

### 2. 东盟新车评价规程（ASEAN NCAP）泰产双排座车型同规程正面交锋对比
泰国制造的第 3 代五十铃 D-Max 与泰国制造的改款丰田 Hilux Revo 均于 **2020 年**在**完全相同的 ASEAN NCAP 2017–2020 测试规程**下（64 km/h 40% 偏置可变形壁障正面碰撞 + 50 km/h UN R95 侧面移动壁障碰撞）接受了实车碰撞测试：

| ASEAN NCAP 测试指标（2017–2020 规程） | **2020 款五十铃 D-Max Double Cab 1.9L (`TFR87`，泰国制造)** | **2020 款丰田 Hilux Revo Double Cab 2.8L (`GUN126`，泰国制造)** | **结构表现与泰国在售 2WD 配置适用性分析** |
| :--- | :--- | :--- | :--- |
| **ASEAN NCAP 综合总分与星级** | **83.16 / 100 分（5 星）** | **83.42 / 100 分（5 星）** | 综合总分几乎打平（仅差 0.26 分）。 |
| **成人乘员保护（AOP —— 原始分 /36 与加权分 /50）** | **30.76 / 36.00 分**（加权：**42.72 / 50.00**） | **32.93 / 36.00 分**（加权：**45.74 / 50.00**） | Hilux Revo 在 AOP 原始分上**高出 +2.17 分**，主要得益于更低的小腿胫骨载荷以及测试基础车型标配的**主驾膝部气囊（共 3 气囊）**。 |
| **64 km/h 正面 40% 偏置碰撞得分（ODB）** | **12.76 / 16.00 分**<br>*(乘员舱保持**稳定 Stable**；胸部保护为 Marginal/Adequate；小腿为 Adequate)* | **14.93 / 16.00 分**<br>*(乘员舱保持**稳定 Stable**；头部、颈部、膝盖/大腿骨及右小腿均为 Good 优秀)* | 两款车架与驾驶室均防止了 A 柱折曲和脚部空间撕裂。Hilux Revo 凭借**第 3 具主驾膝部气囊**与前纵梁三阶段受控溃缩，在正面碰撞假人读数上取得了 **+2.17 / 16.00 分的优势**。 |
| **50 km/h 侧面移动壁障碰撞得分（MDB）** | **16.00 / 16.00 分（满分）** | **16.00 / 16.00 分（满分）** | 两款高底盘双排皮卡的门槛与梯形大梁纵梁高度均高于移动壁障冲击中心，由大梁纵梁与门槛直接承力，未直接侵入假人胸腔。 |
| **儿童乘员保护（COP）** | **42.78 / 49.00 分**（加权：**21.83 / 25.00**） | **44.13 / 49.00 分**（加权：**22.52 / 25.00**） | 两车后排均标配 ISOFIX 接口与顶部固定锚点（Top Tether）。 |
| **对泰国市场 2026 款 D-Max Hi-Lander 2WD 与 MY24/25 Hilux Revo Prerunner 2WD 各配置的适用性** | • **走量的入门/中配（`2.2 L`、`2.2 Z`、`X-Series`）：** 仅配备 **2 具安全气囊**（前排双气囊；**无膝部、无侧气囊、无侧气帘**），与 ASEAN NCAP 测试的 2 气囊车款一致。<br>• **顶配（`2.2 M`、`3.0 M`）：** 配备 **6 具安全气囊**（前排、前侧、前后贯穿气帘）+ EPS 高阶 ADAS（`4_door_brochure_2026_be4df560bb.pdf` 第 7 页）。 | • **走量的入门/中配（`2.4 Entry`、`2.4 Mid`）：** 全系标配 **3 具安全气囊**（前排双气囊 + **主驾膝部气囊**），与 ASEAN NCAP 测试的 3 气囊车款一致。<br>• **高配（`2.4 High`、`Rocco`）：** 配备 **7 具安全气囊**（前排、主驾膝部、前侧、前后贯穿气帘）（`hiluxrevo-prerunner-4x4-2024-65ff9db103811942741600.pdf` 第 10 页）。 | **泰国市场真实被动安全差异：** 在走量的入门与中配 2WD 双排车型（`L`/`Z` 对比 `Entry`/`Mid`）上，Hilux Revo Prerunner 标配了**主驾膝部气囊（3 气囊）**，直接使其在正面碰撞下肢与整体 AOP 得分（14.93 vs. 12.76/16）上领先；而在高配车型上，Revo `High`/`Rocco` 提供 **7 气囊**，多于 D-Max `M` 的 **6 气囊**。 |

*独立安全章节文献引用：* ASEAN NCAP 官方评估报告，《Isuzu D-Max (2020)》，`http://www.aseancap.org/x/result.php?slug=isuzu-d-max-2` 及 PDF `https://aseancap.org/v2/wp-content/uploads/2020/11/Isuzu-D-Max-Result-1.pdf`；ASEAN NCAP 官方评估报告，《Toyota Hilux (2020)》，`http://www.aseancap.org/x/result.php?slug=toyota-hilux-2020`；ANCAP Technical Report《Toyota Hilux (Jul 2019 onwards)》，`https://www.ancap.com.au/safety-ratings/toyota/hilux/818873`。**置信度：** 高。**证据分级：** 2（独立碰撞测试确认）& 1（泰国各配置气囊数由 OEM 宣传册确认）。

---

## 证据缺口（Evidence Gaps）

若要从数学上以 100% 的绝对确定性证明哪一款裸梯形大梁具有更高的绝对弹性刚度和极限承载能力，仍需获取以下目前未在任何公开宣传册、改装厂指南或车身维修手册中披露的 OEM 专有数据或实测数据：

| 缺失的工程参数 | 所需的确切文件或物理实测手段 | 该参数可能如何影响最终结论 |
| :--- | :--- | :--- |
| **1. 两款车架全长范围的超声波/千分尺壁厚分布图（$t_w, t_f$）** | 在去除表面电泳漆至裸钢后，使用经校准的超声波测厚仪（UT）或解剖千分尺，对泰国市场实车 `TFR41` D-Max Hi-Lander 与 `GUN135` Hilux Revo Prerunner 纵梁的 10 个纵向断面进行实测，或获取 Press Kogyo / TSPK 内部冲压零件蓝图。 | 由于丰田主纵梁采用 **590 MPa** 钢材（`SPFH590`，$\sigma_y \approx 430\text{ MPa}$），而五十铃采用 **`SAEJ1392050YLK`**（$\sigma_y \ge 345\text{ MPa}$），如果丰田为了减重将其单层钢板壁厚减薄了 $\ge 25\%$（例如丰田用 2.3 mm，而五十铃用 3.1 mm），则两款车架的屈服强度（$M_y$）将几乎持平，而壁厚更厚的 D-Max 车架反而会拥有高出 **~25% 的弹性抗弯与抗扭刚度（$EI_x, GJ$）**。反之，若两车采用相近的壁厚（~2.8–3.2 mm），则 Hilux Revo 车架的抗永久屈服折弯强度将**高出 ~25–35%**。 |
| **2. 完整的纵梁截面几何坐标函数 $b(x) \times h(x)$** | 从前保险杠至后吊耳的完整 CAD 截面切片或 OEM 工程蓝图尺寸表，包含外宽 $b(x)$、外高 $h(x)$、圆角半径 $R$ 及内部隔板/加强筋的确切位置。 | 由于惯性矩 $I_x$ 与高度的三次方 $h^3$ 成正比，抗弯模量 $Z_x$ 与 $h^2$ 成正比，中段纵梁高度哪怕相差 **15 mm**（例如 $h = 175\text{ mm}$ 对比 $160\text{ mm}$），就会带来 **~25% 的抗弯刚度变化**与 **~15% 的截面模量变化**。 |
| **3. 裸车架台架绝对刚度测试值（$\text{N}\cdot\text{m}/\text{deg}$ 与 $\text{N}/\text{mm}$）** | OEM 企业工程论文（如日本汽车工程学会 JSAE *Transactions* 或五十铃/丰田内部底盘台架报告），披露裸车架抗扭刚度（$\text{kN}\cdot\text{m}/\text{deg}$）与垂向抗弯刚度（$\text{kN}/\text{mm}$）的绝对数值，而非相对于各自上一代车型的百分比增幅（+20% / +23% / +26%）。 | 两家车企均仅公布相对于自身前代车型的提升百分比（Hilux Revo 较 Vigo 提升 +20%；D-Max RG 较 RT 抗扭提升 +20–23% / 抗弯提升 +26%）。在缺乏上一代基准绝对值的情况下，相对百分比无法直接证明哪款车架的绝对刚度更高。 |
| **4. 钢厂质保书（MTR）实测屈服强度与焊接接头疲劳 $S\text{-}N$ 曲线** | 新日铁 / JFE / POSCO 泰国工厂向 Thai Summit PK 供应的 `SAEJ1392050YLK` 与 `SPFH590` 钢卷批次质保书（Mill Test Certificate），以及焊接节点在 $10^7$ 次循环下的疲劳 $S\text{-}N$ 曲线。 | `SAEJ1392050YLK` 规定的是*最小*屈服强度 345 MPa，但实际交货钢卷的平均屈服强度可能达到 370–390 MPa。同样，焊接结构在 $10^7$ 次循环下的疲劳寿命取决于焊趾过渡半径与除渣工艺，而非静态抗拉强度。 |
| **5. 循环盐雾腐蚀测试（CCT）与耐石击涂层测试数据** | TSPK 生产的五十铃与丰田车架内外表面按 JASO M 609 / JIS Z 2371 标准进行的循环腐蚀出现红锈小时数及干膜厚度（DFT）质检报告。 | 可明确判定丰田宣称的“20 年耐腐蚀目标”是否包含了比五十铃更厚的 C-EDP 电泳漆膜或改良的磷化预处理工艺。 |

---

## 最终工程裁定（Final Verdict）

### 1. 车架材料等级与冶金质量（Frame Material Quality）
- **胜出者：** **主纵梁材质由丰田 Hilux Revo Prerunner 2WD（`GUN135`）胜出**；**驾驶室悬置支座材质由五十铃 D-Max Hi-Lander 2WD（`TFR41`/`TFR40`）胜出**。
- **裁定依据：** 丰田官方车身维修手册（`BM3250E` `RM100000000TR7F`，图 `K123547C01.png`）确凿证实，Hilux Revo Pre-Runner 在整个中段与后段主纵梁（含内外层槽钢）上全部采用 **590 MPa 级高强度钢（`SPFH590` 级别）**，并在可更换前吸能延伸段、前弹簧塔座、纵梁外侧补强板及主横梁上采用 **440 MPa 级高强度钢**。五十铃官方改装厂指南（`IMITPPD-BBG-GE-20001`，第 23 页）确凿证实，D-Max 在纵梁与横梁上采用 **`SAEJ1392050YLK`**（$\ge 345\text{ MPa}$ 屈服 / $\ge 415\text{–}440\text{ MPa}$ 抗拉），而在剪切式驾驶室悬置支座上采用 **590 MPa 级（`JSH590Y`）**高强钢（高于 Hilux Revo 的 **440 MPa** 驾驶室悬置支座）。
- **置信度评级：** **高（High）**（由 OEM 原厂维修与改装手册直接确认 —— 第 1 级证据）。

### 2. 车架钢板壁厚与截面设计（Frame Thickness and Cross-Section）
- **胜出者：** **钢板壁厚平手 / 无法单凭公开文件分出高下**（因两家 OEM 均未公开毫米级壁厚表）；**翼缘搭接截面效率由丰田 Hilux Revo 略占优**，**已确认纵梁宽度（84 mm）与 8 横梁格栅支撑由五十铃 D-Max 略占优**。
- **裁定依据：** 两家车企均未在公开手册中披露各分区的毫米级板厚，且网络上“4.8 mm vs. 3.6 mm”的说法已被证实为论坛讹传。然而，丰田 `NM3250E`（`V113717C01.png`）证实其采用了内外双 C 型槽钢上下水平翼缘重叠搭接的闭合箱型截面，将双倍钢板厚度集中在弯曲应力最大的上下表面；而五十铃 `IMITPPD-BBG-GE-20001`（第 9 页）证实其采用了 **84 mm** 宽幅闭合箱型纵梁、**1,080 mm** 宽幅后车架以及 **8 根横梁**支撑架构。
- **置信度评级：** **中（Medium）**（截面构型由 OEM 第 1 级文件确认；具体毫米壁厚 $t$ 未公开验证）。

### 3. 抗弯强度与抗扭强度（Bending and Torsional Strength）
- **胜出者：** **塑性超载抗弯屈服强度（极限屈服弯矩 $M_y$）由丰田 Hilux Revo Prerunner 2WD 胜出**；**弹性抗弯刚度与抗扭刚度（$EI_x, GJ$）平手 / 无法单凭公开文件分出高下**。
- **裁定依据：** 由于钢材杨氏模量（$E \approx 206\text{ GPa}$）完全相同，弹性刚度仅取决于几何尺寸。但抵抗永久塑性变形的屈服弯矩容量（$M_y = \sigma_y Z_x$）与屈服应力（$\sigma_y$）直接成正比。丰田的 **590 MPa（`SPFH590`）** 主纵梁配合上下双层搭接水平翼缘以及前弹簧塔座下方的 **440 MPa** 外侧补强板，使 Hilux Revo 在极端垂向超载或剧烈路面冲击下具备**高出约 22–35% 的抗永久折弯屈服能力**（除非五十铃未公开的纵梁壁厚比丰田厚出 $25\%$ 以上，但这与两车的整备质量及裸车架重量区间不符）。
- **置信度评级：** **中高（Medium-High）**（基于已核实的 OEM 钢材等级与闭合箱型结构力学推导 —— 第 1 级与第 3 级证据）。

### 4. 长期抗疲劳寿命（Long-Term Fatigue Resistance）
- **胜出者：** **原厂标定及中重度使用下打平（Tie）**；**极端改装下视具体工况而定**。
- **裁定依据：** 两款车架均在泰国使用纯净度极高的铝镇静、硫化物形态控制热轧汽车结构钢（`SAEJ1392050YLK` 与 `SPFH590`）制造。在第 3 代 RG D-Max（2020–2026）上，五十铃通过 `JSH590Y` 剪切式车身悬置、8 横梁和强化机舱冲压件，彻底解决了第 2 代 RT 的机舱内翼子板撕裂（`ซุ้มล้อหน้าฉีก`）问题。丰田则通过**横梁端部全周满焊（"All-Round Welding"）**（`NM3250E` `V113718C01.png`）最小化了循环扭转下的焊缝端点应力集中。反之，若车主计划在后市场对大梁进行非原厂违规施焊（如焊接改装支架），五十铃碳当量更低的 `SAEJ1392050YLK`（440 MPa 级）纵梁对焊接热影响区（HAZ）脆化的敏感度略低于丰田的 590 MPa 纵梁。
- **置信度评级：** **高（High）**（由 OEM 手册、技术通报及大量实车检验记录支持 —— 第 1、2、3 级证据）。

### 5. 耐腐蚀性能（Corrosion Resistance）
- **胜出者：** **平手（Tie）**。
- **裁定依据：** 两款车架均在泰国同一一级供应链体系（Thai Summit PK / Press Kogyo）内完成冲压、MAG 焊接、磷酸锌预处理及阴极电泳涂装（C-EDP / E-coat），均无热浸镀锌或原厂内腔防锈蜡。两车在泰国湿热气候下均会因焊缝不导电硅酸盐渣岛与电泳漆锐边缩边而在焊缝处出现早期表面浮锈（`สนิมตามรอยเชื่อม`）；同时，只要保持闭合箱型纵梁排水孔畅通、不在潮湿浮锈表面盲目封死厚沥青装甲并定期喷注空腔防锈蜡/羊毛脂，两款车架在非沿海盐雾的泰国本土环境下均可轻松使用 10 年以上而不发生结构性锈穿。
- **置信度评级：** **高（High）**（由 OEM 维修手册与广泛的泰国实车案例确认 —— 第 1、3、4 级证据）。

### 6. 泰国实际拥车综合耐用性（Practical Ownership Durability in Thailand）
- **胜出者：** **按使用场景分胜负 —— 重载拉货、烂路高强度耐造性与前部碰撞可维修性选丰田 Hilux Revo Prerunner 2WD；高速铺装稳定性、涉水离地间隙（240 mm）与空载驾乘平衡性选 2026 款五十铃 D-Max Hi-Lander 2WD。**
- **裁定依据：**
  - **选择丰田 Hilux Revo Prerunner 2WD（`GUN135`）的场景：** 如果你的核心诉求是主纵梁的最大抗屈服折弯裕度（**590 MPa** 主纵梁 + **440 MPa** 前弹簧塔座外侧补强板）、重载锻造钢前转向节、**模块化的前部碰撞大梁可维修性**（丰田 `BM3250E` `RM100000000MUPM` 专门在弹簧塔座前方设计了允许切割更换的 **440 MPa** 前纵梁吸能延伸段，使中轻度正面追尾事故无需更换整根车架总成），以及走量入门/中配车型更完善的被动安全保护（标配含**主驾膝部气囊在内的 3 气囊**，对比 D-Max `L`/`Z` 的 2 气囊）。
  - **选择 2026 款五十铃 D-Max Hi-Lander 2WD（`TFR41`/`TFR40`）的场景：** 如果你的核心诉求是更现代化的动力总成（**2.2 Ddi MaxForce 8AT** 或 **3.0 Ddi 450 Nm 6AT**）、应对泰国雨季内涝积水时**高出 +18 至 +23 mm 的最小离地间隙**（235–240 mm 对比 217 mm）、更长的轴距（3,125 mm vs. 3,085 mm）与更宽的轮距（1,570 mm vs. 1,540/1,550 mm）、抗疲劳衰减的 **WSSP 温态喷丸** 3 片式后板簧，以及隔振更细腻的 `JSH590Y` 剪切式驾驶室悬置。
- **置信度评级：** **高（High）**。

### 7. 总体优胜结论与综合置信度（Overall Confidence in the Winner）
- **总体裁定：** **在纯粹的梯形大梁纵梁冶金等级与抗屈服折弯强度上，丰田 Hilux Revo Prerunner 2WD（`GUN135`）拥有有据可查的工程优势（置信度：中高 Medium-High）**；**在整车底盘综合耐用性、耐腐蚀寿命与结构刚度表现上，两车处于同一工程梯队、实用表现打平（置信度：高 High）**。
- **总结说明：** 由于丰田在整个主纵梁上使用了 **590 MPa** 级高强钢（由 `BM3250E` 官方证实），而五十铃在主纵梁上使用 **345 MPa 屈服 / ~440 MPa 抗拉（`SAEJ1392050YLK`）** 钢材并将 **590 MPa（`JSH590Y`）** 用于车身悬置支座（由 `IMITPPD-BBG-GE-20001` 官方证实），Hilux Revo 在纵梁母材本身的屈服强度指标上拥有更强的原厂证据支持。然而，由于两家制造商均未公开纵梁各分段的精确毫米壁厚（$t$）及裸车架抗扭刚度（$\text{N}\cdot\text{m}/\text{deg}$）台架测试绝对值，在对两款实车车架进行超声波测厚之前，无法在弹性刚度指标上宣布单一绝对胜出者。

---

## 文献来源附录（Source Appendix）

### 1. 五十铃官方技术文件、产品手册与维修手册
1. **Isuzu Motors International Operations (Thailand) Co., Ltd. (IMIT) ——《ISUZU D-MAX For General Export BODY BUILDERS GUIDE》（2020 年 4 月版，文档编号 `IMITPPD-BBG-GE-20001`）**：披露 `SAEJ1392050YLK` 车架纵梁材质、`JSH590Y` 车身悬置支座材质（第 23 页）、84 mm 单根纵梁宽度、857/1,080 mm 前后车架外宽（第 9 页）以及车架钻孔/焊接规范（第 24 页）。
   - URL: `https://www.scribd.com/document/563840714/BBG-D-MAX-single-cab`
   - 档案馆快照 URL: `http://web.archive.org/web/20251230051818/https://www.scribd.com/document/563840714/BBG-D-MAX-single-cab`
2. **Tri Petch Isuzu Sales Co., Ltd. ——《Official 2026 Isuzu D-Max 4-Door (Cab 4 & Hi-Lander) Brochure》（印刷编码 `PR0226`，2026 年 2 月）**：泰国市场 MY2026 完整技术规格参数表（第 6 页）。
   - URL: `https://assets.isuzu-tis.com/4_door_brochure_2026_be4df560bb.pdf`
3. **Tri Petch Isuzu Sales Co., Ltd. ——《Official 2026 Isuzu D-Max Owner's Manual》（`คู่มือการใช้รถ ISUZU D-MAX 2026`）**：第 8 章（"Main Data and Specifications"，第 8-1 至 8-13 页 / PDF 第 593–605 页），涵盖 `TFR41`（`RZ4F-TC` 2.2L）与 `TFR40`（`4JJ3-TCX E5` 3.0L）。
   - URL: `https://assets.isuzu-tis.com/d_max_owner_manual_2026_58baae5400.pdf`
4. **Tri Petch Isuzu Sales Co., Ltd. —— 官方车型配置与整备质量交互对比数据库**：公布 2026 款 Hi-Lander 四门 2WD 全系各配置的精确整备质量（`1,835–1,950 kg`）。
   - URL: `https://www.isuzu-tis.com/compare`
5. **Isuzu Motors Limited（日本）—— 第 3 代 D-Max 全球首发工程新闻公报（2019 年 10 月 11 日）**：确认纵梁截面扩大、剪切式驾驶室悬置、驾驶室白车身采用 980 MPa 及 46% >390 MPa 高强钢、以及前悬架高位上控制臂支座。
   - 英文版 URL: `https://www.isuzu.co.jp/world/newsroom/details/20191011_01.html`
   - 日文原版 URL: `https://www.isuzu.co.jp/newsroom/details/20191011_01.html`
6. **Isuzu Motors Limited ——《Official Isuzu D-Max (2020-) Rescue Sheet》（文档编号 `MPA-TF-RSE-2001AU-01`，Version 01，第 3 页）**：乘员舱白车身 590、780、980 及 1,500 MPa 高强钢分布彩色区域图。
   - URL: `https://www.isuzu.co.jp/world/ci/rescue/pdf/australia_en_2020.pdf`
7. **Isuzu UTE Australia ——《24MY Isuzu D-Max Specification Sheet》**：确认全系采用含 8 根横梁的独立全长重载车架（第 2 页）。
   - URL: `https://admin.i-motor.com.au/ssl/CMS/files_cms/98007_isuzu-d-max_specification-sheet-24my.pdf`
8. **Isuzu Motors ——《2020MY- Isuzu D-Max Body Repair Manual》（样页与车架尺寸图）**：确认 >390 MPa 高强钢禁止加热修复规定（第 4 页）及 2WD 高底盘与低底盘专属车架尺寸图（`dmax_11.jpg`）。
   - URL: `https://cargeometry.org/isuzu/887-isuzu-d-max-tfr-tfs-2020-2025-body-repair-manual.html`

### 2. 丰田官方技术文件、产品手册与维修手册
9. **Toyota Motor Corporation ——《Toyota Hilux 8th-Gen Body Repair Manual (`BM3250E`)》，章节 `RM100000000TR7F` / `RM100000000M5US`（*STRUCTURAL OUTLINE*）**：包含官方车架高强钢分布图 `K123547C01.png`（`Double Cab Frame: for 4WD and Pre-Runner`）与 `K123544C01.png`（`for 2WD`），确凿证明 **590 MPa** 主纵梁以及 **440 MPa** 前吸能延伸段、弹簧塔座、外侧补强板、主横梁与驾驶室悬置支座。
   - URL: `https://gitlab.com/ToyotaManuals/n00148/-/raw/main/N00148/manual/brm/contents/RM100000000TR7F.html`
10. **Toyota Motor Corporation ——《Toyota Hilux Body Repair Manual (`BM3250E`)》，章节 `RM100000000NO8Z`（禁止对高强钢车架加热修复）、`RM100000000M834`（前纵梁端盖板 277 mm 周长焊缝）、`RM100000000MUPM`（前纵梁吸能延伸段 146 mm / 172 mm 切割更换规程）及 `RM100000000M5V2` / `M5V3`（4WD 与 Pre-Runner 车架 3D/2D 基准尺寸图）**：
    - 禁止加热修复 URL: `https://gitlab.com/ToyotaManuals/n00148/-/raw/main/N00148/manual/brm/contents/RM100000000NO8Z.html`
    - 前纵梁端盖板 URL: `https://gitlab.com/ToyotaManuals/n00148/-/raw/main/N00148/manual/brm/contents/RM100000000M834.html`
    - 前纵梁延伸段更换 URL: `https://gitlab.com/ToyotaManuals/n00148/-/raw/main/N00148/manual/brm/contents/RM100000000MUPM.html`
    - 4WD 与 Pre-Runner 3D 车架尺寸图 URL: `https://gitlab.com/ToyotaManuals/n00148/-/raw/main/N00148/manual/brm/contents/RM100000000M5V2.html`
11. **Toyota Motor Corporation ——《Toyota Hilux 8th-Gen New Car Features Manual (`NM3250E`)》，章节 `NM100000000NEGR`（*LIGHTWEIGHT AND HIGHLY RIGID BODY*）、`NM100000000NEGS`（*BODY SHELL > Frame*，图 `V113717C01.png` 双 C 搭接箱型截面 & 图 `V113718C01.png` 横梁全周满焊）及 `NM100000000NEGO`（*SAFETY FEATURES*，图 `V113699C01.png` 前纵梁三阶段受控屈曲）**：
    - `NM100000000NEGR` URL: `https://gitlab.com/ToyotaManuals/n00148/-/raw/main/N00148/manual/ncf/contents/NM100000000NEGR.html`
    - `NM100000000NEGS` URL: `https://gitlab.com/ToyotaManuals/n00148/-/raw/main/N00148/manual/ncf/contents/NM100000000NEGS.html`
    - `NM100000000NEGO` URL: `https://gitlab.com/ToyotaManuals/n00148/-/raw/main/N00148/manual/ncf/contents/NM100000000NEGO.html`
12. **Toyota Motor Thailand Co., Ltd. ——《Official MY2024 (Euro 5) Hilux Revo Prerunner & 4x4 Brochure》（2024 年 3 月，第 9–10 页）**：泰国市场 Hilux Revo Double Cab Prerunner 2x4（`GUN135`）最终核实规格与配置表。
    - URL: `https://toyotasummit.co.th/assets/images/newcar/brochure/18b4655c-68e8-4118-ba55-665f75d13c39/hiluxrevo-prerunner-4x4-2024-65ff9db103811942741600.pdf`
13. **Toyota Motor Thailand Co., Ltd. ——《Official Hilux Revo Double Cab Brochure (`B10303T-18090`, 第 5 页)》与《Hilux Travo 全球首发新闻公报》（2025 年 11 月 10 日）**：确认 FIRM 车架截面较 Vigo 增大 +20 mm 以及 2025 年 11 月的车型换代时间线。
    - Revo FIRM 宣传册 URL: `https://www.toyotalibra.co.th/Files/Name2/CONTENT5c2d6d94dd00d7001d67e0b6056720342042307.pdf`
    - Hilux Travo 首发公报 URL: `https://www.toyota.co.th/en/news/HILUX-TRAVO-AND-HILUX-TRAVO-e`
14. **Toyota Motor Europe ——《8th-Gen Toyota Hilux Press Kit》（2016 年 5 月，第 26–28 页）**：确认抗扭刚度提升 +20%、纵梁/横梁截面扩展达 +30 mm、20 年耐腐蚀目标及平行前倾后减振器布置。
    - URL: `https://newsroom.toyota.eu/a-new-era-for-the-pick-up-but-every-inch-a-hilux/`
    - 完整 PDF 存档: `https://www.scribd.com/document/408363159/2016-toyota-hilux-dpl-en-1-pdf`

### 3. 独立安全测试、冶金学文献、一级供应商与实际耐用性来源
15. **Press Kogyo Co., Ltd. ——《Automotive Chassis Parts: Weld Frame for Pickup Truck & SUV》**：一级车架制造商量产参数（189–252 kg 裸车架质量，4.5–5.1 m 长度）。
    - URL: `https://www.presskogyo.co.jp/en/products/car/chassis/`
16. **Nippon Steel Technical Report No. 88 ——《Development of High Strength Steels for Automobiles》（2003 年 7 月，第 5 页）**：详述 440 MPa（`SAPH440`）与 590 MPa（`SPFH590`）热轧卡车大梁钢材及电弧焊疲劳极限。
    - URL: `https://www.nipponsteel.com/en/tech/report/nsc/pdf/n8802.pdf`
17. **I-CAR New Zealand ——《PanelTalk》关于 Holden Colorado / Isuzu D-Max（2012 年 5/6 月刊，第 44–46 页）与 Toyota Hilux（2013 年 7/8 月刊，第 52–56 页）的碰撞维修技术报告**：
    - D-Max/Colorado URL: `https://i-car.co.nz/wp-content/uploads/2018/10/Holden-Colorado-MayJune-2012.pdf`
    - Hilux URL: `https://i-car.co.nz/wp-content/uploads/2018/10/Toyota-Hilux-JulyAug-20131.pdf`
18. **ASEAN NCAP 与 ANCAP 官方碰撞测试报告（2020 款 Isuzu D-Max 与 2020 款 Toyota Hilux）**：
    - ASEAN NCAP D-Max (2020): `https://aseancap.org/v2/wp-content/uploads/2020/11/Isuzu-D-Max-Result-1.pdf`
    - ASEAN NCAP Hilux (2020): `http://www.aseancap.org/x/result.php?slug=toyota-hilux-2020`
    - ANCAP D-Max 技术报告: `https://cdn.ancap.com.au/app/public/assets/3e7ebc8e1bc3c20a4e84f4e9ada644776148d6d0/original.pdf?1761112583`
19. **实地耐用性、流言溯源与泰国防锈讨论文献**：
    - "4.8 mm vs 3.6 mm" 流言原始出处（`4x4earth.com` 第 61 楼）: `https://4x4earth.com/forum/index.php?threads/another-bent-chassis-discussion.40039/page-4`
    - 2025 泰国超级皮卡锦标赛技术规则（5 mm 切口补强钢板规定，第 5 页）: `https://www.thailandsuperseries.net/wp-content/uploads/2025/05/2025-Technical-Regulations-TH-Super-Pickup.pdf`
    - RT 代 D-Max 机舱内衬钣金开裂报道（Drive.com.au，2019 年 2 月）: `https://www.drive.com.au/news/isuzu-d-max-and-mu-x-inner-guard-cracking-issue-emerges/`
    - RG 代 D-Max 转向节更新报道（CarExpert，2023 年 11 月）: `https://www.carexpert.com.au/car-news/isuzu-d-max-mu-x-steering-parts-updated-amid-tyre-wear-complaints`
    - 泰国新车大梁焊缝浮锈实拍讨论（Pantip）: `https://pantip.com/topic/41249204`, `https://pantip.com/topic/42517505`, `https://pantip.com/topic/31255063`
