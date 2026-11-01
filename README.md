<p align="center">
  <img src="assets/banner.svg" alt="0xM44k — Penetration Tester and Security Tooling Engineer" width="100%">
</p>

<p align="center">
  <a href="mailto:m11k.08k3@gmail.com"><img src="https://img.shields.io/badge/email-contact-00f3ff?style=flat-square&labelColor=0e1620" alt="Email"></a>
  <img src="https://img.shields.io/badge/focus-security%20tooling-00ff88?style=flat-square&labelColor=0e1620" alt="Focus">
  <img src="https://img.shields.io/badge/python-3.9%E2%80%933.13-3776AB?style=flat-square&labelColor=0e1620&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square&labelColor=0e1620" alt="License">
</p>

---

### `whoami`

I build **small, auditable command-line tools for security review** — MCP configs, lockfiles, cryptography, firewall rules, incident drills and AI-agent memory forensics. Each tool does a single job and documents what it **cannot** do. I'd rather ship a tool that is honest about its blind spots than one that overstates what it catches.

Everything here is a **personal project**, verifiable from the public code. There are no certifications or employers listed because none have been added yet; the code is the proof.

---

### `ls ~/tools`   —   7 tools

| Tool | What it does |
|------|--------------|
| **[mcp-lantern](https://github.com/0xM44k/mcp-lantern)** | Flags which combinations of your MCP servers can leak data or run injected commands (the "lethal trifecta") |
| **[ramnesia](https://github.com/0xM44k/ramnesia)** | Carves AI-agent traces — prompts, tool calls, secrets, model identity — out of a memory dump |
| **[ruleglass](https://github.com/0xM44k/ruleglass)** | Analyses `iptables` rulesets and traces a packet through them, saying `UNCERTAIN` when it can't be sure |
| **[scopekeeper](https://github.com/0xM44k/scopekeeper)** | A scope guard + tamper-evident hash-chained log for authorised security testing |
| **[lockdiff](https://github.com/0xM44k/lockdiff)** | Diffs two `package-lock.json` files for tamper signals, offline — not advisories |
| **[cryptoscan](https://github.com/0xM44k/cryptoscan)** | Inventories a codebase's cryptography and ranks what to migrate first for post-quantum |
| **[tabletop](https://github.com/0xM44k/tabletop)** | Generates a realistic incident-response tabletop exercise from your own environment |

Every one is offline-first, dependency-light, and emits machine-readable output (JSON / SARIF / CBOM) so it can gate a pipeline.

---

### `cat skills.txt`

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white&labelColor=0e1620)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white&labelColor=0e1620)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black&labelColor=0e1620)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white&labelColor=0e1620)
![iptables](https://img.shields.io/badge/-netfilter%2Fiptables-EE0000?style=flat-square&labelColor=0e1620)
![MCP](https://img.shields.io/badge/-MCP-00f3ff?style=flat-square&labelColor=0e1620)
![SARIF](https://img.shields.io/badge/-SARIF-6E40C9?style=flat-square&labelColor=0e1620)
![Volatility](https://img.shields.io/badge/-Volatility%203-1f6feb?style=flat-square&labelColor=0e1620)

**Interests:** networking · Linux & operating systems · cryptography · security research · agents & MCP · memory forensics.

---

### `./approach --how`

- **Build to spec.** The smallest tool that answers one question beats a framework that answers none well.
- **Work against reality.** ruleglass is built around the real Linux kernel's behaviour; scopekeeper's log is tamper-evident by construction; ramnesia reads real memory layouts.
- **State the limits.** Every tool ships a "what it does *not* catch" list. That list is the senior part.

---

<p align="center">
  <sub><code>m11k.08k3@gmail.com</code> · built from scratch · no analytics, no trackers</sub>
</p>
