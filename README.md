# Content Hive Plugin: Threads

A Threads content parsing plugin for Content Hive. Parses post URLs to extract text, images, videos, and author information via mobile page scraping. Supports optional cookie authentication for accessing restricted content.

Plugin for [Content Hive](https://github.com/content-hive/content-hive).

## Layout

```
plugin/              # plugin source, installed as plugins/threads/ by Content Hive
├── manifest.json    # plugin metadata (domain, version, requirements, release_notes)
├── __init__.py
└── ...
contenthive.json     # repository metadata for the Content Hive plugin catalog
```

## Disclaimer

> This plugin fetches content via Threads mobile page scraping. Cookie authentication may carry the risk of account suspension. Please ensure compliance with Threads' Terms of Service and applicable local laws before use. Platform policy changes may cause the plugin to stop working.
