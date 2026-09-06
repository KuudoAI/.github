<div align="center">
  <img src="https://raw.githubusercontent.com/KuudoAI/.github/main/profile/assets/kuudo-logo.svg" width="96" alt="Kuudo logo" />

  # Kuudo

  **Run real Amazon work from any AI client — on your data, in your cloud.**

  [Website](https://www.kuudo.com) · [Docs](https://www.kuudo.com/docs/) · [Guides](https://www.kuudo.com/guides/) · [Discussions](https://github.com/orgs/KuudoAI/discussions) · [Roadmap](https://github.com/orgs/KuudoAI/projects)
</div>

Kuudo connects Amazon Ads, AMC, SP-API, and Vendor Central to ChatGPT, Claude, Cursor, and any MCP client, so teams can run governed Amazon workflows from chat.

## Products

- [**Amazon Ads MCP**](https://www.kuudo.com/features/amazon-ads-mcp/) — the entire Amazon Ads stack: 711 operations across 55 services, from Sponsored Products to DSP and AMC. Open source.
- [**Amazon Selling Partner MCP**](https://www.kuudo.com/features/amazon-selling-partner-mcp/) — the entire Selling Partner API: 304 operations across 40+ services, from Catalog and Orders to FBA and A+ Content. ([repository](https://github.com/KuudoAI/amazon-selling-partner-mcp))
- [**Amazon Vendor Central MCP**](https://www.kuudo.com/features/amazon-vendor-central-mcp/) — every Vendor Central function: Direct Fulfillment, Retail Procurement, Data Kiosk, and analytics. ([repository](https://github.com/KuudoAI/amazon-vendor-central-mcp))
- [**Amazon Agent Iris**](https://www.kuudo.com/features/amazon-agent-iris/) — generates, edits, and audits compliant, on-brand product images from your live listings and ads.
- [**Amazon Agent Atlas**](https://www.kuudo.com/features/agent-atlas/) — the Amazon knowledge your agent didn't have to earn: 7,589 indexed documents plus a hand-built decision rulebook.
- [**Amazon Agent Crawl**](https://www.kuudo.com/features/agent-crawl/) — one endpoint, any product question, answer-shaped output.
- [**Amazon Agent Flow**](https://www.kuudo.com/features/amazon-agent-flow/) — turns Selling Partner and Ads into a durable, query-ready data layer your agents can act on.
- [**Skills**](https://www.kuudo.com/features/skills/) — guided, multi-step automations for real Amazon Ads and Seller workflows.

## Get started

[`amazon_ads_mcp`](https://github.com/KuudoAI/amazon_ads_mcp) is our open-source MCP server for the Amazon Ads API — **711 operations across 55 services**, from Sponsored Products, Brands, Display, and TV to DSP, AMC, and the unified Ads API v1.

```bash
git clone https://github.com/KuudoAI/amazon_ads_mcp.git
cd amazon_ads_mcp && cp .env.example .env   # add your Amazon Ads API credentials
docker compose up
```

Then connect your client: [ChatGPT](https://www.kuudo.com/docs/quick-start/chatgpt/) · [Claude](https://www.kuudo.com/docs/quick-start/claude/) · [n8n](https://www.kuudo.com/docs/quick-start/n8n/) — every client's setup is in the [docs](https://www.kuudo.com/docs/).

## Found a bug? Want a feature?

This is the place.

- 🐛 [Report a bug](https://github.com/KuudoAI/community/issues/new?template=bug_report.yml) — a broken tool, a wrong response, a setup step that fails
- 💡 [Request a feature](https://github.com/KuudoAI/community/issues/new?template=feature_request.yml) — a tool, surface, or behavior Kuudo should have
- 💬 [Ask a question](https://github.com/orgs/KuudoAI/discussions) — troubleshooting, how-do-I, best practices
- 🗺️ [Roadmap](https://github.com/orgs/KuudoAI/projects) — see what's planned, 👍 the issues you want

Learning rather than reporting? The field guides walk through real workflows:
[Build an AMC cart-abandoner audience](https://www.kuudo.com/guides/amc-audiences/amc-cart-abandoner-audience/) · [Quantify Subscribe & Save lift](https://www.kuudo.com/guides/amc-measurement/amc-subscribe-and-save-lift/) · [CLTV segmentation beyond ROAS](https://www.kuudo.com/guides/amc-advanced/amc-cltv-cohort-segmentation/) · [Dispute a PO chargeback](https://www.kuudo.com/guides/vendor-ops/vendor-po-chargeback-disputes/)

---

<div align="center">

**Private. Trusted. Owned.**
Kuudo runs in your cloud, not ours. Nothing inside it trains anyone else's model. If you ever walk away, what you built keeps running.

[kuudo.com](https://www.kuudo.com) · [X](https://x.com/Kuudo) · [LinkedIn](https://www.linkedin.com/company/kuudo/)

</div>
