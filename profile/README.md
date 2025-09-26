<img align="left" width="250"  src="https://kivigo.github.io/img/logo-kivigo.png" alt="KiviGo Logo" />

# KiviGo · Unified Key-Value Store for Go

Welcome to the **KiviGo** GitHub organization!  
KiviGo provides a modular, production-ready key-value store library for Go, designed for flexibility, testability, and ease of use across a wide range of storage backends.

---

## 🚀 What is KiviGo?

KiviGo is a lightweight, extensible key-value store library for Go that offers:

- **Unified API** for all supported backends (Redis, BoltDB, Consul, etcd, Badger, DynamoDB, and more)
- **Pluggable encoders** (JSON, YAML, etc.)
- **Health checks**, batch operations, and mock/test support
- **Modular architecture**: each backend is a standalone Go module with its own dependencies, tests, and documentation

KiviGo helps you focus on your application logic, not backend-specific details.

---

## 📚 Documentation

- **Main documentation:** [https://kivigo.github.io/](https://kivigo.github.io/)
- **API reference:** [pkg.go.dev/github.com/kivigo/kivigo](https://pkg.go.dev/github.com/kivigo/kivigo)
- **Backends overview:** [Backends list & docs](https://kivigo.github.io/docs/backends/overview)

---

## 🏗️ Main Repositories

- [**kivigo/kivigo**](https://github.com/kivigo/kivigo) — Core library, unified API, and documentation
- [**kivigo/backends**](https://github.com/kivigo/backends) — Modular backend implementations (Redis, Badger, Consul, etcd, DynamoDB, etc.)
- [**kivigo/encoders**](https://github.com/kivigo/encoders) — Pluggable encoders (JSON, YAML, etc.)

---

## ✨ Features

- Unified interface for all supported backends
- Pluggable encoding/decoding
- Health check and batch operation support
- Easy to add new backends or encoders
- Mock backend for testing
- Comprehensive documentation and examples

---

## 🥝 Why "KiviGo"?

"KiviGo" is a play on "key-value" and "Go" (the language), and also evokes the fruit "kiwi" 🥝 — simple, fresh, and full of possibilities!

---

**License:** MIT  
