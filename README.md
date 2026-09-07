# vanliessum.io

Personal website for Richard van Liessum.

Built with [Astro](https://astro.build) and [Tailwind CSS v4](https://tailwindcss.com).

## Local Development

```bash
# Install dependencies
npm install

# Start dev server (http://localhost:4321)
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deploy to Netlify

The site is configured for Netlify deployment. Connect your repository to Netlify and it will automatically:

1. Run `npm run build`
2. Publish the `dist` directory

### Custom Domain Setup

To configure `vanliessum.io`:

1. In Netlify, go to **Domain management** → **Add custom domain**
2. Add `vanliessum.io` as the primary domain
3. Add `www.vanliessum.io` as an alias (optional)

Configure DNS at your registrar:

| Type  | Name | Value                      |
|-------|------|----------------------------|
| A     | @    | 75.2.60.5                  |
| CNAME | www  | your-site.netlify.app      |

> Netlify's load balancer IP may vary. Check the Netlify dashboard for the current IP or use their DNS service.

Alternatively, use Netlify DNS for automatic configuration.

## Stack

- **Astro** — static site generation
- **Tailwind CSS v4** — styling
- **Zero client JS** — except a tiny dark-mode toggle

## License

MIT
