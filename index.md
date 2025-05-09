<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <title>郭志霖 • 个人主页</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body { max-width: 800px; margin: 2rem auto; font-family: sans-serif; line-height: 1.6; padding: 0 1rem; }
    h1, h2, h3 { color: #333; }
    .meta { color: #666; margin-bottom: 1.5rem; }
    section { margin-bottom: 2rem; }
    ul { list-style: none; padding-left: 0; }
    li::before { content: "•"; margin-right: .5em; color: #007acc; }
    a { color: #007acc; text-decoration: none; }
  </style>
</head>
<body>
  <h1>郭志霖（Guo Zhilin）</h1>
  <div class="meta">
    男 | 20 岁 | 山东青岛<br>
    📱 (+86) 133 7557 9633 | 📧 <a href="mailto:guozhilin.cs@mail.sdu.edu.cn">guozhilin.cs@mail.sdu.edu.cn</a>
  </div>

  <section>
    <h2>教育经历</h2>
    <p><strong>山东大学 · 计算机科学与技术（机电与信息工程学院）</strong><br>
    本科 | 2022.09 — 2026.06</p>
    <ul>
      <li>GPA: 90.89/100 （专业排名 9/106, 前 8.5%）</li>
      <li>获奖: 两次校级二等奖学金；两次院级“三好学生”；人工智能算法精英赛省级二等奖 (A–)</li>
      <li>主修课程: 计算机网络 (96), 离散数学 (93), 数据结构 (92), 深度学习概论 (94)</li>
    </ul>
  </section>

  <section>
    <h2>科研经历</h2>
    <h3>OpenGU · 图遗忘综合评测基准</h3>
    <p><em>VLDB (CCF‑A) 会议在投</em></p>
    <ul>
      <li>集成 16 种 SOTA 算法、13 个 GNN Backbones 与 37 个多域数据集</li>
      <li>3×3 实验配置，覆盖遗忘能力、效率、鲁棒性等多指标</li>
      <li>大规模实证实验，总结 8 项关键结论</li>
      <li>搭建 & 维护 GitHub 仓库，撰写技术文档，参与论文撰写</li>
    </ul>

    <h3>图文本攻击研究 · 融合图修改与文本攻击</h3>
    <p><em>2025.01 — 至今</em></p>
    <ul>
      <li>提出梯度驱动的图–文本联合攻击框架</li>
      <li>制定攻击成功率、扰动代价、隐蔽性指标</li>
      <li>实现基于梯度贪心优化的算法，在 Cora/Citeseer 上评测</li>
    </ul>
  </section>

  <section>
    <h2>实习经历</h2>
    <h3>中科院计算所 · 分布式系统监控平台开发（线上）</h3>
    <p><em>2025.02 — 至今</em></p>
    <ul>
      <li>基于 Prometheus & Grafana 构建监控平台</li>
      <li>PromQL 自动监控与预警</li>
      <li>多层级设备指标可视化看板设计</li>
    </ul>

    <h3>Nokia 朗讯 · 测试及前端开发助理</h3>
    <p><em>2023.07 — 2023.08</em></p>
    <ul>
      <li>开发自动化测试平台，Python 爬取 & 分析测试结果</li>
      <li>参与 WebXR Data Channel 通信功能设计与实现</li>
    </ul>

    <h3>青岛虚拟现实研究院 · Unity 开发实习生</h3>
    <p><em>2024.07 — 2024.08</em></p>
    <ul>
      <li>参与 VR 项目需求分析与整体策划</li>
      <li>整合 Unity3D Demo，负责角色/地图/UI/交互</li>
    </ul>
  </section>

  <section>
    <h2>联系方式</h2>
    <ul>
      <li><a href="https://github.com/FrankCoding00">GitHub</a></li>
      <li><a href="https://orcid.org/0000-0002-1234-5678">ORCID</a></li>
      <!-- 如有 Google Scholar、LinkedIn 可添加 -->
    </ul>
  </section>

  <footer style="text-align:center; margin-top:2rem; color:#999;">
    © {{ “now” | date: “%Y” }} Guo Zhilin · <a href="https://FrankCoding00.github.io">FrankCoding00.github.io</a>
  </footer>
</body>
</html>
