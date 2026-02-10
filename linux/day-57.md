# Day 57
## Focus
CDN (Content Delivery Network) Basics

## What is a CDN?
A CDN is a distributed network of servers that delivers content to users from the nearest location.

It improves performance and reduces load on the origin server.

## Why CDN is Used
- Faster content delivery
- Reduced latency
- Reduced bandwidth usage on origin server
- Better availability and reliability
- Protection against DDoS attacks

## How CDN Works
1. User requests content (image/video/web page)
2. CDN checks cache at nearest edge server
3. If cached → served immediately
4. If not cached → fetched from origin server and cached

## Common CDN Cached Content
- images
- CSS and JS files
- video streams
- static web pages

## Observations
- CDN improves speed globally
- Cache invalidation is important
- CDNs reduce server load significantly
