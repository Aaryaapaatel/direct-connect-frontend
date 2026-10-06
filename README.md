# Direct Connect — frontend

Static frontend for Direct Connect, a platform where brands and creators find each other, agree on terms, fund campaigns and release payments milestone by milestone.

## Pages

| File | What it is |
|---|---|
| `index.html` | Landing page (scroll animations, floating discovery map, niches marquee) |
| `login.html` | Glass sign-in page; the panel slides between Log in and Sign up. Google, Apple or email. |
| `brand.html` | Brand dashboard: overview, campaigns, discover creators, payments, messages |
| `creator.html` | Creator dashboard: overview, opportunities, campaigns, earnings, messages, profile |
| `styles.css` | Shared design system (dashboards and common components) |
| `landing.css` | Landing page styles and motion |

## Run locally

No build step or dependencies. From this folder:

```sh
python3 -m http.server 5173
```

Then open http://localhost:5173.

## Notes

- There is no backend yet. Log in, sign up, and the Google/Apple buttons just open the matching dashboard; the spot to connect real auth is marked in `login.html`.
- All dashboard data is sample content.
- Animations respect the system "reduce motion" setting.
