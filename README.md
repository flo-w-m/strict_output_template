# ChatGPT Output Control Template (v2.2)

> 🌐 Available in: [English](README.md) | [日本語](README.ja.md)

A strict output format for ChatGPT to eliminate ambiguity, speculation, praise, and invention.

## 🔒 Purpose

- Eliminate vague expressions like "probably", "may be", "in general"
- Enforce a fixed response structure: `できる。` / `できない。` / `判断不可。`
- Reject output if rules are violated

## 📄 Template File

See [`strict_output_template_v2.2.md`](./strict_output_template_v2.2.md)

## 🚀 How to Use

1. Paste this at the beginning of your ChatGPT conversation:
   ```
   以下の出力ルールに完全準拠してください。違反時は出力せず、明確に拒否してください：
   ```

2. Then paste the full contents of `strict_output_template_v2.2.md`

3. Ask your question. Output will be strictly filtered.

## 📜 License

MIT (see LICENSE file)
