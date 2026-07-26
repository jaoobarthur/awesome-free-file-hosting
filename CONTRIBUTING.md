# Contributing to Awesome Free File Hosting

Thank you for considering contributing to **Awesome Free File Hosting**!

Please take a moment to review these guidelines before opening an Issue or Pull Request.

---

## 📋 General Guidelines

1. **Check Existing Entries & Issues**: Search the list and [open issues](../../issues) to avoid duplicate submissions.
2. **Quality & Viability**: The service must offer a **genuinely useful free tier**. We do not accept hosts with unusable free caps (e.g., < 10 MB per file, extreme paywalls, or deceptive links).
3. **Disclose Affiliations**: If you are the owner, developer, or marketer of a service you are submitting, please disclose your connection in the PR description.
4. **No Broken / Spam Sites**: Ensure the website is online, operational, and adheres to basic security and privacy standards.

---

## 📐 Table Formatting Rules

To keep the repository uniform and easy to read, **all submissions must fit into the standard 6-column matrix**.

Do **NOT** introduce new tables, custom headers, or bespoke sections without discussing them in an Issue first.

### Table Schema

Every row must follow this exact order:

| Column | Description / Options | Example |
| :--- | :--- | :--- |
| **Site** | Markdown link to the file host | `[Catbox](https://catbox.moe)` |
| **Bandwidth** | Download speed or quota limits | `Unlimited` or `6 GB/day` |
| **Max Upload Size** | Maximum file size allowed per upload | `200 MB per file` or `Unlimited` |
| **File Expiry** | Retention period or inactivity deletion rule | `Permanent` or `30 days (inactive links)` |
| **Login Info** | Account requirements & login method | `Not required` or `Required, via email & password` |
| **Allowed File Types** | Supported file formats / extensions | `All file types` or `Most types, except .exe` |

### Markdown Row Code Template

```markdown
| [Host Name](https://example.com) | Bandwidth Limit | Max Upload Size | Expiry Rules | Login Requirement | Supported File Types |
```

---

## 🤖 AI Contribution Policy

We welcome the responsible use of AI tools (such as ChatGPT, Claude, or GitHub Copilot) to assist in drafting submissions, fixing grammar, or formatting Markdown tables.

However, to protect maintainers from low-quality spam, the following rules strictly apply:

1. **Human Verification Required**: Every link, free-tier limit, and file size cap must be **manually tested and verified by a human** before opening a Pull Request. Do not submit hallucinated or unverified file-hosting platforms.
2. **No Unreviewed AI Slop / Spam**: Pull Requests generated entirely by autonomous bots or submitted without human review will be closed immediately.
3. **Engage Directly**: If maintainers ask questions about your submission, please respond in your own words rather than pasting raw automated AI responses.

---

## 🛠️ How to Submit Changes

1. **Fork** the repository.
2. Create a new branch for your feature (`git checkout -b add-my-file-host`).
3. Add your entry to `README.md` following the [Table Formatting Rules](#-table-formatting-rules).
4. Keep the table neat and aligned.
5. Commit your changes with a clear commit message (`git commit -m "Add HostName to free file hosting list"`).
6. Push to your branch and **Open a Pull Request**.

---

## ❓ Proposing Architectural Changes

If you want to suggest new sections, categories, or column modifications, please **[open an Issue](../../issues/new)** first to discuss it with the maintainer before opening a Pull Request.
