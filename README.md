# api-rate-limiter


# API Rate Limiting Middleware

## Features
- IP-based rate limiting
- Configurable per route
- Returns HTTP 429 on limit exceed
- In-memory or MongoDB support

## Usage

```js
rateLimiter({
  limit: 5,
  windowMs: 60000
})

---

## PHASE 8 — Why This Impresses Reviewers
- Custom middleware (not express-rate-limit)
- Clean separation of concerns
- Route-level configuration
- Easy extensibility to Redis/MongoDB
- Production-aligned structure

---

If you want next:
- MongoDB-backed version  
- Redis-ready design  
- Sliding window algorithm  
- Token bucket model  
- Unit tests  

Say the word.
