# UUID and ULID Generator

> Random v4 UUIDs and lexicographically sortable ULIDs, generated in your browser.

**Live demo:** https://0xelitesystem.github.io/uuid-and-ulid-generator/

Single HTML file. Runs in the browser with no build step, no server, no tracking, and no data leaving the page.

## What it does

- Generates UUID v4 using the crypto API, with the correct version and variant bits
- Generates ULIDs as a millisecond timestamp plus randomness in Crockford base32, so they sort by time
- Bulk generates up to 100 at once
- Copies a single value or the whole list

## What it is not

- Not a namespace UUID tool. It does not do v3 or v5 name-based identifiers
- Not a registry. Nothing is stored or checked for prior use

## Use it

Open the hosted page: https://0xelitesystem.github.io/uuid-and-ulid-generator/

Or download `index.html` and open it in any browser. It works offline.

## Privacy

Everything runs client-side. No analytics, no cookies, no network calls, no local storage.

## Related

- [unix-timestamp-converter](https://github.com/0xelitesystem/unix-timestamp-converter)
- [slug-generator](https://github.com/0xelitesystem/slug-generator)
- [case-converter](https://github.com/0xelitesystem/case-converter)

## More

Part of a catalog of single-file browser tools and plain-language references, all MIT licensed and dependency-free: [0xelitesystem.github.io](https://0xelitesystem.github.io/). Built by [elitesystem.ai](https://elitesystem.ai).

## License

MIT, copyright 0xelitesystem 2026.
