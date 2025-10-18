Rust-focused engineer. I build backends, pipelines, and small tools that actually run.  
I’m not a visual/UI designer; I keep UIs minimal and functional. ![](https://hit.yhype.me/github/profile?user_id=60039721)

- Location: Italy
- Tools: Rust (axum, sqlx, tokio, tower, tracing, utoipa), SQL (Postgres/SQLite), Docker Compose, GitHub Actions, Amazon S3, Python (utilities)
- Contact — Email (relay): [fixable40.bluffer@icloud.com](mailto:fixable40.bluffer@icloud.com)

---

## Active projects

### [borsa](https://github.com/borsaorg/borsa)
High-level, pluggable market data API for Rust with multi-provider routing.
- Intelligently routes requests across connectors with automatic fallback and data merging.
- Supports quotes, historical data, fundamentals, options, news, and real-time streaming.
- Built on `paft`, offering zero-boilerplate Polars DataFrame conversion.

### [yfinance-rs](https://github.com/gramistella/yfinance-rs)
Ergonomic Rust client for Yahoo Finance, an async-first rewrite inspired by the popular Python library.
- Historical prices, real-time streaming, options, fundamentals, and company info
- Async-first API using **tokio** and **reqwest**
- High-level `Ticker` interface for ease of use
- Builder pattern for complex queries
  
### [paft](https://github.com/paft-rs/paft)
Provider-agnostic financial types for Rust; a compact foundation for provider adapters.
- Standardized models (instruments, quotes/candles, money, options, fundamentals)
- Swap data providers without touching your analysis or app code
- Seamlessly converts to Polars `DataFrame`s (powered by `df-derive`) with an optional feature.

### [df-derive](https://github.com/gramistella/df-derive)
Derive macro that turns your Rust structs into Polars `DataFrame`s—fast, zero-boilerplate.
- Generates `ToDataFrame` + efficient columnar `[T]` conversion
- Flattens nested structs; supports `Option`, `Vec`, tuple structs, `DateTime<Utc>`, `Decimal`
- Schema introspection + `#[df_derive(as_string)]` for enum/string outputs

### [cornerstone](https://github.com/gramistella/cornerstone)
A practical starter for writing business logic from day one.
- Rust backend (**axum**, **SQLx**) with typed shared code; auth with refresh tokens
- Migrations for **SQLite** and **Postgres**
- Tests, Docker Compose, CI
- Optional frontends: **Svelte (web)** or **Slint (desktop)**

### [stitch](https://github.com/gramistella/stitch)
Context manager for LLM workflows, now rewritten in **Rust + Slint** with a fast, native UI.

> Earlier repos are archived for reference.

<sub>Note: I update this occasionally; the pinned repos are the most current. Last updated: 2025-10-18.</sub>

---

## Archived projects

<details>
  <summary><strong>Show archived projects</strong></summary>

### 🧵 [stitch-py](https://github.com/gramistella/stitch-py)
Original Python + Tkinter version of **Stitch**.
- Interactive tree view for selecting project files
- Filtering and exclusion controls
- Context generation for LLM workflows
- Superseded by the faster, native Rust + Slint rewrite

### 📸 [instagram-scraper-rs](https://github.com/gramistella/instagram-scraper-rs)
Adopted and modified an existing crate to support `repost_rusty`.
- Session management and request workflow
- Pagination and data extraction
- Error handling across API changes

### 🔁 [repost_rusty](https://github.com/gramistella/repost_rusty)
Rust-based reposting pipeline for Instagram Reels, coordinated via Discord.
- Scraping and media retrieval
- Database + Amazon S3
- Video handling and posting flow
- Scheduling and basic rate limiting
- Perceptual hashing to detect and avoid duplicate reels

### 🤖 [copbot_rs](https://github.com/gramistella/copbot_rs)
Rust rewrite of the `copbot_java` bot to learn Rust.
- Request/response handling
- Benchmarking and performance testing
- Early GUI experiments

### 🎓 [yes-u-public](https://github.com/gramistella/yes-u-public)
Erasmus project built with Flask.
- Models, forms, routes, templated pages, simple admin
- Built to be a straightforward working web app

### 🧪 [copbot_java](https://github.com/gramistella/copbot_java)
First large project.
- Multithreading and HTTP automation
- MySQL persistence
- Simple Swing control panel

</details>

---

## Working together
Open to Rust backend/platform work with small teams.  
Remote is fine; EU relocation possible. Open to visa sponsorship for other locations. Contract or full-time.

