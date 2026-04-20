# UUID-Hex
High-performance library for formatting UUIDs into hexadecimal strings.

## ✅ Features
- **Efficiently** converts UUIDs to hex format
- Optimized for speed by relying on a precomputated hexadecimal range (`0000-FFFF`), increasing static data usage

## 📖 Usage
Call the `uuid:_` function as an entity and use its output in `storage uuid:out plain`\
Alternatively, assign a 4-integer array to `storage uuid:in UUID`, then call the `uuid:convert` function to format it.
