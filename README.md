
<div align="center">
  
<div align="center">
  <img src="./logo.png" alt="Logo" width="120" />
</div>

# 小朱诺诺的.skill

**一个蒸馏自 12 个「最O幻想」视频的 GalGame Skill**

每次都是独一无二的小朱诺诺的。

<br>

作者：**小鱿万事屋**　｜　文案原著：**汐鱼不吃鱼**　｜　logo作者：**MELLOW**

<br>

![License](https://img.shields.io/badge/license-MIT-pink)
![Platform](https://img.shields.io/badge/platform-Claude%20Code-blue)
![Game](https://img.shields.io/badge/game-守望先锋-orange)

</div>

---

## 安装

```bash
npx skills add https://github.com/MapleOAO/xiao-zhu-nuonuo-skill
```

---

## 使用

```
/小朱诺诺的          → GalGame 模式（默认）
/小朱诺诺的 chat     → 聊天模式，直接和她说话
/小朱诺诺的 help     → 查看帮助
```

---

## 两种模式

### 🎮 GalGame 模式

AI 生成全新独一无二的守望先锋邂逅故事。你们在某一局游戏里相遇——也许你是她的对手，也许是队友，也许是游戏房里唯一的陌生人。

- **每次都是全新场景**，触发器 × 时间背景 × 角色气质随机组合，不会重复
- **5-8 个选项 + 自由输入**，自由输入会被实时分析情感倾向
- **隐藏属性系统**：亲密度 / 理性好感 / 感性好感 / 紧张值，只在结局揭示
- **结局报告**：本局故事标题、关键选择回放、她从未说出口的内心独白、解锁标签

结局等级：

| 评级 | 亲密度 | 结局 |
|------|--------|------|
| S | 90+ | 她先开口，或你凑到她耳边说出那句话 |
| A | 70-89 | 没捅破窗户纸，但你们心里都明白了 |
| B | 50-69 | 成为固定游戏搭子，关系停在温暖的省略号 |
| C | 30-49 | 她有点失落地下线，留下没说完的话 |
| F | 0-29 | 好友申请发出又撤回，头像灯灭了 |

### 💬 聊天模式

她就是小朱诺诺的本人。没有剧情，没有属性，就是和她聊天。聊游戏、聊番剧、聊你最近在干嘛。

---

## 文件结构

```
xiao-zhu-nuonuo-skill/
├── SKILL.md             # 主入口（npx skills add 读取此文件）
├── character-dna.md     # 角色人设 DNA（她是谁，她怎么说话）
├── scene-dna.md         # 场景基因库（邂逅方式、时间背景、道具意象）
├── galgame-rules.md     # GalGame 规则（属性系统、选项格式、结局报告）
├── chat-rules.md        # 聊天规则（聊天模式行为准则）
└── 小朱诺诺的.md         # Claude Code 本地命令入口
```

每个文件职责单一，互相独立。想增加新的邂逅场景？改 `scene-dna.md`。想调整她的性格？改 `character-dna.md`。

---

## 兼容平台

| 平台 | 支持 |
|------|------|
| Claude Code | ✅ |
| Cursor | ✅（通过 npx skills add） |
| Trae | ✅（通过 npx skills add） |
| Windsurf | ✅（通过 npx skills add） |
| OpenClaw | ✅（通过 npx skills add） |
---

## 致谢

本 skill 的所有内容蒸馏自「汐鱼不吃鱼」发布的 12 个「最O幻想」视频。  

文案原著：**汐鱼不吃鱼**  
Skill制作：**小鱿万事屋**

---

<div align="center">

*"万一主播不是幻想的呢"*

</div>
