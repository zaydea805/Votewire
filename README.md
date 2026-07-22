# Votewire

**Pin a question. Watch the votes stack up.**

Votewire is a no-login, share-a-code polling tool for group chats. Type a question, share the code, and watch votes roll in live — no accounts, no setup, no friction.

🔗 **Live app:** [votewire.vercel.app](https://votewire.vercel.app/)

---

## Why

Every group chat hits the same wall eventually: someone has to decide something, everyone says "idc, whatever you want," and it still somehow takes twenty minutes to land on an answer. Votewire is a faster way through that — post the question, share a code, and let the tally speak instead of five people saying "idc" at once.

## Features

- 📌 **Pin a poll** — write a question, add options, get a shareable code
- 🗳️ **Live results** — the tally updates in real time as votes come in
- 🔓 **No sign-in required** — for the poll creator or the voters
- 🔗 **Share by code** — anyone with the code can open and vote on the poll
- 🚀 **Zero setup** — no accounts, nothing to remember

## How it works

1. **Create a poll** — enter your question and add as many options as you need
2. **Pin it** — get a unique poll code
3. **Share the code** — drop it in a group chat, DM, wherever
4. **Watch it fill in** — votes tally live as people respond

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- npm / pnpm / yarn

### Installation

```bash
git clone https://github.com/<your-username>/votewire.git
cd votewire
npm install
```

### Development

```bash
npm run dev
```

The app will be available at `http://localhost:3000`.

### Build

```bash
npm run build
npm start
```

## Deployment

Votewire is built for [Vercel](https://vercel.com/):

```bash
vercel deploy
```

## Pages

| Page | Description |
|------|--------------|
| `/` | Home — create or open a poll |
| `/about.html` | About Votewire |
| `/terms.html` | Terms of use |
| `/privacy.html` | Privacy policy |

## Roadmap / Ideas

- [ ] Poll result export
- [ ] Custom expiration for polls
- [ ] Vote change / undo
- [ ] Pro tier features

## Contributing

Issues and pull requests are welcome. If something's broken or missing, opening an issue is genuinely useful.

## License

Add your license here (e.g. MIT).

---

Built and maintained by one person, kept running by a little advertising and an optional Pro tier.
