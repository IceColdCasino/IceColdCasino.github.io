# icecold.casino

Static site for the Ice Cold Casino circuit publication.

- Site: https://icecold.casino
- Organization: https://github.com/IceColdCasino
- Circuits: https://github.com/IceColdCasino/repo

GitHub Pages serves this repository from `main`. The apex domain is set in `CNAME`.

## Namecheap DNS

In Advanced DNS for `icecold.casino`, remove parking and URL-redirect records, then add:

| Type | Host | Value |
|------|------|--------|
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| CNAME | `www` | `icecoldcasino.github.io.` |

The trailing dot on the CNAME keeps Namecheap from appending `.icecold.casino`. After the records propagate, enforce HTTPS in the repository Pages settings.
