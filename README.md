# Token Radar — Phantom Deep Link Signer

Static page that signs the make.fun Token Radar 01 entry message using the
official Phantom deep link flow (Connect + signMessage). It does not use the
Phantom in-app browser provider.

- Opens in Chrome Android.
- Connects via `https://phantom.com/ul/v1/connect` (deep link).
- Signs via `https://phantom.com/ul/v1/signMessage` (deep link, NaCl box encrypted).
- Verifies the connected wallet is `Coo3gDVDGgyXNGvcFxabCeGQrz1WnMD5HieRqLHe9yUJ` (MAKEFUN BOUNTY).
- Never asks for a seed phrase, private key, or transaction.

Live page: https://ashatralife24.github.io/token-radar-signer/
