# 🎬 Opening Demo Idea — /loop 5m

## Demo Concept

開場直接讓 Claude Code 跑一個 5 分鐘 loop：

`/loop 5m design claude code workshop hands on tutorial for beginner`

目的：
- 一開場就展示 Claude Code 不只是 chat，而是真的能持續工作
- 讓觀眾先看到「agent 在自己跑」的感覺
- 後面再拆解 Claude Code 的工作方式、prompt、context、輸出品質

## Why this works

- 比靜態 slides 更有震撼感
- 對學生/老師/工程師/企業家都直觀：它真的在幫你做事
- 跟 workshop 主題直接對齊：Claude Code 自己幫忙設計 Claude Code workshop
- 5 分鐘足夠讓它產出有內容的結構，不會拖太久

## Suggested script

### On screen
```text
/loop 5m design claude code workshop hands on tutorial for beginner
```

### Speaker line
> “Instead of telling you what Claude Code is, let me show you. I’m going to give it one sentence, and for the next five minutes it will keep working on its own.”

> “While it runs, I’ll explain what’s actually happening under the hood — context loading, tool use, iteration, and output refinement.”

## What to do during the 5 minutes

1. 先下 `/loop 5m ...`
2. Claude Code 開始跑後，你切回 slides
3. 用 3-4 張 slide 解釋：
   - Claude Code 是什麼
   - 它不是 autocomplete，是 agent
   - 它會讀 context、執行、反覆修正
4. 5 分鐘後切回終端，看成果
5. 當場點評：
   - 哪裡做得好
   - 哪裡需要人類補 prompt / 補 context
   - 這就是「agentic engineering」

## What to emphasize

- 同一句 prompt，Claude Code 不是只回一段文字，而是持續迭代
- AI 的價值不只是回答問題，而是持續工作
- 真正的 skill 在於：你怎麼設計任務、怎麼給 context、怎麼評估結果

## Risks / backup

### Risk 1: output 太普通
解法：事先準備一版錄好的 terminal 輸出或截圖

### Risk 2: loop 中斷 / 網路問題
解法：改成預錄影片 + 說明這是同樣 prompt 的備份結果

### Risk 3: 結果太長
解法：只截取最有價值的 3 個部分（outline / exercise ideas / beginner pitfalls）

## Best placement in talk

放在最開頭，第 1-2 分鐘就做。

流程：
1. 開場一句 hook
2. 立刻下 `/loop 5m ...`
3. Claude 跑時，你開始講 slides
4. 中段回來看結果

## Key message

> Claude Code is not just answering. It is working.
