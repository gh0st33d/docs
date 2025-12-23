# DeepDive Platform Documentation

This directory contains the API documentation powered by [Mintlify](https://mintlify.com).

## Local Development

### Preview Documentation

```bash
cd docs
npx mintlify dev
```

This starts a local server at http://localhost:3000 with hot-reload.

### File Structure

```
docs/
├── mint.json              # Mintlify configuration
├── introduction.mdx       # Platform overview
├── getting-started.mdx    # Quick start guide
├── authentication.mdx     # API authentication
├── credits.mdx            # Credit system
├── rate-limiting.mdx      # Rate limits
├── ml-enrichment.mdx      # ML analysis options
├── pagination.mdx         # Pagination guide
├── errors.mdx             # Error handling
├── platforms/             # Platform-specific guides
│   ├── tiktok.mdx
│   ├── instagram.mdx
│   ├── youtube.mdx
│   ├── reddit.mdx
│   └── ml.mdx
├── openapi.json           # OpenAPI specification
└── favicon.svg            # Site favicon
```

## Deployment

Mintlify automatically deploys when connected to your repository. See [Mintlify Deployment](https://mintlify.com/docs/quickstart) for setup.

## Updating Documentation

1. Edit `.mdx` files in the `docs/` directory
2. Preview locally with `npx mintlify dev`
3. Commit and push to deploy

## Configuration

Edit `mint.json` to customize:
- Navigation structure
- Colors and branding
- API base URL
- OpenAPI integration

See [Mintlify Configuration](https://mintlify.com/docs/settings/global) for all options.
