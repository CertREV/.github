<p align="center">
  <img src="https://raw.githubusercontent.com/CertREV/.github/main/profile/logo.png" alt="CertREV" width="112" height="112" />
</p>

<h1 align="center">CertREV</h1>

<p align="center"><strong>Expert-reviewed content certification for E-E-A-T, AI citations, and organic growth.</strong></p>

<p align="center"><em>Real experts, behind every word you publish.</em></p>

CertREV attaches credentialed expert review to content, so it stays citable in an era where
AI search filters for verifiable expertise. Credentialed MDs, PharmDs, RDs and RNs review,
revise and certify your drafts. Every certificate publishes as a card on your page and as
JSON-LD that AI assistants already parse.

CertREV certifies; the expert reviews.

Despite the name, this is not certificate revocation.

## The thesis

Generative engines (ChatGPT, Google AI Overviews, Perplexity, and the rest) increasingly
decide *which* sources to cite and which to filter out. Their bias is toward content that
carries verifiable signals of experience, expertise, authoritativeness and trust: the
"E-E-A-T" Google has long described for ranking, now load-bearing for **AEO / GEO**
(answer-engine and generative-engine optimization).

Most content has no way to *prove* any of that. CertREV closes the gap. A named,
credentialed expert reviews the content claim by claim, and the proof publishes with the
page.

## What a certification attaches

- **Expert memo** · a named, credentialed reviewer's first-person assessment of the content.
- **A verified credential** · the license is verified before assignment, and the credential
  travels with the certificate. CertREV recognizes 274 specialties across MD, PharmD, RD, RN,
  PhD and JD.
- **`reviewedBy` JSON-LD** · machine-readable provenance for crawlers and answer engines.
- **A SHA-256 fingerprint** · of the exact text that was approved, so a page that drifts from
  what was reviewed can be detected rather than assumed.
- **A badge and contributor card** · the human-readable mark, rendered on your own page.
- **A public certificate** · at certrev.com, that anyone can verify.

Built for health, beauty and wellness brands: the content, compliance and legal teams who
answer to Google, and to readers.

Nothing ships without you. Work lands in your CMS as a draft and waits, and sign-offs are
recorded and dated.

## Open source

- [`@certrev/cert-block`](https://www.npmjs.com/package/@certrev/cert-block) · the render edge.
  SSR-safe React components, a deterministic schema.org JSON-LD projector, and a fail-closed
  verify layer.
- [`@certrev/cert-contract`](https://www.npmjs.com/package/@certrev/cert-contract) · the
  signed-envelope contract and its verification kernel.
- [`reviewedby-schema`](https://www.npmjs.com/package/reviewedby-schema) · standards-correct
  `reviewedBy` / E-E-A-T JSON-LD, MIT-licensed and usable without CertREV.

Public source for the first two lives in [cert-kit](https://github.com/CertREV/cert-kit).

## Links

- Website · https://certrev.com
- Pricing · https://certrev.com/pricing
- Contact · support@certrev.com
- Company · https://www.linkedin.com/company/certrev
- Founder · Owen Walls · https://www.linkedin.com/in/owenwalls

<p align="center"><sub>CertREV LLC · Expert-reviewed content certification.</sub></p>
