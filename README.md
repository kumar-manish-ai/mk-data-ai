# Manish Kumar — Data & AI Architecture

Personal portfolio for enterprise Data, AI and solution architecture, with reference diagrams for Agentic AI, RAG, and AI observability.

## Portfolio

- **Profile:** Senior Solution Architect focused on enterprise Data & AI architecture, Agentic AI, LLM/RAG, cloud data platforms, and real-time intelligence.
- **Experience and credentials:** Resume-grounded details are presented in `index.html`; architecture diagrams are illustrative reference patterns, not claims that every depicted component is deployed.
- **Contact:** [LinkedIn](https://www.linkedin.com/in/manish-kumar-100570175/) · [GitHub](https://github.com/mk-data-ai) · [Email](mailto:manish.chaudhary.mrt@gmail.com)

## GitHub Pages deployment

A GitHub Actions workflow in `.github/workflows/pages.yml` publishes the repository root as a static GitHub Pages site.

1. Open **Settings → Pages** for this repository.
2. Under **Build and deployment**, choose **GitHub Actions** as the source.
3. Open **Actions** and confirm the Pages workflow completes successfully.
4. The project site is normally available at `https://mk-data-ai.github.io/mk-data-ai/` after Pages is enabled and deployment finishes.

## Custom domain plan: `manishkumar.ai`

The domain is a preference, not a confirmed registration. Availability and registration have **not** been verified or completed. Do not configure the domain in Pages or add a `CNAME` file until you have registered/controlled it.

After acquiring the domain:

1. In GitHub, open **Settings → Pages → Add a domain** (or the custom-domain field) and follow GitHub's domain-verification instructions. Prefer verifying the domain before attaching it to the site.
2. At the DNS provider, point the apex/root domain to GitHub Pages using the current official GitHub Pages DNS records. GitHub's documented IPv4 A records are `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, and `185.199.111.153`; add the documented IPv6 AAAA records if desired. A DNS provider's supported ALIAS/ANAME option may also work.
3. Optionally add `www` with a CNAME pointing directly to `mk-data-ai.github.io` (not the repository path), and configure the preferred canonical domain in Pages.
4. Wait for DNS propagation and GitHub's certificate provisioning. Then enable **Enforce HTTPS** in **Settings → Pages** when available.
5. Verify both DNS resolution and the final HTTPS URL after deployment.

Official guides:
- [Configuring a custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)
- [Managing custom domains and DNS records](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site)
- [Verifying a custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/verifying-your-custom-domain-for-github-pages)
- [Securing GitHub Pages with HTTPS](https://docs.github.com/en/pages/getting-started-with-github-pages/securing-your-github-pages-site-with-https)

Avoid wildcard DNS records. DNS changes and HTTPS certificate provisioning can take time; follow the current GitHub documentation if the dashboard's instructions differ.
