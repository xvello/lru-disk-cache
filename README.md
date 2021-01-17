# ⚠️️ Please read below before using this crate ⚠️️

# A LRU cache for files on disk &nbsp; &nbsp; [![CI status](https://github.com/xvello/lru-disk-cache/workflows/ci/badge.svg?branch=master)](https://github.com/xvello/lru-disk-cache/actions) [![dependency status](https://deps.rs/repo/github/xvello/lru-disk-cache/status.svg)](https://deps.rs/repo/github/xvello/lru-disk-cache)

This repository is a fork of the lru-disk-cache crate that used to be exported by [the sccache project](https://github.com/mozilla/sccache), but got yanked from crates.io due to [valid concerns about data-loss risks](https://github.com/mozilla/sccache/issues/916).

The API and documentation of this crate would need an overhaul to address these risks before releasing it again. Progress on this in tracked in [issue #1](https://github.com/xvello/lru-disk-cache/issues/1)
