# Codex

## 定位
Codex 是用于把需求转为可执行变更的协作代理，适合在 Git 仓库中进行结构化交付。

## 适合做什么
- 把模糊任务拆成可提交的变更。
- 维护模板、规则、系统文档的一致性。
- 生成可追踪的 PR 说明与交付清单。

## 不适合做什么
- 代替长期产品决策。
- 在规则不明确时自行发明新体系。
- 绕开既有命名、路径、字段规范。

## Git 交接方式
1. 先读状态文件与规则文件。
2. 再做增量修改，避免重构式破坏。
3. 每次提交保持“单任务可回滚”。
4. 输出修改清单、理由、下一步。

## 常用任务模板
- `Refine QuickAdd core entries`
- `Build Codex topic page and handoff references`
- `Build proxy and network channel knowledge framework`

## 经验教训
- 先对齐变量名，再配置入口。
- 对象页与记录页必须分离，后期维护成本显著下降。
- 优先模板改造而不是实例逐页修补。
