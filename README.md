# PageSpeed Insights MCP Server by Insightful Pipe

[![MCP Compatible](https://img.shields.io/badge/MCP-Compatible-blue)](https://insightfulpipe.com/mcp-servers/pagespeed)
[![Insightful Pipe](https://img.shields.io/badge/Insightful_Pipe-MCP_Servers-purple)](https://insightfulpipe.com/mcp-servers)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> **Analyze website performance and Core Web Vitals with AI through MCP.**

Part of the [Insightful Pipe MCP Server Collection](https://insightfulpipe.com/mcp-servers) — The PageSpeed Insights MCP server enables Claude, ChatGPT, Cursor, and other AI assistants to analyze website performance. Get Core Web Vitals, performance scores, and AI-powered optimization recommendations.

[![Explore All MCP Servers](https://img.shields.io/badge/Explore_All-MCP_Servers-blue?style=for-the-badge)](https://insightfulpipe.com/mcp-servers)

![PageSpeed Insights MCP Server](https://insightfulpipe.com/images/google-pagespeed-insights-icon-2021-.svg)

## MCP Server URL

```
https://pagespeed.insightfulmcp.com/
```

## What is PageSpeed Insights MCP?

PageSpeed Insights MCP is a **remote Model Context Protocol server** that provides AI assistants with website performance analysis capabilities. This performance optimization integration allows you to:

- Analyze page speed and Core Web Vitals
- Get detailed Lighthouse performance breakdowns
- Receive AI-powered optimization recommendations
- Check accessibility and SEO scores
- Identify resource optimization opportunities

## Installation

### Claude

1. Copy the MCP Server URL: `https://pagespeed.insightfulmcp.com/`
2. Open [Claude Connectors Settings](https://claude.ai/settings/connectors)
3. Scroll to the bottom and click **Add custom connector**
4. Paste the URL and click **Add**
5. Click **Connect** on the connector to start authorization
6. Click **Authorize access** in the browser to complete the connection

### ChatGPT

1. Copy the MCP Server URL: `https://pagespeed.insightfulmcp.com/`
2. Open ChatGPT Settings → **Connections**
3. Click **Add Connection** and paste the URL
4. Authorize with your InsightfulPipe account

### Claude Code

```bash
claude mcp add pagespeed https://pagespeed.insightfulmcp.com/
```

### Cursor

1. Open Cursor Settings → **MCP Servers**
2. Add new server with URL: `https://pagespeed.insightfulmcp.com/`
3. Authorize the connection

## Available Actions

| Action | Description |
|--------|-------------|
| `core-web-vitals` | Core Web Vitals snapshot (FCP, LCP, CLS, TTI, TBT, Speed Index, TTFB) |
| `resource-optimizations` | Resource-focused audits (render-blocking, unused JS/CSS, caching, images) |
| `accessibility-seo` | Accessibility and SEO category scores with failing audits |
| `analyze.full` | Full Lighthouse payload across all categories |

## Usage Examples

### Performance Analysis

```
"Analyze the page speed of https://example.com"
```

### Core Web Vitals Check

```
"What are the Core Web Vitals for my homepage?"
```

### Resource Optimization

```
"What resources are slowing down my page?"
```

### Full Lighthouse Audit

```
"Run a full Lighthouse audit on this URL"
```

### Accessibility Check

```
"Check the accessibility score for this page"
```

## Core Web Vitals

| Metric | Description | Good Threshold |
|--------|-------------|----------------|
| LCP | Largest Contentful Paint | < 2.5s |
| FID/INP | First Input Delay / Interaction to Next Paint | < 100ms |
| CLS | Cumulative Layout Shift | < 0.1 |
| TTFB | Time to First Byte | < 800ms |
| FCP | First Contentful Paint | < 1.8s |
| TTI | Time to Interactive | < 3.8s |
| TBT | Total Blocking Time | < 200ms |
| Speed Index | Visual loading speed | < 3.4s |

## Why PageSpeed Insights MCP?

### For Web Developers
- **Performance monitoring** - Track site speed
- **Debug slow pages** - Identify bottlenecks
- **Optimization guidance** - Know what to fix

### For SEO Professionals
- **Core Web Vitals** - Critical ranking factor
- **Mobile performance** - Mobile-first indexing
- **Technical SEO** - Performance auditing

### For Marketers
- **Conversion optimization** - Speed impacts conversions
- **User experience** - Better page experience
- **Competitive analysis** - Compare against competitors

## Security & Privacy

- **Google API** - Official PageSpeed Insights API
- **No data storage** - URLs not persisted
- **Public page analysis** - Only public URLs
- **Rate limiting** - API quota management

## Explore More MCP Servers by Insightful Pipe

Visit **[insightfulpipe.com/mcp-servers](https://insightfulpipe.com/mcp-servers)** to discover our full collection of MCP servers for marketing and analytics.

### SEO & Performance MCP Servers
- [Google Search Console MCP](https://insightfulpipe.com/mcp-servers/google-search-console) - SEO analytics
- [Web Crawler MCP](https://insightfulpipe.com/mcp-servers/crawler) - Site crawling
- [Screenshot MCP](https://insightfulpipe.com/mcp-servers/screenshot) - Visual capture

### Analytics MCP Servers
- [Google Analytics MCP](https://insightfulpipe.com/mcp-servers/google-analytics) - Website analytics
- [Google My Business MCP](https://insightfulpipe.com/mcp-servers/google-my-business) - Local SEO

**[View All MCP Servers →](https://insightfulpipe.com/mcp-servers)**

## Resources

- [Documentation](https://insightfulpipe.com/docs/pagespeed)
- [Video Tutorial](https://www.youtube.com/playlist?list=PLJNzvjxzI5Xwe__BJJLAelSF0ewO3mEFk)
- [InsightfulPipe Blog](https://insightfulpipe.com/blogs)

## Support

- **Documentation**: [insightfulpipe.com/docs](https://insightfulpipe.com/docs)
- **All MCP Servers**: [insightfulpipe.com/mcp-servers](https://insightfulpipe.com/mcp-servers)
- **Email**: support@insightfulpipe.com

---

**[Insightful Pipe](https://insightfulpipe.com)** — AI-powered marketing analytics through MCP servers. [Explore all integrations →](https://insightfulpipe.com/mcp-servers)

## License

MIT License - see [LICENSE](LICENSE) for details.
