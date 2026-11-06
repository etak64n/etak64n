# etak64n

Self-hosted services, command-line tools, and libraries, mostly in Go, TypeScript on Cloudflare Workers, and Rust.
These are the projects to start with.

- [deneb](https://github.com/etak64n/deneb): a self-hosted video API in one Docker image. It takes uploads over tus, encodes them to HLS, writes captions with Whisper, and signs the URLs of playback and the webhooks. Go.
- [polaris](https://github.com/etak64n/polaris): a dashboard on Cloudflare Workers that shows how much of each Free plan limit is left, and the cost and metrics of Workers, D1, R2, KV, and the other products. TypeScript.
- [albireo](https://github.com/etak64n/albireo): a private video library on Cloudflare Workers. The videos stay in S3-compatible storage, and Cloudflare Access decides who can open the library. TypeScript.
- [kickd](https://github.com/etak64n/kickd): an always-on agent that runs named commands from cron schedules, webhooks, file changes, and the command line, with a durable SQLite queue, on macOS, Linux, and Windows. Go.
- [calx](https://github.com/etak64n/calx): a native macOS command-line tool for Apple Calendar, on EventKit, with dates in natural language such as "tomorrow 3pm". Rust.
- [gocron](https://github.com/etak64n/gocron): a Go library without dependencies that parses cron expressions and works out when they fire, across time zones and changes of daylight saving time. Go.
