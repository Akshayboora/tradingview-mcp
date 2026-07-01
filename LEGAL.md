# Legal Disclaimer & Terms of Use

This project is provided **for personal, educational, and research purposes only**.

## How This Tool Works

This tool uses the Chrome DevTools Protocol (CDP), a standard debugging interface built into all Chromium-based applications by Google. It does not reverse engineer any proprietary code or bypass any security measures.

**What it does:**
- Connects to your **locally running TradingView Desktop instance** via Chrome DevTools Protocol on localhost:9222
- Reads chart state (symbol, timeframe, indicator values, drawings)
- Controls chart UI (change symbols, timeframes, add indicators, create drawings)
- Compiles Pine Script offline using TradingView's server-side compile endpoint
- Streams real-time data from your local chart instance

**What it does NOT do:**
- Connect to TradingView's servers or APIs
- Store, transmit, or redistribute any market data
- Bypass TradingView's paywall or access restrictions
- Execute real trades
- Modify any TradingView files on your system
- Intercept or proxy any network traffic

The debug port is **disabled by default** and must be explicitly enabled by you using the standard Chromium flag `--remote-debugging-port=9222`. Nothing happens without that deliberate step.

## Terms & Conditions

By using this software, you acknowledge and agree that:

### 1. Your Responsibility

**You are solely responsible** for ensuring your use of this tool complies with:
- [TradingView's Terms of Use](https://www.tradingview.com/policies/)
- [TradingView's Community Rules](https://www.tradingview.com/policies/community-rules/)
- All applicable laws in your jurisdiction
- Any data provider and exchange licensing terms

### 2. TradingView Terms of Use Compliance

TradingView's Terms of Use **restrict automated data collection, scraping, and non-display usage** of their platform and data.

This tool uses Chrome DevTools Protocol to programmatically interact with your **local desktop instance only**. However:

- If you use this tool to collect, redistribute, or commercially exploit TradingView's market data, **you are in violation of their Terms of Use**, regardless of whether the data came from their servers or your local chart.
- You are responsible for ensuring your streaming, analysis, and data usage complies with TradingView's terms.
- Market data accessed through this tool remains subject to exchange and data provider licensing terms.

### 3. Assumption of Risk

**You assume all risk** associated with using this tool. The authors are not responsible for:
- Account bans or suspensions from TradingView
- Legal action from TradingView Inc.
- Loss of data or chart configuration
- Unintended consequences of chart automation
- Compliance violations resulting from your use

### 4. Prohibited Uses

This tool **must not be used** for:

- **Redistributing, reselling, or commercially exploiting TradingView's market data** — even if collected via this tool, data remains subject to TradingView's licensing terms
- **Circumventing TradingView's access controls or subscription restrictions** — this tool requires a valid TradingView Desktop subscription
- **Performing automated trading or algorithmic decision-making** using extracted data without human review
- **Violating the intellectual property rights of Pine Script indicator authors** — do not copy, modify, or redistribute others' indicators without permission
- **Connecting to TradingView's servers or infrastructure** — all access must be via your locally running Desktop app only
- **Reverse engineering TradingView's software** — use only the documented Chrome DevTools Protocol
- **Accessing TradingView without a valid subscription** — this tool requires paid access to TradingView Desktop

### 5. Streaming & Data Handling

The streaming functionality monitors **your locally running TradingView Desktop instance only**. It does not:
- Connect to TradingView's servers or infrastructure
- Extract data from TradingView's CDN or databases
- Perform any network requests to tradingview.com or related domains

However:
- Market data accessed through this tool remains subject to exchange and data provider licensing terms
- **Do not redistribute, store, or commercially exploit any data obtained through this tool**
- Programmatic consumption of data may conflict with TradingView's Terms of Use regardless of the data source

### 6. Undocumented APIs

This tool accesses internal, undocumented TradingView application interfaces that:
- May change or break without notice in any TradingView update
- Are not officially supported by TradingView Inc.
- Should not be relied upon for production systems
- May violate TradingView's Terms of Service if used beyond intended scope

**Pin your TradingView Desktop version** if stability is critical. Test thoroughly after updates.

### 7. No Warranty

This tool is provided **"as is"** without any warranty, express or implied:
- No warranty of fitness for a particular purpose
- No warranty of merchantability
- No warranty that the tool will continue to work with future TradingView updates
- No warranty of data accuracy or completeness

## What Happens If You Violate These Terms?

TradingView may:
- **Ban your account** without refund
- **Pursue legal action** for Terms of Use violations
- **Block access** to TradingView services

The authors of this tool:
- **Cannot help you recover** a banned account
- **Cannot reverse** TradingView's enforcement actions
- **Are not liable** for any consequences

## When Should You NOT Use This Tool?

❌ Do not use this tool if:
- You plan to redistribute or sell TradingView data
- You plan to bypass subscription restrictions
- You plan to perform algorithmic trading without human review
- You are unsure whether your intended use complies with TradingView's terms
- You cannot accept the risk of account suspension or legal action

✅ This tool is appropriate for:
- Personal research and education
- Manual chart analysis with AI assistance
- Pine Script development and learning
- Single-user chart automation on your own charts
- Testing and experimentation (non-commercial)

## If You're Unsure

**Do not use this tool.** Contact TradingView support or legal counsel if you have questions about:
- Whether your use case complies with their Terms of Use
- Whether you need special licensing or permissions
- Whether commercial use is allowed
- Data redistribution or resale options

## Attribution

This disclaimer is based on:
- [TradingView Terms of Use](https://www.tradingview.com/policies/)
- [Chrome DevTools Protocol Documentation](https://chromedevtools.github.io/devtools-protocol/)
- [Electron Security Best Practices](https://www.electronjs.org/docs/tutorial/security)

---

**Use at your own risk.** If you are unsure whether your intended use complies with TradingView's terms, **do not use this tool**.

Last updated: 2026-07-01
