## Asaf Zamir

Fractional CTO and payments architect, based in Toronto and working mostly with
US and UK clients through [AZdev](https://azdv.co). Payments and regulated
fintech, plus the evaluation and model-risk side of putting AI into a regulated
institution.

Rails I work on: ACH, SEPA, UK Faster Payments, SWIFT and cards. Fifteen years,
most of it inside regulated platforms. [azdv.co](https://azdv.co) has the
history.

### Selected public work

Both of these are mine, under the [AZdev](https://github.com/AZdv) org. They
share a habit that is the point of publishing them: **neither one guesses.**

- **[payment-rail-reference](https://github.com/AZdv/payment-rail-reference)**
  US payment-rail parameters with the source URL and the date each value was
  checked. Anything that cannot be confirmed against a primary source is recorded
  in `gaps` rather than asserted, `supersedes` keeps the value that applied last
  year for whoever is debugging a payment from then, and a monthly job re-hashes
  every source page and opens an issue only when one actually moved.
- **[finstatement-parser](https://github.com/AZdv/finstatement-parser)**
  Python reference implementation for structured JSON extraction from US bank and
  credit-card statement PDFs. A field it cannot read comes back as `None` with the
  reason in `parse_errors` and a confidence of `0.0`, and that behaviour is
  documented before the features because it matters more than the happy path.

Many repos on this personal account are forks from 2013 to 2018.

### Smaller things

[hugo-data-to-pages](https://github.com/kidsil/hugo-data-to-pages) generates Hugo
pages from data files. [fx-cli](https://github.com/kidsil/fx-cli) is a
dependency-free Rust currency converter with a 90-day anomaly gauge.
[tz-cli](https://github.com/kidsil/tz-cli) is a timezone CLI built on jiff, with
the IANA database bundled into the binary so it does not depend on the host's
timezone database.

### Contact

[azdv.co](https://azdv.co) for work, [azdv.co/blog](https://azdv.co/blog) for
writing on payments and AI, and
[linkedin.com/in/asafzamir](https://linkedin.com/in/asafzamir). I wrote
*From Coder To CTO* (2024).
