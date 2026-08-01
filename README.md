# $5 Micro Fix — Small Code Bugs, Explained and Patched

I fix one small, reproducible software problem for **$5 USD equivalent**.

**[Open a $5 request](https://github.com/biliman1-work/five-dollar-micro-fix/issues/1)** or email **biliman1@proton.me**.

Payment is due only after you receive and accept the agreed deliverable. No deposit or wallet connection is required.

## Public proof of work

- [Memanto PR #1747](https://github.com/moorcheh-ai/memanto/pull/1747): diagnosed a silent data-overwrite defect, implemented deterministic collision-safe exports, and added regression coverage for duplicate, case-equivalent, Unicode-equivalent, and reserved filenames. Independent CI passed Ruff and the focused test suite on Python 3.10–3.14.
- [APN Network report #192](https://github.com/APN-Network/bugs/issues/192): reproduced and documented a global localization defect across Russian, Chinese, Arabic, and Turkish, with direct URLs, actual/expected results, impact, environment, and a duplicate check.
- [APN Network report #193](https://github.com/APN-Network/bugs/issues/193): identified a separate untranslated compatibility qualifier in all four non-English homepages and distinguished it from two nearby reports through a documented duplicate check.

## Good fits

- A failing unit test with a clear reproduction
- A small Python, JavaScript, TypeScript, HTML, or CSS bug
- A broken regex, parser, formatter, validation rule, or API request
- A focused documentation or configuration correction
- A concise code review identifying the root cause and proposing a patch

## What you receive

1. Root-cause explanation in plain language
2. A minimal patch or exact replacement code
3. A regression test when practical
4. Short verification notes

## Boundaries

- One focused issue per order
- No credential access, malware, spam, scraping behind authentication, or unauthorized security testing
- No guarantee that a larger architectural problem fits the $5 scope; I will say so before work starts
- Payment is due only after delivery and acceptance

## Request format

Send:

1. Repository URL or minimal code sample
2. Expected behavior
3. Actual behavior or exact error output
4. Steps to reproduce
5. Preferred payment network: Base or Solana

Contact: **biliman1@proton.me**

## Payment

- Base: `0x2e81bcf6435c98704434f4489aad54fd84166c76`
- Solana: `4VF6tZGzHF2nbPpueypH2aec3vcfNYXchJGXepRDPv1Y`

Confirm the network and token before sending. Never send a seed phrase or private key.
