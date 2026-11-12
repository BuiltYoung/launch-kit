# Built Young Skills

Open-source [Claude Skills](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview) for young builders.

Built Young teaches teenagers aged 10–18 to find a problem worth solving and ship a real product. These are the tools we use with our own students, released free for anyone to use.

---

## Skills

### `launch-kit`

Turns a working product into a ready-to-run launch on Product Hunt, on Kickstarter, or in your school and local community. You get every page field written to the platform's limits, the people to line up, and a plan for the day.

Most launch guides assume the founder is an adult with a free afternoon. This one checks who is allowed to hold the account before it writes a word, and plans launch day around the school timetable.

**How it works**

1. **Ask first.** The product, what state it's in, the founders' age brackets, the adult involved, the date, and who already knows about it.
2. **Pick the platform.**

| Situation | Launch here |
|---|---|
| Software people can use today through a link | Product Hunt, plus a school or community launch |
| A physical product that needs money for a first batch, with a working prototype | Kickstarter, run by an adult creator |
| A mostly local audience, or founders under 16 with no adult ready to hold an account | School and community launch |
| Not usable yet | Don't launch. Open a waitlist |

3. **Eligibility gate.** Product Hunt and Kickstarter both have age rules. The kit states the result at the top: who holds the account, and what a parent or guardian needs to agree to.
4. **Build the kit.**
   - **Product Hunt:** name, tagline, description, tags, gallery plan and maker comment, each with its character count, plus the launch time converted to your time zone.
   - **Kickstarter:** the delivery check comes first. It works out unit cost, shipping, fees and a buffer, and sets the funding goal from those. Then the story, reward tiers, video outline, and risks.
   - **School and community:** an announcement script, a poster with a QR code, a five-minute demo plan, and a message a parent can send.
5. **Supporters and launch day.** A first-ten-supporters table, two outreach messages, and a schedule built around before school, lunch and after school.
6. **After the launch.** A short recap with real numbers. It doubles as the traction slide for a pitch competition.

**What it won't do**

- Ask anyone for upvotes. Product Hunt treats that as spam.
- Promise a ranking or a funded campaign.
- Invent users, quotes or numbers. Gaps are marked `[NEEDS: ...]`.
- Write Kickstarter copy before the cost numbers exist.

Platform rules in the skill were checked against the official pages in November 2026. The skill re-reads them when it has web access, because platforms change them.

Launch posts hand off to [build-in-public](https://github.com/BuiltYoung/build-in-public), and posters to [ig-poster-studio](https://github.com/BuiltYoung/ig-poster-studio).

---

## Installing

**Claude Code**

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/BuiltYoung/launch-kit.git ~/.claude/skills/launch-kit
```

Restart Claude Code. The skill loads automatically when you ask how to launch a product.

**Claude.ai**

Settings → Capabilities → Skills → Upload, then select the `launch-kit` folder.

---

## Using it

Describe your product and ask. No command needed:

> *"Our team built a web app that helps school clubs track members. It's live, two of us are 16 and one is 15, and a parent is helping. We want to launch on Product Hunt in three weeks."*

---

## Contributing

Issues and pull requests welcome. If you used this with students and something didn't land, we especially want to hear about it.

## Licence

MIT. See [LICENSE](LICENSE). Use it, fork it, teach with it.

---

**[Built Young](https://builtyoung.org)** · Build before everyone else.
