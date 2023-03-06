# chat-gpt-trial.js

Create chat completion API（Chat GPT API）のサンプルコード

https://platform.openai.com/docs/api-reference/chat/create?lang=node.js

## 事前準備

下記ページでAPI Keyを発行しておく（`sk-`から始まる文字列）

https://platform.openai.com/account/api-keys

## インストール

```bash
npm i
```

## 実行

```bash
OPENAI_API_KEY=[API Keyをここにコピペ] node index.js
```

イメージ

```bash
OPENAI_API_KEY=sk-******************************** node index.js
```

## 結果

```js
{
  role: 'assistant',
  content: '\n' +
    '\n' +
    '!\n' +
    '\n' +
    "As an AI language model, I don't have feelings and emotions, but it's great to assist you with anything you need! How can I be of service today?"
}
```
