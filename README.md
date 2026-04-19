# teale-node (archived)

> **This repository has been consolidated into
> [teale-ai/teale-mono](https://github.com/teale-ai/teale-mono).**
>
> All history was preserved in the new repo via `git filter-repo`:
>
> - Rust supply-agent source → [`teale-mono/node/`](https://github.com/teale-ai/teale-mono/tree/main/node)
> - Original `docs/protocol.md` → [`teale-mono/docs/protocol.md`](https://github.com/teale-ai/teale-mono/blob/main/docs/protocol.md)
>
> `git log --follow` in `teale-mono` on any moved file traces back to the
> original commits here.
>
> The monorepo also ships several new components:
>
> | Path | What |
> |---|---|
> | [`protocol/`](https://github.com/teale-ai/teale-mono/tree/main/protocol) | Rust crate with all wire types, shared with the gateway |
> | [`gateway/`](https://github.com/teale-ai/teale-mono/tree/main/gateway) | OpenAI-compatible HTTP gateway (`gateway.teale.com`) |
> | [`stress/`](https://github.com/teale-ai/teale-mono/tree/main/stress) | Load + fault-injection harness for the supply fleet |
> | [`relay/`](https://github.com/teale-ai/teale-mono/tree/main/relay) | The relay server that used to live in `teale-mac-app/relay/` |
> | [`mac-app/`](https://github.com/teale-ai/teale-mono/tree/main/mac-app) | The Swift Mac + iOS app that used to live in `teale-mac-app/` |
>
> Open issues / PRs here are read-only. Continue new work in `teale-mono`.

---

## Former README (for reference)

Cross-platform TealeNet supply node agent. Run this on any machine
(Linux, Windows, macOS, Android) to contribute inference capacity to
the Teale network.

See [`teale-mono/node/teale-node.example.toml`](https://github.com/teale-ai/teale-mono/blob/main/node/teale-node.example.toml)
for the latest config.
