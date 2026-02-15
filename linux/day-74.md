# Day 74
## Focus
HTTP Caching Basics (Browser and Server Cache)

## What is Caching?
Caching means storing responses so future requests can be served faster.

It reduces:
- server load
- bandwidth usage
- page load time

---

## Browser Cache
Browsers store:
- images
- CSS files
- JS files
- API responses (sometimes)

So the next time you open the website, it loads faster.

---

## Cache-Control Header
Controls caching behavior.

Examples:
Means cache for 1 hour.Means revalidate with server before using cache.Means do not store at all.

---

## ETag Header
ETag is a version identifier for cached content.

Flow:
- Client requests resource
- Server sends ETag
- Client stores ETag
- Next request includes:

- If unchanged server replies:

---

## Expires Header
Old caching method:

---

## Observations
- caching improves performance massively
- `304 Not Modified` is common in caching
- cache-control is modern standard
- CDN heavily relies on caching

