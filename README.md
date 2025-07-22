# 🧅 Onion Architecture Sample - Image Processing Backend

This repository demonstrates a modular and maintainable backend system based on **Onion Architecture**, also known as **Clean Architecture**, for scalable .NET applications.

The architecture separates **domain logic**, **application services**, **infrastructure**, and **presentation layers** into clear boundaries. This promotes testability, flexibility, and long-term maintainability.

---

## 🧠 Core Principles

- **Domain-Centric Design**: Business logic resides at the core with zero dependencies on frameworks or databases.
- **Inversion of Control**: Outer layers depend on abstractions provided by inner layers.
- **Persistence Ignorance**: Infrastructure concerns (e.g., EF Core, file storage) are isolated from domain rules.
- **Independent Deployment**: Each layer can evolve independently.

🚀 Live Example

Looking for a real-world example of this kind of architecture in action?

Visit [ResizerPhoto.com](https://resizerphoto.com/en) — a live, production-grade image optimization and conversion service.

    📷 Resize, compress, crop, and convert images (JPG, PNG, WEBP) right in your browser — no upload required.
