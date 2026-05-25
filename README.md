# nanocode

Minimal Claude Code alternative. Single Python file, zero dependencies, ~250 lines.

Built using Claude Code, then used to build itself.

![screenshot](screenshot.png)

## Features

- Full agentic loop with tool use
- Tools: `read`, `write`, `edit`, `glob`, `grep`, `bash`
- Conversation history
- Colored terminal output

## Usage

```bash
export ANTHROPIC_API_KEY="your-key"
python nanocode.py
```

## Commands

- `/c` - Clear conversation
- `/q` or `exit` - Quit

## Tools

| Tool | Description |
|------|-------------|
| `read` | Read file with line numbers, offset/limit |
| `write` | Write content to file |
| `edit` | Replace string in file (must be unique) |
| `glob` | Find files by pattern, sorted by mtime |
| `grep` | Search files for regex |
| `bash` | Run shell command |

## Example

```
────────────────────────────────────────
❯ what files are here?
────────────────────────────────────────

⏺ Glob(**/*.py)
  ⎿  nanocode.py

⏺ There's one Python file: nanocode.py
```

## License

MIT
---

## 🤝 Contributing

Contributions are welcome! We encourage the community to help improve this project.

1. **Fork** the repository
2. Create a **feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. Open a **Pull Request**

Please make sure to update tests as appropriate and follow the existing code style.

---

## 📬 Contact

**Mulky Malikul Dhaher** — [mulkymalikuldhaher@email.com](mailto:mulkymalikuldhaher@email.com)

GitHub: [https://github.com/mulkymalikuldhrs](https://github.com/mulkymalikuldhrs)

---

## ⚠️ Disclaimer

**This project is for Education Purpose only.**

All content, code, and documentation provided in this repository are intended solely for educational and research purposes. Nothing in this repository constitutes financial, investment, legal, or professional advice.

**Risiko apapun tidak kita tanggung.** (We are not responsible for any risks or damages.)

Use at your own risk. The authors and contributors assume no liability for any losses, damages, or consequences arising from the use of this software or information provided herein.

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

Copyright © Mulky Malikul Dhaher. All rights reserved.


---

## Disclaimer

**For Education Purpose Only.** This project is for educational and research purposes only. The author assumes no responsibility for any losses, damages, or consequences arising from the use of this software.

**Hanya untuk Tujuan Pendidikan.** Proyek ini hanya untuk tujuan pendidikan dan penelitian. Risiko apapun tidak kita tanggung.

**仅用于教育目的。** 本项目仅供教育和研究目的。作者对因使用本软件而造成的任何损失不承担责任。

---

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## Contact

**Mulky Malikul Dhaher** — [mulkymalikuldhaher@email.com](mailto:mulkymalikuldhaher@email.com)
