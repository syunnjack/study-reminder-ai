# Study Reminder AI

資格試験の一問一答・学習リマインド

## Repository

Recommended repository name: `study-reminder-ai`

## Domain candidates

Confirmed domain: `studyreminder.jp`

Other candidates:

- `studyreminder.jp`
- `ichimonai.jp`
- `aistudyalert.jp`
- `quizremind.jp`

## Concept

資格学習をLINE/メールで毎日通知し、AI解説、有料問題集、講座送客へつなげる。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static alert seed records in `src/App.jsx`
- Local state: localStorage for MVP saved alerts and UGC requests
- Notification integrations: LINE Messaging API, X API, transactional email provider, Slack Incoming Webhooks
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- 月額課金
- 有料問題集
- 講座 affiliate
- 模試販売
- 教育広告

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```
