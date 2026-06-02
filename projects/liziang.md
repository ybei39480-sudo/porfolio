<style>
@media print {
    @page { margin: 0.3cm 0.8cm 0cm 0.8cm; }
}
body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans CJK SC", sans-serif;
    color: #222;
    line-height: 1.7;
    font-size: 13px;
    margin: 0;
    padding: 0;
}
.header-container {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-bottom: 2px;
}
.header-left { flex: 1; }
.photo-box {
    width: 75px;
    height: 100px;
    border: 1px solid #ccc;
    background-color: #f5f5f5;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 10px;
    color: #888;
    margin-left: 16px;
    -webkit-print-color-adjust: exact;
    print-color-adjust: exact;
}
.photo-box img { width: 100%; height: 100%; object-fit: cover; }
h1 { font-size: 24px; text-align: left; margin-top: 0; margin-bottom: 10px; letter-spacing: 2px; }
h3 { font-size: 14px; color: #1a4a75; margin-top: 6px; margin-bottom: 4px; border-bottom: 1.5px solid #1a4a75; padding-bottom: 3px; }
p { margin: 2px 0; }
.bullet-list { margin: 6px 0; padding-left: 0; list-style-type: none; }
.bullet-list li { margin-bottom: 6px; text-align: left; padding-left: 12px; position: relative; line-height: 1.7; }
.bullet-list li::before { content: "•"; position: absolute; left: 0; color: #222; }
.contact-line { font-size: 12px; color: #444; margin-bottom: 4px; }
.contact-line span { margin-right: 14px; }
.line-row { display: flex; justify-content: space-between; margin-top: 8px; margin-bottom: 4px; font-size: 13px; }
.project-name { font-weight: 600; }
</style>

<div class="header-container">
    <div class="header-left">
        <h1>李梓昂</h1>
        <div class="contact-line">
            <span>电话：15990962069</span>
            <span>邮箱：2941988664@qq.com</span>
        </div>
        <div class="contact-line" style="margin-top: 2px; font-weight: bold; color: #1a4a75;">
            求职意向：产品经理（AI / 用户）
        </div>
    </div>
    <div class="photo-box">
        <img src="../一寸_2.png" alt="一寸照片">
    </div>
</div>

### 教育背景
<div class="line-row">
    <span>中国海洋大学（985 211 双一流）</span>
    <span>电子信息工程（本科）</span>
    <span>2024.09 - 2028.06</span>
</div>
<ul class="bullet-list">
    <li>专业主修课程：数据结构、C语言程序设计、线性代数、微机结构和原理等。</li>
    <li>获得证书：大学英语四级（CET-4）、普通话二级甲等、计算机二级等。</li>
</ul>

### 专业技能
<ul class="bullet-list">
    <li><b>产品设计</b>：能独立撰写结构完整的 PRD，涵盖用户画像、需求分析、功能定义、异常边界与验收标准，善于将模糊需求转化为可落地的产品方案。</li>
    <li><b>数据分析</b>：具备结构化数据思维，熟练使用 MySQL 进行数据查询与清洗，能从用户反馈中提炼量化指标并驱动产品决策。</li>
    <li><b>AI 驱动开发</b>：熟练使用 Claude Code 完成从需求分析、原型构建到文档撰写的全流程，能通过 Prompt 工程将产品方案直接转化为可交互原型，缩短方案验证周期。</li>
    <li><b>技术理解</b>：具备编程基础（C / C++ / Python），理解数据结构与算法边界，能准确判断技术可行性与实现成本，有效降低产品-研发对齐成本。</li>
    <li><b>协调沟通</b>：EE 工科背景，能有效拉通研发、设计对齐目标与优先级，主导需求确认到方案评审的全链路沟通。</li>
</ul>

### 项目经历

<div class="line-row">
    <span class="project-name">12306 候补功能交互与逻辑优化方案</span>
    <span>核心负责人</span>
    <span>2026.01 - 2026.03</span>
</div>
<ul class="bullet-list">
    <li><b>项目背景</b>：12306 候补功能长期存在放票策略不透明、成功率指示失效等问题，用户无法感知进度与兑现概率；同时单车次不可候补导致整单报错、已填信息频繁丢失，候补提交完成率仅 62%。</li>
    <li><b>项目目标</b>：作为项目核心负责人，独立负责从问题定位、方案设计到需求文档输出的全流程，目标是提升候补流程透明度和操作效率。</li>
    <li><b>项目内容</b>：自主收集 158 条用户反馈，通过归类分析定位两大核心痛点——候补过程不透明与提交流程繁琐；独立完成可视化建议面板方案设计，量化展示「多买一站 → 成功率 +25%」等可操作选项，并加入进度提示降低用户焦虑；提出后台批量处理方案，可一键剔除不可候补车次并保留已填信息，预计单次提交耗时可从 3.5min 降至 1.2min；拉通产品、研发、设计各方对齐目标，完成从需求确认到方案评审的全流程推进。</li>
    <li><b>项目成果</b>：输出完整产品方案文档，包括用户画像、功能定义和验收标准，并定义了可量化的评估指标（开车前 24h 预测准确率 ≥80%、候补提交完成率 ≥90%）作为后续落地的参考依据。方案基于 158 条真实用户反馈设计，核心功能设计均经过用户反馈归因验证。同时输出 A/B 测试方案，设计了两组对比实验的评估框架及分阶段上线计划。</li>
</ul>

<div class="line-row">
    <span class="project-name">闪动校园Pro 跑步体验优化方案</span>
    <span>设计负责人（校园自主调研项目）</span>
    <span>2026.04 - 2026.05</span>
</div>
<ul class="bullet-list">
    <li><b>项目背景</b>：校园强制跑步软件「闪动校园Pro」因防作弊机制过于严格，正常用户跑步过程中经常被随机人脸弹窗打断，信号不好时 GPS 定位漂移也会被判作弊，同学反馈很多但官方一直没有优化。</li>
    <li><b>项目目标</b>：作为设计负责人自主发起调研，独立完成从问题定位、方案设计到原型输出的全流程，产出可落地的完整方案。</li>
    <li><b>项目内容</b>：与 30+ 同学深度访谈，梳理完整的跑步体验流程，归纳核心矛盾——防作弊机制没有给正常用户留出容错空间；设计两套方案（优化防作弊规则 + 改善弱网定位）并对比评估，综合可行性和体验后推荐组合方案；使用 Claude Code 构建可交互原型验证核心流程，请访谈对象试用并收集反馈持续优化；产出涵盖用户画像、体验流程图、功能优先级和异常情况处理的完整需求文档。</li>
    <li><b>项目成果</b>：独立完成完整的产品调研与设计流程（用户访谈→痛点分析→方案设计→原型测试），方案经过 30+ 同学的原型试用验证，核心功能（人脸触发策略优化、弱网补偿）获得 90% 以上试用者认可，产出一套可直接评审的产品方案。</li>
</ul>

### 个人优势
<ul class="bullet-list">
    <li><b>跨职能协作</b>：在两个项目中独立承担产品与研发、设计的对接协调，完成从需求定义到方案输出的完整流转。</li>
    <li><b>需求拆解</b>：善于从零散的用户反馈中提炼核心问题，通过 158 条用户反馈归因 + 30+ 深度访谈验证了这套方法的可复制性。</li>
    <li><b>项目主导力</b>：独立主导两段产品项目，完成从 0 到 1 的方案设计。</li>
    <li><b>协调沟通</b>：工科背景能与研发顺畅对接，降低产品与技术之间的理解成本。</li>
    <li><b>英文能力</b>：能流畅阅读英文技术文档和产品资料，关注海外产品动态及AI发展。</li>
</ul>
