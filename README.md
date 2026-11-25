# OpenGateway

## 服務

- OpenAI 相容 API（chat completions／responses／messages，支援串流）
- Base URL：`https://api.open-gater.com`
- 狀態頁：<https://opengater.github.io/llm-gateway-status/>
- 一個 API key，照量計價

## 模型（可呼叫清單）

目前只提供 GPT 與 Claude 的文字模型（chat／responses／messages），最新世代優先。實際開放清單以 `GET /v1/models` 為準。

- **GPT**：gpt-6.2-sol／astra、gpt-6.1、gpt-6、gpt-5.x 等
- **Claude**：opus／sonnet／haiku 5.5、fable 5.x 等

## 定價

- 源頭原價計費（1.0×）
- 儲值包：最低 $10–20 起；XMR 付款確認即簽發 API key，餘額即儲值額
- USDT/USDC 付款 +5–10%

## 下單流程

1. 轉 XMR 到店面地址（儲值包金額以上）
2. 鏈上確認後簽發 API key 給你
3. 客戶端 base URL 指向店面端點即可使用

## 規則

- key 隨用隨扣、可隨時補儲
- 無 SLA 承諾、有狀況 24 小時內回應
- 尖峰公平使用，必要時節流

## 條款（三行版）

- 退款：未使用餘額可退，按實際用量扣帳後原路退回（鏈上手續費由客戶負擔）；已開始用量不整包退。
- 停權：上游暫停服務期間對應用量不計價；店面若停運，剩餘餘額全額退。
- 爭議：以 hash-chain 帳本為準，每月可對帳。
