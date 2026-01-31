# Soqueroir

Website for soqueroir.com.br hosted on GitHub Pages.

## Setup

This site is configured to use GitHub Pages with a custom domain.

### GitHub Pages Configuration

1. Go to your repository settings on GitHub
2. Navigate to **Settings** → **Pages**
3. Under "Source", select **Deploy from a branch**
4. Select the branch (usually `main`) and root folder (`/`)
5. The CNAME file will automatically configure the custom domain: `soqueroir.com.br`

### Custom Domain (DNS)

Ensure your domain registrar has DNS records pointing to GitHub Pages:

**For apex domain (soqueroir.com.br):**
- Add `A` records pointing to:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`

**For www subdomain (optional):**
- Add a `CNAME` record pointing to: `<username>.github.io`

Or use GitHub's automatic nameservers:
- `ns-1707.awsdns-21.co.uk`
- `ns-48.awsdns-06.com`
- `ns-632.awsdns-03.org`
- `ns-1234.awsdns-45.net`

## Development

Simply edit the `index.html` file and push to the repository. Changes will be live within seconds.
