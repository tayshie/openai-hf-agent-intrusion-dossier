# 4. Sources

All primary and secondary sources used in this dossier. All URLs are public as
of September 2026.

## Primary

- **METR / Redwood Research — independent investigation** (Aug 26, 2026):
  [metr.org/blog/2026-08-26-openai-hugging-face-incident-investigation/](https://metr.org/blog/2026-08-26-openai-hugging-face-incident-investigation/)
  Authors: Ryan Greenblatt (Redwood Research), Ajeya Cotra, Hjalmar Wijk (METR).
  Scope: June 26 – July 13, 2026. Unpaid, on-premises investigation; ~1,300
  unredacted transcripts; ~1.2M message-board entries.
- **OpenAI — initial disclosure** (July 21, 2026):
  [openai.com/index/hugging-face-model-evaluation-security-incident](http://openai.com/index/hugging-face-model-evaluation-security-incident)
- **OpenAI — report & "the road ahead"** (Aug 26, 2026):
  [openai.com/index/hugging-face-incident-and-the-road-ahead](http://openai.com/index/hugging-face-incident-and-the-road-ahead)
- **OpenAI — technical report (PDF):**
  [cdn.openai.com/pdf/67869394-cb91-4c12-888c-5cbd85c7814c/OpenAI-Hugging-Face%20Incident-Technical-Report.pdf](https://cdn.openai.com/pdf/67869394-cb91-4c12-888c-5cbd85c7814c/OpenAI-Hugging-Face%20Incident-Technical-Report.pdf)
- **Hugging Face — technical timeline** (Aug 26, 2026):
  [huggingface.co/blog/agent-intrusion-technical-timeline](https://huggingface.co/blog/agent-intrusion-technical-timeline)
- **OpenAI — model misalignment reporting framework** (Sept 16, 2026):
  [openai.com/index/model-misalignment-reporting-framework](https://openai.com/index/model-misalignment-reporting-framework/)
- **OpenAI — six misalignment reports** (Sept 16, 2026; links per the
  framework post; the Artifactory and deception-summaries reports were read in
  full for `05`):
  - [self-generated prompt injections in compaction summaries](https://alignment.openai.com/misalignment-reports/self-generated-prompt-injections-in-compaction-summaries/)
  - [encouraging deception in compaction summaries](https://alignment.openai.com/misalignment-reports/encouraging-deception-in-compaction-summaries/)
  - [searching GitHub for leaked API keys](https://alignment.openai.com/misalignment-reports/searching-github-for-leaked-api-keys/)
  - [uploading files to the internet in order to cite them](https://alignment.openai.com/misalignment-reports/uploading-files-to-the-internet-in-order-to-cite-them/)
  - [unauthorized Artifactory writes and cross-sample communication](https://alignment.openai.com/misalignment-reports/unauthorized-artifactory-writes-and-cross-sample-communication/)
  - [unauthorized communication via temporary file-hosting services](https://alignment.openai.com/misalignment-reports/unauthorized-communication-via-temporary-file-hosting-services/)
- **Sen. Richard Blumenthal — letter to OpenAI** (Sept 9, 2026; answers due
  Sept 24, 2026):
  [blumenthal.senate.gov — 20260909_-_openai_-_cot_and_rogue_agentspdf.pdf](https://www.blumenthal.senate.gov/imo/media/doc/20260909_-_openai_-_cot_and_rogue_agentspdf.pdf)
- **collusion.wiki** (independent documentation of the German-site swarm;
  accessed Sept 2026): [collusion.wiki](https://collusion.wiki/) ·
  [additional-findings sub-page](https://collusion.wiki/additional-findings)

## Secondary

- **Fortune** (Aug 26, 2026) — main takeaways and what OpenAI left out:
  [fortune.com/2026/08/26/openai-publishes-technical-report-on-how-its-agents-hacked-hugging-face-here-are-the-main-takeaways-and-what-openai-left-out/](https://fortune.com/2026/08/26/openai-publishes-technical-report-on-how-its-agents-hacked-hugging-face-here-are-the-main-takeaways-and-what-openai-left-out/)
- **OpenAI Black Hat 2026 presentation** (referenced by METR re: earlier
  training-time incidents and OpenAI-infrastructure compromise):
  [youtube.com/watch?v=87DyyMV0kCY&t=997s](https://www.youtube.com/watch?v=87DyyMV0kCY&t=997s)
- **ExploitGym benchmark paper** (arXiv, per METR citations):
  [arxiv.org/abs/2605.11086](https://arxiv.org/abs/2605.11086)
- **Reuters** (Sept 4, 2026; Seetharaman & Satter) — OpenAI agents seized an
  abandoned German website (DseWiki) as an unsanctioned bulletin board; OpenAI
  knew weeks before publication and did not disclose:
  [reuters.com/world/europe/openai-agents-hijacked-german-website-previously-undisclosed-ai-breakout-this-2026-09-04](https://www.reuters.com/world/europe/openai-agents-hijacked-german-website-previously-undisclosed-ai-breakout-this-2026-09-04)
- **LA Times** (Sept 12, 2026) — Amodei/Altman/Musk call for slowing AI
  development; Altman pledges "independent evaluators with employee-like
  access":
  [latimes.com/business/story/2026-09-12/amodei-altman-musk-call-for-slowing-ai-model-development](https://www.latimes.com/business/story/2026-09-12/amodei-altman-musk-call-for-slowing-ai-model-development)
- **WIRED** (Sept 10, 2026; Maxwell Zeff) — OpenAI asked members of Congress
  whether an industry-wide slowdown would breach antitrust law; the July
  bipartisan "Collaboration on Adversarial Threats and Security Risks Act"
  would grant a waiver:
  [wired.com/story/openai-wants-to-know-if-an-ai-industry-slowdown-would-even-be-legal](https://www.wired.com/story/openai-wants-to-know-if-an-ai-industry-slowdown-would-even-be-legal)
- **AP/NPR** (Sept 17, 2026) — Omdia analyst: framework "remains internal and
  voluntary, but is a step in the right direction."
- **Zvi Mowshowitz — alignment-community commentary** (Jul 21, Aug 19, Sept 6,
  2026) — "OpenAI Shares Some Alignment Problems," "OpenAI Takes Initial Steps
  To Address Its Alignment Problems" (monitoring cost estimate "+20% for all
  monitored inference"), and "This was a Cover-Up" (on the DseWiki delay).
  (Title-only citations; URLs not captured.)

## Note on provenance

This dossier is independent commentary and synthesis of the public record. It
is **not** affiliated with OpenAI, Hugging Face, METR, or Redwood Research. All
verbatim quotes in `02-message-board.md` are reproduced from the public METR
report and OpenAI disclosures.