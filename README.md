# ljding.app

Homepage for [ljding.app](https://ljding.app) — a landing page that lists my apps hosted as subdomains.

## Apps

| App | Live | Source |
| --- | --- | --- |
| Learn Some AI | [learn.ljding.app](https://learn.ljding.app) | [znding04/learn-some-ai](https://github.com/znding04/learn-some-ai) |
| Play Arcade Games | [arcade.ljding.app](https://arcade.ljding.app) | [znding04/play-arcade-games](https://github.com/znding04/play-arcade-games) |
| Who To Hang With | [hangwith.ljding.app](https://hangwith.ljding.app/#/) | [znding04/who-to-hang-with](https://github.com/znding04/who-to-hang-with) |

## Local preview

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deployment

Static site — deployable via GitHub Pages, Cloudflare Pages, Vercel, or any static host. To serve at the root domain `ljding.app`, point the apex DNS to the host and configure the custom domain.
