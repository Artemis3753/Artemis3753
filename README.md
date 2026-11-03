# Jihwan Oh

Junior full-stack developer who automates real workflows with Claude Code, shipping a live site and editor tooling for a 70K-follower magazine.

## Work

**[Minecraft Server Companion](https://github.com/Artemis3753/minecraft-companion-Jihwan)**

A React + Express dashboard for a live Minecraft server. RCON reports every
failure as a success reply, so the API translates replies into 404 and 409,
and destructive actions need a token and a second confirmation.
[Demo video](https://youtu.be/STs8S6lfzRQ)

**[Trend Portal](https://github.com/Artemis3753/trendportal-newsletter#automation-with-claude-code)**

A live site and newsletter for a client's trend magazine ([trendportal.kr](https://trendportal.kr)).
Transis (트란시스) is the assistant behind it, with three jobs: a daily schedule,
a trend feed and card-news drafts, each run by a Claude Code routine. Reminders
go out through a send-only account whose script refuses any address off an
allowlist, and a repeat send is refused as a duplicate.
[How it is built](https://github.com/Artemis3753/trendportal-newsletter/blob/main/docs/TRANSIS.md)

<a href="https://github.com/Artemis3753/trendportal-newsletter/blob/main/docs/TRANSIS.md">
  <img src="https://raw.githubusercontent.com/Artemis3753/trendportal-newsletter/main/docs/img/transis-schedule-email.png" width="420" alt="The Transis morning reminder email, built from sample appointments. UI text translated from Korean.">
</a>

<sub>The morning reminder email, from sample data. The shipped email is in Korean.</sub>

**[FarmDelve](https://github.com/Artemis3753/farmdelve)**

A single-player farming and gear-upgrade game on Node, Express and PostgreSQL.
Every write runs in one transaction with row locks taken in one fixed order, to
avoid double-spends and deadlocks. In development.

## How I work with Claude Code

- **Project rules:** [CLAUDE.md in Minecraft Server Companion](https://github.com/Artemis3753/minecraft-companion-Jihwan#how-i-work-with-claude-code): no credentials in the repo, destructive actions confirmed, no whole features unprompted.
- **Routine instructions and their limits:** [transis/PROMPT.md](https://github.com/Artemis3753/trendportal-newsletter/blob/main/transis/PROMPT.md) and [docs/TRANSIS.md](https://github.com/Artemis3753/trendportal-newsletter/blob/main/docs/TRANSIS.md), which list what code enforces and what rests only on the instructions.
- No hooks or custom commands.

## Learning

Automated testing with Vitest.

[LinkedIn](https://www.linkedin.com/in/jihwan-oh-dev/) · yd30421@gmail.com
