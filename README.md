# Hi, I'm us-kg 👋

I keep a complete, self-hosted Surge setup — profile, modules and rule index, all wired to rule data that rebuilds itself every day.

## 📦 us-kg/surge

**[us-kg/surge](https://github.com/us-kg/surge)** — a ready-to-use Surge resource repository:

- **Profiles** — full annotated `surge.conf` + a lite variant for low-memory devices (just fill in your own nodes)
- **Rule index** — self-hosted rule sets (`china` / `ads` / `apple` / `douyin` / `ai` / `school`…) with one-line snippets
- **Modules** — ad blocking, YouTube in-app ad removal, NetEase Cloud Music unlock, dashboard widgets (IP info, streaming check, subscription traffic)
- **Scripts** — the panel widgets and response cleaners behind the modules

It's the consumer side of a small self-owned supply chain: rule data comes from [Jovanykoch/rules](https://github.com/Jovanykoch/rules), rebuilt daily by CI from upstream sources (v2fly, hagezi, Loyalsoldier…). Nothing here depends on anyone else's rule service — if an upstream changes, the daily build picks it up.

- ✅ Daily link-check of every remote asset URL
- 📝 Bilingual docs (EN / 中文), MIT licensed

## Quick start

Download [`profiles/surge.conf`](https://github.com/us-kg/surge/blob/main/profiles/surge.conf), fill in the `[Proxy]` section with your own nodes, and import it into Surge.
