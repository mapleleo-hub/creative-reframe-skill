# status

最后更新 2026-11-12

## 当前进度

已发布。

- GitHub 公开仓库 `mapleleo-hub/creative-reframe-skill`，默认分支 master，首版提交 d15b879
- clawhub 提交 `creative-reframe@0.6.0`，返回 Update submitted，等 24 到 72 小时安全扫描后公开
- `npx skills add mapleleo-hub/creative-reframe-skill --list` 识别到 1 个 skill，仓库布局与 frontmatter 三项通过
- 泛化扫描通过，无个人路径与凭据
- 名字检查：clawhub 空闲，GitHub 无同名仓库，skills.sh 三处相关但不冲突
- 许可证 MIT，版权方 mapleleo-hub

## 下一步

1. 等 clawhub 安全扫描结束，确认 `https://clawhub.com/skills/creative-reframe` 可访问
2. 用 `npx skills find creative-reframe` 确认 skills.sh 索引生效，异步，可能滞后数小时
3. 本地中枢 `~/.agents/skills/creative-reframe` 指向 magpie library 的 v7，公开仓库是 v6，两条线分开维护

## 已知坑

**公开版与开发版分叉。** 公开的是 v6，本地 magpie library 里是 v7。改任一版都要手动同步，没有自动化。分叉原因：v7 删掉四块收束后只做过一次四轮测试，且回测结论当天被自己推翻，不足以对外发布。

**v6 的 R3 行为不稳定。** 三轮设置下第 3 轮净新增采购是 0／460／420，四轮设置下是 1240／4260／480，同一版本换会话长度中位差三倍。对外描述「零成本解决」会与实测不符，README 里只写了适用范围，没写这条主张。

## 决策记录

**2026-11-12 发布 v6 而不是 v7。** 理由：v6 在 36 次历史对话里守住率 9/9，v7 只有一次外部复现且结论被撤回。被否掉的方案：直接把 v7 发布，理由是它更新。反方理由：未验证的新版本对外发布等于让用户承担回测成本。

**2026-11-12 许可证选 MIT。** 被否掉的方案：CC BY-NC 4.0（禁商用）。理由是方法类文本用 NC 更常见，但采用门槛高，这个技能的定位是被人用而不是被人引用。

**2026-11-12 仓库放 E 盘 01_projects 下，编号 24。** 首次建目录时漏了编号与 README、status，已当场补。
