# Burp Suite HTTP Traffic Analysis

## Objective

To use Burp Suite to intercept and analyze HTTP traffic in a controlled local environment.

## Target

http://127.0.0.1:8000

## Tools Used

- Burp Suite
- Python HTTP Server
- curl

## Setup

A local Python HTTP server was started using:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
