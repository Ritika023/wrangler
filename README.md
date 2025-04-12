## 🚀 New Feature: Byte Size & Time Duration Parsers

Wrangler now includes built-in support for parsing **Byte Sizes** and **Time Durations**, making your data transformation recipes more powerful and easier to write.

---

### ✅ Supported Units

#### 📦 Byte Sizes *(case-insensitive)*

| Unit     | Meaning      |
|----------|--------------|
| B        | Bytes        |
| KB / K   | Kilobytes    |
| MB / M   | Megabytes    |
| GB / G   | Gigabytes    |
| TB / T   | Terabytes    |

**Examples:**  
`512B`, `1KB`, `1.5MB`, `2G`, `3.75tb`

#### ⏱️ Time Durations

| Unit | Meaning       |
|------|---------------|
| ms   | Milliseconds  |
| s    | Seconds       |
| m    | Minutes       |
| h    | Hours         |
| d    | Days          |

**Examples:**  
`100ms`, `2s`, `1.5m`, `3h`, `1d`

---

### 🧠 How It Works

You can now use byte size and time duration values **directly inside Wrangler recipes**.

These values are parsed as **native token types**, meaning:
- No more manual unit conversions
- Easily aggregate, compute, and transform data

---

## 📊 New Directive: `aggregate-stats`

This directive lets you **aggregate byte sizes and time durations** across multiple rows.

### 🔧 Syntax

