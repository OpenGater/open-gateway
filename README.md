# OpenGateway

## 服務

- OpenAI 相容 API（chat completions／responses／messages，支援串流）
- Base URL：`https://api.open-gater.com`
- 狀態頁：<https://opengater.github.io/llm-gateway-status/>
- 一個 API key，照量計價

## 模型（可呼叫清單）

完整目錄以 `GET /v1/models` 即時為準（目前 270+）。主要家族：

- **Claude**（opus／sonnet／haiku／fable，含最新世代）
- **GPT**（gpt-6.2-astra／sol、gpt-5.5 系、image、realtime）
- **Gemini**（3.x pro／flash、embedding）
- **DeepSeek／Qwen** 等開放權重

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
