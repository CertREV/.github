<p align="center">
  <img src="https://raw.githubusercontent.com/CertREV/.github/main/profile/logo.png" alt="CertREV" width="112" height="112" />
</p>

<h1 align="center">CertREV</h1>

<p align="center"><strong>Expert review for brand content, made verifiable.</strong></p>

<p align="center"><em>Real experts, behind every word you publish.</em></p>

CertREV matches a brand's health, beauty and wellness content with a credentialed expert who
reviews it claim by claim, corrects what is wrong, and certifies the final text under their
own name. The proof publishes with the page: a card readers can see, schema.org JSON-LD that
search engines can read, and a public certificate anyone can open.

## Why

Most content has no way to show who checked it. Google's guidance for health and other
high-stakes topics asks who created a page, how, and why, and says its systems give more
weight to content that shows real expertise and trust. A named, credentialed reviewer whose
review anyone can verify is a direct answer to that question. What we attach is
evidence a reader, a regulator or a machine can check.

## What a certification attaches

- **Expert memo** · a first-person narrative from the named reviewer, drawing on their own
  relevant experience with the topic: the Experience in Google's E-E-A-T, in the expert's words.
- **A verified credential** · checked before the expert is assigned, and shown with the
  certificate. The catalog covers more than 250 credential types, from physicians, pharmacists
  and dietitians to nurses, estheticians and cosmetic chemists.
- **`reviewedBy` JSON-LD** · machine-readable provenance, attached to the page's own markup.
- **A SHA-256 fingerprint** · of the exact text that was approved, so a page that drifts from
  what was reviewed can be detected rather than assumed.
- **A badge and contributor card** · the human-readable mark, rendered on your own page.
- **A public certificate** · at certrev.com, that anyone can verify.

## How it maps to E-E-A-T

Google's quality guidelines describe four things that make content trustworthy. Each part of a
certification answers one of them.

| Pillar | What Google asks | What CertREV attaches |
| :-- | :-- | :-- |
| **Experience** | Has the author dealt with this first-hand? | The expert memo: a first-person narrative from the reviewer's own practice. |
| **Expertise** | Do they have the knowledge or training? | A credential verified against its issuer before the expert is assigned. |
| **Authoritativeness** | Are they a recognized source on the topic? | A named expert matched to the subject, with a public profile and `reviewedBy` markup linking page, person and credential. |
| **Trust** | Is the page accurate, honest and safe to rely on? | A public certificate, a fingerprint of the exact approved text, a dated record of every sign-off, and a plain statement that the reviewer is paid and independent. |

Built for health, beauty and wellness brands, and for the content, compliance and legal teams
behind them.

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
- Founders · Kim Walls · https://www.linkedin.com/in/kimwalls/ and Owen Walls · https://owenwalls.com

<p align="center"><sub>CertREV LLC · Expert review you can verify.</sub></p>
