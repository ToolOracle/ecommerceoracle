# 🛒 ecommerceOracle

**Consumer MCP Server** — 8 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-8-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Free-2196F3?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/ecommerce/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "ecommerceoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/ecommerce/mcp/"]
    }
  }
}
```

## Tools (8)

| Tool | Description |
|------|-------------|
| `product_search` | Search products by name across Algolia, UPCItemDB, and Open Food Facts. Returns  |
| `barcode_lookup` | Look up product by EAN/UPC barcode. Returns full product details, prices from mu |
| `shopify_products` | Fetch products from any Shopify-powered store via their public /products.json en |
| `price_comparison` | Compare product prices across multiple sources. Provides merchant links for Idea |
| `category_trends` | Trending products and news in a specific category. |
| `marketplace_monitor` | Monitor marketplace presence and pricing news for your brand vs competitor. |
| `product_detail` | Extract structured product data (price, rating, images) from any product page UR |
| `health_check` | EcommerceOracle server status. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 100 calls/day | €0 |
| Pro | 10,000 calls/day | €29/month |
| Enterprise | Unlimited | Custom |

> Free tier includes all tools with rate limiting. Upgrade for higher limits and priority support.

## Part of ToolOracle

ecommerceOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.



**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/ecommerce/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
