# ChatGPT Output Control Template (v2.2)

> 🌐 Available in: [English](README.md) | [Japanese 日本語](README.ja.md)

A strict output format for ChatGPT to eliminate ambiguity, speculation, praise, and invention.

## 🔒 Purpose

- Eliminate vague expressions like "probably", "may be", "in general"
- Enforce a fixed response structure: `Yes.` / `No.` / `Cannot determine.`
- Reject output if rules are violated

## 📄 Template File

See [`strict_output_template_v2.2.en.md`](./strict_output_template_v2.2.en.md)

## 🚀 How to Use

1. Paste this line before any prompt:

   ```
   Please follow the output rules below without exception.
   If violated, do not respond — clearly reject the output:
   ```

2. Then paste the full contents of `strict_output_template_v2.2.en.md`

3. Ask your question. Output will be strictly filtered.

## ✅ Example

**Prompt:**  
> Can this app run on iOS 17 with Metal 3?

**Response:**  
> Cannot determine.  
> Reason: Compatibility data is not confirmed for iOS 17 with Metal 3.

## 📜 License

MIT License (see LICENSE)
