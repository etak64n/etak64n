# etak64n 👋

🛠️ Self-hosted services, command-line tools, and libraries, mostly in Go, TypeScript on Cloudflare Workers, and Rust.

## ✨ Featured

### 🎬 [albireo](https://github.com/etak64n/albireo)

A private video library on Cloudflare Workers.

- 🔐 Cloudflare Access lets in only the people you allow.
- 📦 Videos and attached files stay in your S3-compatible bucket. The browser uploads and plays them directly, so their bytes never pass through the Worker.
- 💬 Series, search, ratings, and comments that link to a time in the video, with previews of attached PDFs, slides, and Markdown.
- 🌐 Each person chooses English or Japanese.
- 🚀 `pnpm stack:deploy` creates the D1 database, the Access application, and the Worker as one stack.

▶️ [Live demo](https://etak64n.github.io/albireo/) · 📖 [Docs](https://etak64n.github.io/albireo/docs/) · TypeScript

### 📊 [polaris](https://github.com/etak64n/polaris)

A dashboard on Cloudflare Workers that shows how much of each Free plan limit is left in your Cloudflare account.

- 🚦 On the Free plan, it shows when to upgrade to Workers Paid. On Workers Paid, it shows whether your usage fits the Free plan again.
- 💰 It estimates the cost of the current billing cycle.
- 📈 It charts the metrics of Workers, D1, R2, KV, Durable Objects, Queues, Workflows, Hyperdrive, Browser Run, and Workers AI, and shows which handlers of which Workers use the most CPU time.
- 🔑 It needs no database. It reads your account with a read-only API token, behind Cloudflare Access.

▶️ [Live demo](https://etak64n.github.io/polaris/) · TypeScript

## 🧰 More projects

- 🎞️ [deneb](https://github.com/etak64n/deneb): a self-hosted video API in one Docker image. It takes a file in one PUT, or over tus to resume, encodes it to HLS, writes captions with Whisper, and signs the URLs of playback and the webhooks. Go.
- ⏱️ [kickd](https://github.com/etak64n/kickd): an always-on agent that runs named commands from cron schedules, webhooks, file changes, and the command line, with a durable SQLite queue, on macOS, Linux, and Windows. Go.
- 📅 [calx](https://github.com/etak64n/calx): a native macOS command-line tool for Apple Calendar, on EventKit, with dates in natural language such as "tomorrow 3pm". Rust.
- 🕰️ [gocron](https://github.com/etak64n/gocron): a Go library without dependencies that parses cron expressions and works out when they fire, across time zones and changes of daylight saving time. Go.
