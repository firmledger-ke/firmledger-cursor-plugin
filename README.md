# FirmLedger for Cursor

Search and verify businesses on FirmLedger from inside Cursor.

## What it does

FirmLedger is a source-backed business directory. This plugin connects Cursor to FirmLedger's MCP server, so you can ask Cursor to look up a company, check whether it's verified, compare businesses, or find relationships — without leaving the editor.

The directory covers companies, startups, agencies, organizations, products, services, and publishers, with ownership verification, confidence scores, and a relationship graph.

## Free vs Pro

**Free** — no key required. Connect and use:

* Search listings by name, category, country, city, or verification status
* Read public company profiles
* Check verification status and confidence score
* Compare two to four companies side by side
* Prepare listing submission links

**Pro** — requires an API key from https://firmledger.co.ke/dashboard/developer

* Contact details (website, email, phone, social links) on every profile
* The relationship graph — founders, investors, parents, subsidiaries, products, services, partners
* Moderated company news
* Job search
* Domain lookup ("is this site on FirmLedger?")
* Account tools: your listings, analytics, leads, watchlist, notifications, tickets

Pro also adds account actions — replying to leads, managing your watchlist, posting jobs — each requiring your explicit confirmation before it runs.

## Install

Install through the Cursor Marketplace. To add it manually, put this in your Cursor MCP config:

```json
{
  "mcpServers": {
    "firmledger": {
      "url": "https://mcp.firmledger.co.ke/mcp"
    }
  }
}
```

For Pro access, replace the URL with your personal connector link from https://firmledger.co.ke/dashboard/developer — it embeds your key.

## Example prompts

* "Search FirmLedger for verified fintech companies in Nairobi."
* "Is Acme Pay verified on FirmLedger?"
* "Compare Acme Pay and Kilimo Soft."
* "Who invested in Acme Pay?"
* "What jobs are open at Acme Pay?"

## Links

* Site: https://firmledger.co.ke
* Docs: https://firmledger.co.ke/docs/mcp
* Technical reference: https://firmledger.co.ke/docs/mcp/reference
* Support: [support@firmledger.co.ke](mailto:support@firmledger.co.ke)

## License

See https://firmledger.co.ke/terms
