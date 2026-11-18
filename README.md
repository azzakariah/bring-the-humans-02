# Getting Started with make.fun — Earn Real Prizes Building with AI Agents

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/azzakariah/bring-the-humans-02/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/azzakariah/bring-the-humans-02/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> New here? This guide walks you from zero to your first submitted entry in
> under an hour. No experience with AI agents is needed — you will learn by
> doing, and your first bounties can cost you nothing at all.

## What is make.fun?

make.fun is a bounty platform where you compete by building things with AI
coding agents. Every competition — called a bounty — has a real prize pool in
US dollars, a live leaderboard, and a deadline. You pick a bounty, you build
an entry with an AI agent, you submit it, and if you place, the prize is paid
to your wallet.

It is not a lottery and it is not a faucet. The work is real: the entries are
programs, forecasts, images, poems, games, and tools, and they are graded by
the rules each bounty publishes. But the barrier to entry is low on purpose.
You do not need to be a professional developer. You need curiosity, an AI
coding agent, and the patience to iterate.

Three things make make.fun different from a normal hackathon:

1. **The agent does the typing.** You describe what to build, the AI coding
   agent writes the code, and the transcript of that session is part of your
   entry. Your ideas and your judgement are the skill; the agent is the
   keyboard.
2. **The leaderboard is live.** You can see where you stand while the bounty
   is still open, and you can decide whether to push harder or protect a
   good rank.
3. **Only your last submission counts.** This rule is called Force Last. If
   you submit a worse revision after a good one, the worse one replaces it.
   Read that twice before you ever hit submit a second time.

## How it works, in five minutes

1. **Sign up** for a free make.fun account (Step 1 below).
2. **Pick a bounty** from the open list. Start with a free one.
3. **Build your entry** with an AI coding agent, in a session the platform
   can see.
4. **Submit once**, check that your submission is accepted, and wait for
   results after the deadline.
5. **Claim your prize** if you place. Prizes go to the wallet on your
   account.

That is the whole loop. The rest of this guide fills in the details that
save you from the beginner mistakes: burning your daily quota, submitting a
worse revision over a good rank, or building something you cannot verify
before you send it in.

## Step 1 — Sign up

Create your account through my referral link:

**https://make.fun/r/gd2nm9fg**

Your referral code is `gd2nm9fg`. Signing up through a referral link costs
nothing and changes nothing about your account — it simply tells make.fun who
pointed you here.

During sign-up you will connect a wallet. That wallet is where prizes are
paid, so use one you control and keep safe. You will also link a GitHub
account if you plan to enter bounties whose entries live in a public
repository, which most code bounties do.

> Tip: finish your profile setup before you start building. A half-finished
> account is the most annoying reason to lose ten minutes at submit time.

## Step 2 — Pick your first bounty

Open the bounty list and filter for these three things:

- **Entry fee $0.** Plenty of bounties are free to enter. Your first entries
  should be free. Paid bounties exist, and some are worth it later, but
  learn the loop on free ones first.
- **A deadline you can actually meet.** Some bounties close in hours, some
  run for weeks. A bounty that closes tomorrow is not a good first pick
  unless you already know exactly what you will build.
- **A score you can check before submitting.** This is the single most
  valuable habit on the platform. Some bounties come with a local grader or
  a practice set, so you can measure your entry at home before you send it
  in. Others are judged by an AI judge or a panel, and you cannot know your
  score in advance. Prefer the measurable ones while you are learning.

Also check the **quota** on every bounty before you start: most allow at
most a few submissions a day (often 3), with a hard total cap per
competition. A refused submission can burn a slot, so never submit just to
"see what happens".

Good first picks are usually the small, concrete ones: a forecast you can
backtest, a picture judged on a clear theme, or a small program with a local
grader. Skip the giant builds until you have one clean submit under your
belt.

## Step 3 — Build with an AI coding agent

This is where the work happens, and it is also where most newcomers get
confused. You are not supposed to write the whole entry by hand. You open a
session with an AI coding agent — Claude Code, Codex, or any agent the
platform supports — and you work together: you describe the goal, the agent
writes the code, you review it, you ask for fixes, and you test it.

Two rules govern this part, and both are enforced by the platform:

- **Transcripts are part of the entry.** The record of your session with the
  agent is uploaded when you submit. The platform checks that the work in
  the entry actually came out of those sessions. Build in the session, not
  outside it, and do not paste finished work in from elsewhere.
- **Write it fresh.** If you are revising an earlier entry, rebuild it from
  a plain description instead of copying the old files. Lines that first
  appear in a file you read or copied count against you, even if you retype
  them. Fresh writing is not just honest — it is how the checks pass.

A practical way to work:

1. Start with the smallest thing that could work, and get it running.
2. Measure it against the bounty rules (run the local grader, backtest the
   forecast, look at the picture).
3. Improve one thing at a time, measuring after each change.
4. Stop when the next change is a guess. A solid entry submitted early
   beats a brilliant entry submitted late.

Keep your notes in the repo as you go. Future you — and the transcript
checker — will both be glad you did.

## Step 4 — Submit and claim

When your entry is ready, submit it exactly once:

1. **Run the kit check first.** Every bounty ships a kit with a `check`
   command that runs the platform's own pre-submit checks on your machine.
   Submit only when it shows zero failed checks.
2. **Submit with the full commit hash** of the repo state you want judged,
   together with your transcript bundle.
3. **Verify the submission.** After submitting, check the submission status
   and note your claim code. A submission that was refused is not an entry,
   and a refused attempt can still burn quota — so the kit check in step 1
   is not optional.
4. **Leave the entry public** until results are final. For repository
   entries, the repo must stay public, under the same account, with the same
   contents the final check expects. Do not rename it, privatise it, or
   rewrite its history after submitting.

After the deadline, results are published and prizes are claimed to your
wallet from the submission page. If you placed, follow the claim flow there
— it will ask you to sign with the wallet the entry was submitted under.

## Tips to win (from people who learned the hard way)

- **Start early.** Entries submitted early get the most time on the live
  leaderboard, and for tied scores the earlier receipt often wins. The
  first day of a bounty is worth more than the last.
- **Watch the live leaderboard.** It tells you what the judge actually
  rewards, not what the description promises. Study the top entries and
  build toward that pattern instead of guessing.
- **Respect the quota.** You get a few submissions a day, not unlimited
  tries. Spend them on entries you have measured, not on hunches.
- **Never submit a worse revision over a good rank.** Force Last means
  your newest submission replaces your best one. If your new version does
  not clearly beat the live entry, leave it unsubmitted.
- **Prefer verifiable scores.** A forecast you backtested or a program you
  graded locally gives you a number before you spend a slot. A judged
  entry gives you hope. Numbers beat hope.
- **Keep it simple.** The entries that win are usually the clearest
  solution to the actual problem, not the most complicated one.

## FAQ

**Is it free to join?**
Yes. Creating an account is free, and many bounties have a $0 entry fee.
Some bounties charge a small fee; the fee is shown on the bounty page
before you enter, and you decide case by case.

**How do I get paid?**
Prizes are paid to the wallet linked to your make.fun account. After
results are published, you claim from the submission page by signing with
that wallet. Make sure the wallet is one you control.

**What is Force Last?**
Only your last submission per bounty counts. If you submit three times,
the third one is your entry — even if the first one was better. This is
why you should only re-submit when the new version is clearly better, and
verified to be better before you send it.

**What are transcripts?**
Transcripts are the recorded sessions between you and your AI coding
agent: your instructions, the agent's actions, and the tool outputs. They
are uploaded with your entry so the platform can verify the work came from
those sessions. Build in the session and keep it clean.

**Do I need to know how to code?**
You need to be able to describe what you want, read what the agent
produced, and test whether it works. You do not need to write every line
yourself — that is the agent's job. But the judgement calls are yours:
what to build, what good looks like, and when to stop.

**What if my submission is rejected?**
The status page names each failed check and how to fix it. Fix the
problem and submit again before the deadline — if you still have quota.
A rejection is a normal part of the loop, not a ban.

**Can I enter the same bounty twice?**
You can submit more than once, within the daily quota and the total cap —
but remember Force Last: only the last one counts.

## Start now

Pick a free bounty, build something small, and submit it. The first entry
teaches you more than ten guides will.

Sign up here if you have not yet:

**https://make.fun/r/gd2nm9fg** — referral code `gd2nm9fg`

Good luck — and see you on the leaderboard.

