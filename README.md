# frenkalassamayoa.com 🚲

My personal website and portfolio, live at **[frenkalassamayoa.com](https://frenkalassamayoa.com)**.

I'm a bike mechanic turned Senior Operations Manager. This site is where I show the tools I've built to run bike service hubs, plus the stuff that keeps me going off the clock.

## What's inside

| Path | What it is |
| --- | --- |
| `index.html` | The whole site: hero, about, apps, resume, music, movies, and my bike build sheet |
| `demos/` | Interactive demos of the apps I've built, all running on fake data |
| `photos/`, `videos/` | Images and the ride footage used on the site |
| `_headers` | Security headers (HTTPS only, no framing, approved outside content only) |
| `_redirects` | Sends old addresses to the main domain |

## Apps featured

- **Pandaworks**: work orders and parts inventory for bike service hubs
- **Warranty Desk**: warranty case tracking with role-based access
- **Path for Advancement**: a role-ladder scorecard so staff know how to grow
- **Pay Bands**: compensation planning, shown as a concept only
- **Ops dashboards and automations**: the analysis and workflows behind the hubs

## Run it locally

It's a plain static site with no build step:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
