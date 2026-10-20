# Happy Townhome — haha happy townhome llc

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `hahahappytownhomellc.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/hahahappytownhomellc.mjs`).
> To change the content, edit that file and run `node build.mjs hahahappytownhomellc` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@hahahappytownhomellc.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Monthly rent / $Monthly rent / $No) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
HAHA Happy Townhome LLC, a Florida limited liability company (document number L24000046867), owns and lets townhomes on long-term residential tenancies: published application criteria applied the same way to every applicant, written leases that set out what the landlord maintains and what the tenant does, security deposits held and accounted for as Florida law requires, and maintenance with one point of contact and a stated response time. Association rules affecting tenants are given before signing. The company lets only property it owns and is an equal housing opportunity provider. Site: hahahappytownhomellc.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
