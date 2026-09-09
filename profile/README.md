# INA GPT GmbH

**Sovereign AI platform, built and operated in Germany.**

INA GPT GmbH develops and operates an AI platform for organisations that need
their data to stay under their own control and their supplier to be
contractually accountable for it. We are a German GmbH: there is a named
Geschäftsführer, a commercial register entry, and a German court of
jurisdiction.

---

## Certification

### Issued

| Standard | Scope | Reference | Validity |
|---|---|---|---|
| **ISO/IEC 27001:2022** | Operation and provision of an AI-powered platform · *Betrieb und Bereitstellung einer KI gestützten Plattform* | Reg. No. **12 310 71178 TMS**, TÜV SÜD | **2026-08-10 → 2029-08-09** |

Certificate verification (Fundstelle): <https://www.tuvsud.com/ms-zert>

### In progress

| Standard | Status |
|---|---|
| **ISO/IEC 42001:2023** — AI management system | Certification with TÜV SÜD **in progress. Not yet issued.** |

### Memberships

**Gaia-X** — European Association for Data and Cloud AISBL, European Member
(Start-up), **Member No. 0469** · KI Bundesverband e. V. · Startup-Verband
(No. 14346) · IHK Berlin (No. 10702437784)

---

## What we build

**INA GPT** — an AI assistant platform for German and European organisations.

**INA Coding** — a self-hostable AI coding assistant for regulated
environments. Point it at your own deployment and no traffic reaches us; the
repository states plainly what the shipped default is.
→ [`ina-coding-extension`](https://github.com/ina-gpt/ina-coding-extension)

**INA Calling** — messaging and calling, built on one conversation model.

---

## How we work in the open

These repositories carry the checks that keep the public surface honest, and
each ships with the negative proof that it can actually fail:

- **`brand-lint`** — the public naming standard in `BRANDING.md`, enforced in
  CI and at commit time. Licence and third-party attribution files are exempt by
  design: attribution is a licence condition, and stripping it to satisfy a
  naming preference would trade a marketing question for a licence breach.
- **`secret-lint`** — credential detection across four channels, including git
  remote URLs and inline command prefixes, following symlinks and crossing
  filesystem boundaries.
- **`claim-audit`** — every security and privacy claim in a public README must
  name a test that exists and passes. A claim without a proof fails the build.
- **`surface-lint`** — a weekly crawl of our live site for the same rules.

Claims about certification state only what is issued, with its registration
number and validity window. Where a certification is in progress it is described
as in progress.

---

## Company

**INA GPT GmbH**
Selerweg 40 A, 12169 Berlin, Deutschland

| | |
|---|---|
| Geschäftsführer | Hassan Taheri |
| Registergericht | Amtsgericht Berlin (Charlottenburg) |
| Registernummer | **HRB 288452 B** |
| USt-IdNr. (§ 27 a UStG) | **DE464255291** |
| E-Mail | <info@inagpt.com> |
| Telefon | +49 30 4243 2400 |
| Web | <https://inagpt.com> |

Data processing agreements (Auftragsverarbeitungsvertrag under Art. 28 GDPR),
our subprocessor list and our full legal notice are published at
<https://inagpt.com>.

---

<sub>Made in Berlin, Germany.</sub>
