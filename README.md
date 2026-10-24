# vibe知识视频生成 · Agent Skill

公开可复用的 **「Vibe知识大赏」** 实操技巧 Skill：无旁白、16:9、底部字幕，画面把句子演出来。

> 本仓库只放**技巧摘要与清单**，不含私人成片、账号或本地绝对路径。完整渲染引擎请用上游开源项目。

## 仓库里有什么

| 文件 | 说明 |
|---|---|
| [`SKILL.md`](./SKILL.md) | Agent Skill（frontmatter + 八条规矩 + 流水线 + 妙招） |
| [`REFERENCES.md`](./REFERENCES.md) | 一页速查清单 |
| `README.md` | 本说明 |

## 怎么用

1. 把本仓库 clone 到你的 Agent 技能目录，或让 Agent「先读 `SKILL.md`」。
2. 按 Skill 里的相对路径工作流建工程：`projects/<片名>/`。
3. **渲染**请安装上游引擎（MIT）：

```bash
git clone https://github.com/Dave-cc/vibe-knowledge-film.git
cd vibe-knowledge-film
python -m venv .venv && . .venv/bin/activate
pip install -r requirements.txt
playwright install chromium
python engine/get_fonts.py
```

4. 对 Agent 说：「用 vibe 知识大赏风格做一条《××》样片（20–30 秒）」。

可选风格 DNA / 合成 BGM：

- <https://github.com/xiazhuo123456789/vibe-knowledge-video>

## 规格速览

- 画幅：1920×1080 · 30fps · 横屏  
- 声音：无旁白；事件音效必配；BGM 可选且垫低  
- 样片 20–30s；完整短片约 45–90s  

## 许可与来源

本仓库文档以便于分享为目的整理；上游引擎与风格仓库各自遵循其 **MIT** 许可。引用事实时请自行核对出处。

## 隐私

请勿向本公开仓库提交：姓名、住址、坐标、邮箱、密钥或凭据、聊天记录、未脱敏成片工程。
