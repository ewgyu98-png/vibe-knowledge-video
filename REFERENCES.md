# 速查清单

## 交片前三问（遮字幕）

- [ ] 这是什么？（日常词）
- [ ] 在干什么？（一个动词）
- [ ] 明白了什么？（一句话论点）

## 八条规矩（打勾）

- [ ] 先形象后文案
- [ ] 主体像真东西（无点线圈框冒充）
- [ ] 动词真发生；示意处写「示意」
- [ ] 先例子后道理；开头先看见
- [ ] 提问/命名/结论可停画
- [ ] 一套世界 + 尺子 + 道具回场
- [ ] 无人声；画面现写不套模板
- [ ] 事实带出处

## 命令骨架（相对路径）

```bash
cd path/to/vibe-knowledge-film && . .venv/bin/activate
python scripts/new_film.py projects/<name> --world C
# 写完 storyboard.md + film.js 后：
python engine/render.py projects/<name> --sheet 16
python engine/render.py projects/<name> --jobs 4
python engine/render.py projects/<name> --events
python engine/audio.py  projects/<name>   # 或 --bgm file.mp3 -8
```

## 时长

- 样片：20–30s  
- 短片：45–90s  
- 先样片过三问，再加长  

## 科学示意（脉搏类）

- [ ] 已区分「血流」与「压力波」
- [ ] 数字标「约 / 示意」且分镜有出处
- [ ] 结尾有示意声明  

## 上游

- 引擎：https://github.com/Dave-cc/vibe-knowledge-film  
- 风格 / BGM：https://github.com/xiazhuo123456789/vibe-knowledge-video  
