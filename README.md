# Chouhan Industries

**Open by Design. Built to Last.**

Website for [chouhan.ai](https://chouhan.ai) — an open hardware manufacturing company.

## What We Build

**Open Media Platform (OMP)** — a fully open, modular media computing platform. Every input, output, codec, and expansion module is replaceable and documented. The core board handles computing. Expansion modules handle everything else.

Hardware released under [CERN OHL-S v2.0](https://ohwr.org/cern_ohl_s_v2.txt).

## Pages

| Page | Path |
| --- | --- |
| Homepage | `index.html` |
| Products | `products.html` |
| Open Source | `open-source.html` |
| About | `about.html` |
| Blog | `blog.html` |
| Careers | `careers.html` |
| Contact | `contact.html` |

## Stack

Static HTML/CSS/JS. No framework. No build step.

```text
assets/
  css/style.css       design system
  js/script.js        nav scroll + mobile menu
  favicons/           ico, png, svg
```

## Local Development

```bash
# any static server works
npx serve .
python3 -m http.server 8080
```

## License

Hardware designs: [CERN OHL-S v2.0](https://ohwr.org/cern_ohl_s_v2.txt)  
Website code: MIT
