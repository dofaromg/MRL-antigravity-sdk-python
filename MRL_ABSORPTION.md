# MRL 母體吸收記錄 — 本 repo 已被 MRL_AI_SYSTEM 去重蒸餾吸收

origin_signature: MrLiouWord
吸收日期: 2026-07-05
法則: 母體整合法則（Additive-Only）— 本檔為新增之定位標記，原始碼一律保留不動

本 repo（Google Antigravity SDK for Python 鏡像）已作為知識／技術模組被母體
`dofaromg/MRL_AI_SYSTEM` 吸收，回收為母體系統名稱產物。原始碼在此保存為
對照母本；可運行蒸餾版在母體側。

## 吸收對照表

| 本 repo 部位 | 母體產物（MRL_AI_SYSTEM） | 狀態 |
|---|---|---|
| `google/antigravity/types.py` | `09_workflow/MRL_AgentHarness_Types_v1.py` | 已吸收（沙盒 PASS 2026-07-05） |
| `google/antigravity/hooks/hooks.py` + `hook_runner.py` | `09_workflow/MRL_AgentHarness_HookLattice_v1.py` | 已吸收（沙盒 PASS 2026-07-05） |
| `google/antigravity/hooks/policy.py` | `09_workflow/MRL_AgentHarness_PolicyGate_v1.py` | 已吸收（沙盒 PASS 2026-07-05） |
| `google/antigravity/tools/tool_runner.py` + `tool_context.py` | `09_workflow/MRL_AgentHarness_ToolLoop_v1.py` | 已吸收（沙盒 PASS 2026-07-05） |
| `google/antigravity/triggers/` | `09_workflow/MRL_AgentHarness_TriggerPulse_v1.py` | 已吸收（watchfiles 依賴蒸餾去除） |
| `google/antigravity/agent.py` + `conversation/` + `connections/` | `09_workflow/MRL_AgentHarness_Kernel_v1.py` | 已吸收（閉源二進位以 ModelGateway 取代；OllamaGateway 待起動） |
| `google/antigravity/conversation/`（會話持久化語意） | 母體既有 `conversation.py` / `conversation_manager.py` | 去重 — 不重複吸收 |
| `google/antigravity/utils/otel.py`（OpenTelemetry） | — | 未吸收（外部依賴，待評估） |
| `google/antigravity/utils/interactive.py` | — | 未吸收（CLI 互動層，待評估） |
| `skills/` / `examples/` | — | 保留為參考文件（待起動） |

詳細去重蒸餾判定與驗收狀態見母體側
`docs/MRL_AgentHarness_吸收報告_v1.md`。
