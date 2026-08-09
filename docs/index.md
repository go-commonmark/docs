# go-commonmark

Pure-Go CommonMark.

go-commonmark is a pure-Go (CGO_ENABLED=0) CommonMark renderer: it parses CommonMark v0.31.2 into a node tree and renders an HTML fragment, with optional GFM extensions behind Options — no cgo binding to libcmark and no third-party dependencies. It passes all 652/652 spec examples byte-exact and compiles to js/wasm for offline Markdown preview.

Everything is **pure Go** (`CGO_ENABLED=0`), standard-library-first, and
cross-compiles to every 64-bit Go target. Licensed BSD-3-Clause.

## Packages

<div class="pk-grid" markdown>
<a class="pk-card" href="packages/commonmark.md"><code>commonmark</code><br><small>Strict CommonMark v0.31.2 Markdown-to-HTML renderer — 652/652 spec, byte-exact, GFM behind Options.</small></a>
</div>
