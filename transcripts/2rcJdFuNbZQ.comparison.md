# Transcript comparison: local Whisper tiny vs YouTube captions

## Overall

- YouTube captions are clearly better for this lecture: cleaner wording, proper nouns preserved, fewer hallucinated character substitutions.

- Local Whisper tiny is usable for gist extraction, but much rougher for publication-quality Chinese transcript.

- Main local-STT failure mode: proper nouns and technical terms (e.g. OpenClaw, Claude Code, WhatsApp, context window) get mangled.


## Saved files

- `2rcJdFuNbZQ.youtube.zh-TW.txt` — YouTube caption transcript with timestamps

- `2rcJdFuNbZQ.local-whisper-tiny.txt` — raw local Whisper tiny transcript with timestamps

- `2rcJdFuNbZQ.cleaned-readable.zh-TW.txt` — cleaned readable Chinese transcript (derived from YouTube captions)


## Spot checks

### Around 0:00

**YouTube**

同學我們就開始來上課吧 今天這一堂課 我想要用 OpenClaw 開源的專案 當做一個例子 跟大家介紹 AI Agent 是怎麼運作的 我相信大家在報章雜誌上 已經聽過很多跟 AI Agent 有關的事情


**Local Whisper tiny**

同學我們就開始來上課吧 今天這一堂課 我想要用Open Core這個專開員的專案 當作一個例子 跟大家介紹AIAgen是怎麼運作的 相信大家在爆章炸至上 已經聽過很多跟AIAgen有關的事情


### Around 10:00

**YouTube**

到 2025 年的時候 AI Agent 看起來已經初步具備雛形 比如說 Claude Code 或者是 Gemini CLI 都可以看作是一種 能夠某種程度自主運行的 AI Agent 其實如果你有用過 Claude Code 的話 OpenClaw 跟 Claude Code 的能力


**Local Whisper tiny**

我們講了24AIAgin 到2025年的時候 AIAgin看起來已經粗布具備出行 比如說Calko的 或者是Germanice.ioi 都可以看作施走 能夠某種程度自主運行的AIAgin 其實如果你有用過Calko的話 這個Otto跟Calko的能力


### Around 20:00

**YouTube**

所以就有人真的做了一個網站 叫 Rent Human 它告訴你說 AI 需要你的身體 當 AI 需要你的身體的時候 它是真的可以在這一個網站上發一個文 說誰來幫我拿一個包裹 或誰來幫我拿一束花送給另外一個人 之類這樣的事情 不過這比較像是一個噱頭


**Local Whisper tiny**

所以就有人真的做了一個網站 叫Renter Human 他告訴你說AI需要你的身體 當AI需要你的身體的時候 他是真的可以在這一個網站上發一個文 說誰來幫我拿一個包裹 或誰來幫我拿一束花送給另外一個人 之類這樣的事情 不過這比較像這個學頭


### Around 30:00

**YouTube**

然後它會有一堆行為的準則 它會有一個長期的記憶 告訴它說它的主人有什麼樣的偏好 那這些文字檔 它就是文字檔 所以完全是你可以自己手動修改的 但其實不太建議你手動修改 比如說我嘗試把小金的名字直接改成大銀


**Local Whisper tiny**

是誰 然後他會有一堆行為的準則 他會有一個長期的記憶 告訴他說他的主人 有什麼樣的偏好 那這些文字檔 他就是文字檔 所以完全是你可以自己 手動修改的 但其實不太介意你手動修改 比如說我常識把小金的名字

