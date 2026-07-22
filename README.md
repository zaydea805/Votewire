# Votewire

Pin a question, share a code, watch the votes come in.

https://votewire.vercel.app/

## What it is

A polling tool for group chats. No accounts, no sign-in, nothing to set up. You type a question, add some options, and get a code back. Send the code to whoever, they vote, the tally updates as it happens.

Made for the "idc, whatever you want" problem — where everyone in the group chat is fine with anything and somehow it still takes twenty minutes to decide.

## How it works

1. Write your question and add options
2. Pin it — you get a short code
3. Send the code to people
4. Watch the votes come in live, no refreshing needed

## Running it locally

```bash
git clone https://github.com/zaydea805/votewire.git
cd votewire
npm install
npm run dev
```

Runs on `http://localhost:3000`.

To build for production:

```bash
npm run build
npm start
```

## Deploying

It's set up for Vercel — `vercel deploy` and you're done.

## Pages

- `/` — create or open a poll
- `/about.html` — about
- `/terms.html`
- `/privacy.html`

## Contributing

Open an issue if something's broken. PRs welcome too.

## License

MIT — see [LICENSE](./LICENSE)
