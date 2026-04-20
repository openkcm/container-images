# 📦 container-images

A collection of custom Dockerfiles for building lightweight, secure, and production-ready container images.
This repository is intended to serve as a base for various containerized environments tailored to specific tools or use cases.

## 🗂️ Available Images

| Image Tag | Base Image     | Tools Included         | Purpose                                  |
|-----------|----------------|------------------------|------------------------------------------|
| `bash-jq` | `alpine:3.22`  | `bash`, `curl`, `jq`   | Lightweight image for running bash scripts with JSON and HTTP capabilities |

> 🔐 All images are built with minimal layers and hardened by removing unnecessary tools like `apk`.
