# signature-one-archive-shard-43

Frozen storage shard of the Signature Spec Catalog (main repo:
justinahiggins614-cmyk/signature-one-archive).

- Range: JAH-SPEC-784051 – JAH-SPEC-800550 (16,500 draft specifications)
- Chunks: data/volumes/specs-c05228.jsonl.gz … specs-c05337.jsonl.gz (150 specs each)
- Index: data/index/specs.idx.json.gz (one compact row per spec)
- Sitemap: sitemap-specs.xml (written by the main repo's code/build_sitemaps.py)

Frozen: chunks are never modified or deleted. New specs always land in the
main repo.
