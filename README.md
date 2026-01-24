# PythonRuntime

### Python Standalone Builds
This project produces standalone, redistributable builds of Python.

---

## Python Standalone Builds Matrix

| OS | OS Version | Architecture | 3.15 | 3.14 | 3.13 | 3.12 | 3.11 | 3.10 | 3.9 | 3.8 | 3.7 |
|---|---|---|---|---|---|---|---|---|---|---|---|
| macOS | macos26<br>(Tahoe) | arm64 | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ⏳<br>≤ 3.9.1 | ⏳<br>≤ 3.8.10 | ❌ |
| macOS | macos15<br>(Sequoia) | arm64 | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ⏳<br>≤ 3.9.1 | ⏳<br>≤ 3.8.10 | ❌ |
| macOS | macos14<br>(Sonoma) | arm64 | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ⏳<br>≤ 3.9.1 | ⏳<br>≤ 3.8.10 | ❌ |
| AL2023 | AL2023 | x86-64 | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⏳<br>≤ 3.7.6 |
| AL2023 | AL2023 | aarch64 | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ |
| AL2 | AL2 | x86-64 | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⏳<br>≤ 3.7.1 |

---

### Notes
- **✅** = full availability for that minor release (all patch versions)
- **⏳** = partial availability
- **❌** = not supported
- **(≤ x.y.z)** = available up to and including that patch release
