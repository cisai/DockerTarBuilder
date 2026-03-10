# QuickAdd Input Map

## Scope
This map defines canonical variable names used by QuickAdd captures and templates.

## Core Variables
| Variable | Meaning | Example |
|---|---|---|
| `project` | Project name | `FEOS 重构` |
| `topic` | Topic name | `代理与网络通道` |
| `person` | Person name | `张三` |
| `date` | Primary date | `2026-03-10` |
| `area` | Area or domain | `Systems` |
| `goal` | Objective | `完成入口配置` |
| `next_step` | Next concrete action | `补全 Log Interaction` |
| `idea` | Idea summary | `把排障做成固定清单` |

## Entry Mapping

### Create Project
- Required: `project`, `goal`, `next_step`, `area`, `date`

### New Topic
- Required: `topic`, `goal`, `next_step`, `date`

### New Person
- Required: `person`, `area`, `next_step`, `date`

### Log Interaction
- Required: `person`, `date`, `topic`, `next_step`
- Optional: `idea`
