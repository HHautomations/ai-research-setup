# Research with AI without fake sources

Three setups so the AI answers from real papers, plus two copy-paste prompts.

## Setup 1: Consensus

A search engine that answers only from published research papers. Free tier available.

1. Go to consensus.app and sign up (free).
2. Ask a **yes/no question**, for example: `Does caffeine improve memory?`
3. Read the **Consensus Meter**: it sorts the top results into "yes", "no" and "possibly", so you see how many papers agree.
4. Open the papers under it. Each claim comes with a quote from the paper, not AI-written text.

The free tier includes unlimited paper searches plus a monthly allowance of Pro messages and Deep reviews.

## Setup 2: Connect PubMed to Claude

PubMed is the free public database of biomedical and life-science papers. The connector lets Claude search it and read the real abstracts instead of guessing. The connector is free for all Claude users.

1. Open claude.ai (or the Claude app) and sign in.
2. Go to **Settings > Connectors**.
3. Find **PubMed** (use **Browse connectors** if it is not listed) and tap **Connect**.
4. Start a new chat and ask, for example: `Find recent studies on sleep and exam performance and list each with its link.`
5. If Claude does not search PubMed, check the connector is switched on for that chat in the chat's tools menu.

On a Team or Enterprise plan, the owner adds it first: **Admin settings > Connectors > Browse connectors > PubMed > Add to your team**.

## Setup 3: Make it quote the exact sentence

Paste this at the start of any research chat:

```
For every claim you make, give the source (authors, year, title, link) and quote the exact sentence from that source that supports it, in quotation marks. Only use sources you have actually opened or searched in this chat. If you cannot quote a sentence, write "NO QUOTE FOUND" and do not make the claim. Never invent a paper, a quote or a number.
```

Rule of thumb: no quote, no trust.

## Bonus: check the AI's sources

Paste this after any answer that cites papers:

```
Check every source in your last answer, one by one:
1. Does this paper exist? Search for it and give the working link.
2. Do the authors, year and title match exactly?
3. Is the quoted sentence really in it? Quote where it appears.
4. Does it actually support the claim, or only something close to it?
Give a table: source / exists (yes, no, unsure) / quote found / supports claim. Mark anything you could not verify as UNVERIFIED. Do not defend your earlier answer; correct it.
```

Then open two or three of the links yourself. That takes one minute and catches what the AI misses.

---

Checked 14 November 2026 against:
- https://consensus.app and https://intercom.help/consensus-d118a252369c/en/articles/10087865-subscription-plans (free plan)
- https://consensus.app/home/blog/consensus-meter/ (Consensus Meter)
- https://academy.claude.com/tutorials/using-the-pubmed-connector-in-claude (PubMed connector setup)
- https://claude.com/connectors/pubmed

From hamzahussain.ai
