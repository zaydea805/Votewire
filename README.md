# Votewire 🗳️

Pin a question, share a code, watch the votes come in.

**[votewire.vercel.app →](https://votewire.vercel.app/)**

![Vercel](https://img.shields.io/badge/deployed-vercel-black?logo=vercel)
![License](https://img.shields.io/badge/license-MIT-green)
![No login](https://img.shields.io/badge/login-none%20needed-blue)

---

## The problem

You know the one. Group chat needs to decide something. Everyone says "idc, whatever you want." Twenty minutes later, still no answer, just more "idc"s.

## The fix

```
1. Type a question
2. Add some options  
3. Get a code
4. Send the code
5. Watch votes roll in live
```

That's it. No sign up, no app download, no "create an account to continue."

## Try it

> 🔗 Head to [votewire.vercel.app](https://votewire.vercel.app/), pin a poll, and share the code with this repo's readers to see it work — or just try it solo, it takes 10 seconds.

## Quick start

```bash
git clone https://github.com/zaydea805/votewire.git
cd votewire
npm install
npm run dev
```

→ open `http://localhost:3000`

<details>
<summary>Building for production</summary>

```bash
npm run build
npm start
```

</details>

<details>
<summary>Deploying</summary>

Built for Vercel:

```bash
vercel deploy
```

</details>

## Pages

| Route | What's there |
|---|---|
| `/` | create or open a poll |
| `/about.html` | why this exists |
| `/terms.html` | terms |
| `/privacy.html` | privacy |

## Why no login?

Because the second you ask someone to make an account just to vote in a group chat poll, they close the tab. Votewire skips that entirely — creator and voters both just show up and go.

## Contributing

Found a bug? Got an idea? Open an issue. PRs are welcome — this is a small project, so even small fixes are appreciated.

## License

MIT — see [LICENSE](./LICENSE)

---

<sub>Built by one person, kept alive by ads and an optional Pro tier. If you like it, share it.</sub>
