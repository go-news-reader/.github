<p align="center"><img src="https://raw.githubusercontent.com/go-news-reader/brand/main/social/go-news-reader.png" alt="go-news-reader" width="640"></p>

<h1 align="center">go-news-reader</h1>
<p align="center">Pure-Go multi-source news & social aggregator — one unified feed.</p>
<p align="center">
  <a href="https://go-news-reader.github.io/docs/"><img src="https://img.shields.io/badge/docs-mkdocs--material-0A6E96?style=flat-square&logo=materialformkdocs&logoColor=white" alt="docs"></a>
  <img src="https://img.shields.io/badge/packages-1-0079A8?style=flat-square" alt="packages">
  <img src="https://img.shields.io/badge/Go-1.26.4-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/CGO-0-22CCE2?style=flat-square" alt="CGO">
  <img src="https://img.shields.io/badge/license-BSD--3--Clause-0A6E96?style=flat-square" alt="license">
</p>

---

## What is this?

go-news-reader is a pure-Go (CGO=0) multi-source news & social aggregator with a go-widgets UI: one app, one unified feed, many sources — each behind the same small `source.Provider` contract. Each platform has a standalone pure-Go client library in its own org (go-reddit, go-syndication, go-hackernews, go-newsgroups, go-mastodon, go-lemmy, go-atproto/Bluesky, …); this org's `reader` adds a thin provider adapter per source that maps onto a normalized `source.Item`.

Everything is **pure Go** (`CGO_ENABLED=0`), standard-library-first, and
cross-compiles to every 64-bit Go target.

## Packages (1)

| Package | What it does | API |
|---|---|---|
| [`reader`](https://github.com/go-news-reader/reader) | Pure-Go multi-source news/social aggregator (Reddit, RSS, HN, Usenet, Mastodon, Lemmy, Bluesky, Twitter, Instagram, TikTok) with a go-widgets UI. CGO=0. | [reference](https://pkg.go.dev/github.com/go-news-reader/reader) |

> This list is generated from the repos that actually exist in the org.

## Links

- Docs — <https://go-news-reader.github.io/docs/>
- Site — <https://go-news-reader.github.io/>
- Brand assets — <https://github.com/go-news-reader/brand>

---
<p align="center"><sub>Branding in <a href="https://github.com/go-news-reader/brand">go-news-reader/brand</a>. Licensed BSD-3-Clause.</sub></p>
