# 🗡️ Karpathy 最新 LLM / Agent 觀點整理（2026 三月）

## 一句話

他說自己已經好幾個月沒手寫一行 code，正處於「精神錯亂狀態」試圖搞清楚 AI 的極限在哪裡。

## 📌 三條主線

### 1. Vibe Coding → Agentic Engineering

- 2025 他發明了「Vibe Coding」（隨便 prompt 就能生 code）
- 2026/02 他宣布這個詞已經過時，提出新詞：**Agentic Engineering**
- 核心差異：你不再寫 code，你在**指揮、監督、編排 agent**
- 他自己從 80% 手寫 + 20% agent → 翻轉成 80% agent + 20% 手寫（12 月開始）
- 「我大概從 12 月以來沒手打過一行 code，這個變化之劇烈一般人根本沒意識到」

### 2. AutoResearch — The Karpathy Loop

- 他寫了 630 行 Python + 一份 markdown prompt → 丟到 GPU 上自動跑
- **2 天跑了 700 個實驗**，自動發現 20 個訓練優化
- 套到更大的模型上，訓練加速 11%
- Shopify CEO 拿去跑內部模型，一夜 37 個實驗、效能提升 19%
- 他的判斷：這就是 **self-improving AI loop** 的起點
- 「Agent 自己設計實驗、改 code、收數據、優化架構——全程無人」

### 3. Agent 是新的工作單位

- 「舊的 IDE 死了。新的工作單位是 agent team」
- 他開了 tmux 多格跑一堆 agent，正在做一個「agent command center」
- 用 OpenClaw 自動化家裡所有設備（Sonos、燈、安控、HVAC、泳池）→ 取名 **Dobby the House Elf**
- 「以前 6 個 app，現在一個 Dobby 搞定。我用 WhatsApp 叫它做事」
- 安全攝影機偵測到 FedEx 送貨，Dobby 會自動發 WhatsApp 通知他

## 💡 金句

- 「I'm in a state of psychosis trying to figure out what's possible」
- 「It's the person's skill issue to get the productivity out of agents」
- 「Programming has fundamentally changed. You're not typing code. You're spinning up agents.」
- Agent 真正難的不是寫 code，是端到端的 **full-stack autonomous deployment**

## 🎯 我的判讀

Karpathy 的立場很清楚：2026 是 agent 年，不是模型年。重點不再是 LLM 本身多強，而是**人怎麼編排 agent 去做事**。他自己就是最好的例子——連 OpenAI 共同創辦人都不手寫 code 了。

這對 Claude Code workshop 很有用，可以直接引用：
- 80/20 coding ratio 翻轉
- Agentic Engineering
- Dobby the House Elf（daily use scenario）
- AutoResearch（agent 做研究）

## Sources

- Fortune — OpenAI cofounder says he hasn't written a line of code in months
- Fortune — The Karpathy Loop: 700 experiments, 2 days
- NextBigFuture — Karpathy on Code Agents, AutoResearch and the Self Improvement Loopy Era of AI
