# Jihwan Oh

Junior full-stack developer who builds AI automation. I build it so that a
failure is reported, a repeat does nothing twice, and a wrong target is refused.

## Work

**[Minecraft Server Companion](https://github.com/Artemis3753/minecraft-companion-Jihwan)**

A React + Express dashboard for a live Minecraft server. RCON reports every
failure as a success reply, so the API translates replies into 404 and 409,
and destructive actions need a token and a second confirmation.
[Demo video](https://youtu.be/STs8S6lfzRQ)

**[Trend Portal](https://github.com/Artemis3753/trendportal-newsletter#automation-with-claude-code)**

A live site and newsletter for a client's trend magazine ([trendportal.kr](https://trendportal.kr)).
Transis (트란시스) is the assistant behind it, three Claude Code routines for
the schedule, a trend feed and card-news drafts. Reminders go out through a
send-only account whose script refuses any address off an allowlist, and a
repeat send is refused as a duplicate.

**[FarmDelve](https://github.com/Artemis3753/farmdelve)**

A single-player farming and gear-upgrade game on Node, Express and PostgreSQL.
Every write runs in one transaction with row locks taken in one fixed order, to
avoid double-spends and deadlocks. In development.

## Next

Automated tests for FarmDelve, starting with concurrent upgrade requests.

[LinkedIn](https://www.linkedin.com/in/jihwan-oh-dev/) · yd30421@gmail.com
