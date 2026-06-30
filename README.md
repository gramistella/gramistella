Rust-focused backend engineer building typed market-data systems, async services, and practical tooling. My focus is on functional systems, not visual/UI design. ![](https://hit.yhype.me/github/profile?user_id=60039721)

- Location: Italy
- Tools: Rust (Axum, Tokio, SQLx, Serde, Polars, Reqwest, Tower, Tracing, Utoipa, Slint), SQL (Postgres, SQLite), Docker Compose, GitHub Actions, Amazon S3, Python, Swift/Rust interop
- Recent work: Rust trading/prediction-market infrastructure; [10 merged PRs](https://github.com/Polymarket/rs-clob-client/pulls?q=is%3Apr+author%3Agramistella+is%3Amerged) to Polymarket's Rust CLOB client.
- Contact — Email (relay): [fixable40.bluffer@icloud.com](mailto:fixable40.bluffer@icloud.com)

---

## Selected public work

### [yfinance-rs](https://github.com/gramistella/yfinance-rs)
Rust Yahoo Finance client.
- High-level `Ticker` API for history, quotes, `fast_info`, fundamentals, options, holders, analysis, ESG, news, search, and screeners.
- Optional WebSocket or polling-based streaming.
- Fixture-backed offline/live tests for provider drift.
- Optional Polars `DataFrame` export through `paft` traits.

### [paft](https://github.com/paft-rs/paft)
Provider-agnostic financial types for Rust.
- Validated identifiers, constrained decimal types, money/price/quantity invariants, and serde-stable wire forms.
- Domain crates for instruments, market data, fundamentals, aggregates, and prediction-market models.
- Optional Polars `DataFrame` export, used by `yfinance-rs` and `df-derive`.

### [borsa](https://github.com/borsaorg/borsa)
Rust market-data router.
- Connector traits for granular provider capabilities and reusable connector SDK patterns.
- Routing policies with priority, fallback, latency strategies, and per-kind/per-symbol overrides.
- History merge/resampling with attribution, deterministic mocks, and cache/quota/blacklist middleware.
- Public connector work includes Yahoo, Binance, and Alpha Vantage adapters.

### [df-derive](https://github.com/gramistella/df-derive)
Polars `DataFrame` derive macros.
- Custom IR/lowering/codegen pipeline split across facade, runtime, and macro crates.
- Supports nested and generic schemas, `Option`/`Vec`/tuple projections, chrono temporal types, decimal backends, binary/string conversion attributes, and runtime trait overrides.
- Broad trybuild, runtime, and benchmark coverage.

### [cornerstone](https://github.com/gramistella/cornerstone)
Full-stack Rust application template.
- Axum + SQLx backend with SQLite/Postgres features.
- JWT auth with refresh-token rotation, OpenAPI, rate limiting, Docker, and CI wiring.
- Shared Rust DTOs with generated TypeScript; optional SvelteKit and Slint frontends.

### [stitch](https://github.com/gramistella/stitch)
Rust + Slint desktop utility for creating auditable LLM context packs from codebases.
- Precise file/directory selection, deterministic scrubbing filters, and round-trip generated trees.
- Shared/local profiles, watcher refresh, token/character stats, and release packaging.

### [serde_field_result](https://github.com/gramistella/serde_field_result)
Small `no_std` + `alloc` Serde helper for schema-drift-tolerant clients.
- Recoverable field-level deserialization with custom scalar decoders.
- Optional owned/borrowed raw JSON capture for invalid values.

> Earlier repos are archived for reference.

<sub>Note: I update this occasionally; the pinned repos are the most current. Last updated: 2026-06-30.</sub>

---

## Archived projects

<details>
  <summary><strong>Show archived projects</strong></summary>

### 🧵 [stitch-py](https://github.com/gramistella/stitch-py)
Original Python + Tkinter prototype of **Stitch**.
- Interactive tree view for selecting project files
- Filtering and exclusion controls
- Context generation for LLM workflows
- Superseded by the faster, native Rust + Slint rewrite

### 📸 [instagram-scraper-rs](https://github.com/gramistella/instagram-scraper-rs)
Archived fork of an async Rust client library.
- Session management and request workflow
- Persistent cookie stores, reel helpers, comment helpers, and a more explicit error model
- Kept for historical reference only

### 🔁 [repost_rusty](https://github.com/gramistella/repost_rusty)
Archived Rust media workflow system coordinated through Discord.
- PostgreSQL-backed state machine
- S3 temporary media storage
- Concurrent async workers
- ffmpeg + perceptual-hash duplicate detection

### 🤖 [copbot_rs](https://github.com/gramistella/copbot_rs)
Archived Rust/GTK rewrite experiment.
- GUI-driven task configuration
- Async HTTP requests and browser automation
- Local JSON profile storage

### 🎓 [yes-u-public](https://github.com/gramistella/yes-u-public)
Erasmus project built with Flask.
- Authenticated editing
- SQLAlchemy/MySQL persistence
- Media uploads and video poster generation

### 🧪 [copbot_java](https://github.com/gramistella/copbot_java)
First large project, built from 2017 to 2018.
- Java Swing control panel
- Concurrent workers, HTTP clients, HTML parsing
- JDBC/MySQL persistence

</details>

---

## Working together
Open to Rust backend/platform work with small teams.  
Remote is fine; EU relocation possible. Open to visa sponsorship for other locations. Contract or full-time.
