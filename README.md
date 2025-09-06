# Rate limiter in NodeJS using Redis

## Overview
Implemented a high-throughput rate limiter middleware in Node.js using Redis and the Fixed Window algorithm to control API access and enhance system stability. Designed to handle over 500 requests per second (RPS), it effectively reduces malicious traffic and ensures fair usage. Dependencies include Express, Nodemon, ioredis, and Moment. Stress testing with 10,000+ simulated requests demonstrated the middleware’s reliability, significantly improving performance and uptime across applications.
