# ZWSteg — Zero-Width Steganography Tool

A Chrome extension for detecting and manipulating zero-width steganographic characters hidden in plain text.

Zero-width Unicode characters like U+200B and U+200C are invisible to the human eye but fully present in text data. They can carry hidden payloads in READMEs, emails, documents, and web pages, including prompt injections targeting LLMs and AI agents.

## Features

- **Encode** — Embed a hidden message into any cover text using invisible zero-width characters. Includes preset templates for common prompt injection patterns.
- **Decode** — Paste suspicious text to extract hidden steganographic messages.
- **Scan** — Detect all 11 known zero-width Unicode character types in any text.
- **Strip** — Remove all zero-width characters from text before sharing or feeding it to an AI system.

## Install

[Chrome Web Store](#) (link coming soon)

## Use Cases

- LLM prompt injection detection
- Content integrity verification for open-source maintainers
- Security research and red teaming
- Digital watermarking and leak tracing

## Privacy

ZWSteg collects no data. All processing happens locally in your browser. See [PRIVACY.md](PRIVACY.md) for details.

## Support

Found a bug or have a feature request? [Open an issue](../../issues).

If you find this tool useful, you can support the project at [buymeacoffee.com/tripvento](https://buymeacoffee.com/tripvento).

## License

All rights reserved. Source code is not included in this repository.

## Built by

[Tripvento](https://tripvento.com) — Geospatial intelligence for hotel ranking.
