# MedXpert Pre-Submission Check Skill

> 申报材料提交前最终自查 · 别在低级错误上浪费审评周期

---

## 🧰 MedXpert Skill Series · 医疗器械注册全家桶

这是 **MedXpert 医疗器械注册Skill系列** 的第二环。四个Skill形成完整闭环：

| 顺序 | Skill | 解决什么 | 状态 |
|------|-------|---------|------|
| ① | [medxpert-reg-path-skill](../medxpert-reg-path-skill/) | 这个产品去哪个市场走哪条路？ | ✅ v0.1 |
| ② | **medxpert-pre-submission-check-skill**（本项目） | 提交前最后自查，别踩P0级坑 | ✅ v0.1 |
| ③ | [medxpert-deficiency-reply-skill](../medxpert-deficiency-reply-skill/) | 收到发补信，怎么回才专业 | ✅ v0.1 |
| ④ | [medxpert-clinical-eval-skill](../medxpert-clinical-eval-skill/) | 临床评价报告怎么写 | ✅ v0.1 |

**同一个体系：LGD（有籍有证有门禁）· 同一个团队：MedXpert · 同一个风格：纯开源MIT协议**

---

## 这是什么？

你辛辛苦苦准备了三个月的申报材料，就因为一个P0级低级错误被FDA打回RTA拒收——白白浪费两个月。

这个Skill就是提交前的最后一道安检：把你的申报材料按P0/P1/P2三级过一遍，告诉你哪里会被退、哪里会被发补、哪里可以优化。

**它不是帮你写材料，是帮你查材料——提交前最后一遍查漏补缺。**

## 为什么需要它？

AI做申报材料最大的问题不是"写不出来"，是**写完了不知道哪里会被退**。

MedXpert Pre-Submission Check做的事情，是把注册专员的"踩坑经验"变成自查清单：
- 🔴 **P0级**：缺了/错了必被退审 → 一个都不能漏
- 🟡 **P1级**：大概率发补 → 尽量都改了
- 🟢 **P2级**：可优化 → 有时间就改

## 覆盖市场

- 🇺🇸 美国 FDA：510(k) / PMA / De Novo 提交前自查
- 🇪🇺 欧盟 MDR：CE技术文档自查
- 🇨🇳 中国 NMPA：注册资料自查

## 30秒开始

```bash
npx skills add https://github.com/stevenzhao07/medxpert-pre-submission-check-skill
```

安装后直接对Agent说：

```text
我的510(k)材料准备完了，帮我做一遍提交前自查
```

## 适合谁用？

- 注册专员提交前做最终自检
- 注册经理审核下属写的材料
- 第三方预审前先自己过一遍

## 与其他Skill的关系

- 做完[① 路径决策](../medxpert-reg-path-skill/) → 开始准备材料 → 用本Skill做提交前自查
- 提交之后收到发补 → 用③ 发补回复Skill
- 全程都需要临床评价 → 用④ 临床评价Skill

---

> ⚠️ **免责声明**：本Skill仅供AI Agent辅助自查参考，不构成合规意见。正式提交前请与注册专员/法规顾问复核。
>
> 📄 MIT 协议开源，可自由使用、修改、分发。
