## 📦 How to Install Split Files Using 7-Zip

If you've downloaded files that are split into parts (e.g., `file.7z.001`, `file.7z.002`, etc.), follow the steps below to extract them properly.

### 🔧 Requirements

- [✅ Download and install 7-Zip](https://www.7-zip.org/download.html)

---

### 📁 Example Split Files

```text
my-archive.7z.001
my-archive.7z.002
my-archive.7z.003
```

> Make sure all parts are in the **same folder**.

---

### 🧩 How to Extract

1. **Install [7-Zip](https://www.7-zip.org/download.html)** if not already installed.
2. **Right-click** on the first part (`my-archive.7z.001`).
3. Select `7-Zip` → `Extract Here` or `Extract to "my-archive/"`.
4. 7-Zip will automatically combine all parts and extract the contents.

---

### ❗ Notes

- You only need to extract **.7z.001**. 7-Zip will detect and use the rest automatically.
- All parts must be **present and named correctly** for extraction to succeed.
