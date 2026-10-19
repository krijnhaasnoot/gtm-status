# gtm-status

Static fallback for GTM Golf service notices. The iOS, Android and web apps read
`notices.json` from this repo when the regular backend is unreachable.

Format: see `servicemelding-contract.md` in the GTM releases folder. An empty
`notices` array means no notice is shown.
