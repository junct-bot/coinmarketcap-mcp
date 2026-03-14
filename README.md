# Coinmarketcap MCP Server

Hosted MCP server for **Coinmarketcap** — giving AI agents direct access to Coinmarketcap analytics data and operations.

> Powered by [Junct](https://junct.dev) — the agent-readiness layer for DeFi.

## Quick Connect

Add to your MCP client config (Claude Desktop, Cursor, Windsurf, etc.):

```json
{
  "mcpServers": {
    "coinmarketcap": {
      "url": "https://coinmarketcap.mcp.junct.dev/mcp"
    }
  }
}
```

**No setup required** — the server is hosted and maintained by Junct.

## Endpoint

| | |
|---|---|
| MCP URL | `https://coinmarketcap.mcp.junct.dev/mcp` |
| Transport | Streamable HTTP |
| Domain | analytics |
| Tools | 30 |
| Docs | [llms.txt](https://coinmarketcap.mcp.junct.dev/llms.txt) |
| OpenAPI | [openapi.json](https://coinmarketcap.mcp.junct.dev/openapi.json) |

## Tools (30)

| Tool | Description |
|---|---|
| `get_v1_cryptocurrency_airdrop` | Airdrop — Returns information about a single airdrop available on CoinMarketCap. Includes the cryptocurrency metadata. 
 |
| `get_v1_cryptocurrency_airdrops` | Airdrops — Returns a list of past, present, or future airdrops which have run on CoinMarketCap.

  **This endpoint is av |
| `get_v1_cryptocurrency_categories` | Categories — Returns information about all coin categories available on CoinMarketCap. Includes a paginated list of cryp |
| `get_v1_cryptocurrency_category` | Category — Returns information about a single coin category available on CoinMarketCap. Includes a paginated list of the |
| `get_v1_cryptocurrency_info` | Metadata — Returns all static metadata available for one or more cryptocurrencies. This information includes details lik |
| `get_v1_cryptocurrency_map` | CoinMarketCap ID Map — Returns a mapping of all cryptocurrencies to unique CoinMarketCap `id`s. Per our <a href="#sectio |
| `get_v1_exchange_info` | Metadata — Returns all static metadata for one or more exchanges. This information includes details like launch date, lo |
| `get_v1_exchange_map` | CoinMarketCap ID Map — Returns a paginated list of all active cryptocurrency exchanges by CoinMarketCap ID. We recommend |
| `get_v1_fiat_map` | CoinMarketCap ID Map — Returns a mapping of all supported fiat currencies to unique CoinMarketCap ids. Per our Best Prac |
| `get_v1_key_info` | Key Info — Returns API key details and usage stats. This endpoint can be used to programmatically monitor your key usage |
| `get_v1_tools_priceconversion` | Price Conversion — Convert an amount of one cryptocurrency or fiat currency into one or more different currencies utiliz |
| `get_v1_blockchain_statistics_latest` | Statistics Latest — Returns the latest blockchain statistics data for 1 or more blockchains. Bitcoin, Litecoin, and Ethe |
| `get_v1_cryptocurrency_listings_historical` | Listings Historical — Returns a ranked and sorted list of all cryptocurrencies for a historical UTC date.  


**Technica |
| `get_v1_cryptocurrency_listings_latest` | Listings Latest — Returns a paginated list of all active cryptocurrencies with latest market data. The default "market_c |
| `get_v1_cryptocurrency_listings_new` | Listings New — Returns a paginated list of most recently added cryptocurrencies.


  **This endpoint is available on the |
| `get_v1_cryptocurrency_marketpairs_latest` | Market Pairs Latest — Lists all active market pairs that CoinMarketCap tracks for a given cryptocurrency or fiat currenc |
| `get_v1_cryptocurrency_ohlcv_historical` | OHLCV Historical — Returns historical OHLCV (Open, High, Low, Close, Volume) data along with market cap for any cryptocu |
| `get_v1_cryptocurrency_ohlcv_latest` | OHLCV Latest — Returns the latest OHLCV (Open, High, Low, Close, Volume) market values for one or more cryptocurrencies  |
| `get_v1_cryptocurrency_priceperformancestats_latest` | Price Performance Stats — Returns price performance statistics for one or more cryptocurrencies including launch price R |
| `get_v1_cryptocurrency_quotes_historical` | Quotes Historical — Returns an interval of historic market quotes for any cryptocurrency based on time and interval para |
| `get_v1_cryptocurrency_quotes_latest` | Quotes Latest — Returns the latest market quote for 1 or more cryptocurrencies. Use the "convert" option to return marke |
| `get_v1_cryptocurrency_trending_gainerslosers` | Trending Gainers & Losers — Returns a paginated list of all trending cryptocurrencies, determined and sorted by the larg |
| `get_v1_cryptocurrency_trending_latest` | Trending Latest — Returns a paginated list of all trending cryptocurrency market data, determined and sorted by CoinMark |
| `get_v1_cryptocurrency_trending_mostvisited` | Trending Most Visited — Returns a paginated list of all trending cryptocurrency market data, determined and sorted by tr |
| `get_v1_exchange_listings_latest` | Listings Latest — Returns a paginated list of all cryptocurrency exchanges including the latest aggregate market data fo |
| `get_v1_exchange_marketpairs_latest` | Market Pairs Latest — Returns all active market pairs that CoinMarketCap tracks for a given exchange. The latest price a |
| `get_v1_exchange_quotes_historical` | Quotes Historical — Returns an interval of historic quotes for any exchange based on time and interval parameters.

**Te |
| `get_v1_exchange_quotes_latest` | Quotes Latest — Returns the latest aggregate market data for 1 or more exchanges. Use the "convert" option to return mar |
| `get_v1_globalmetrics_quotes_historical` | Quotes Historical — Returns an interval of historical global cryptocurrency market metrics based on time and interval pa |
| `get_v1_globalmetrics_quotes_latest` | Quotes Latest — Returns the latest global cryptocurrency market metrics. Use the "convert" option to return market value |

## Links

- [Junct Dashboard](https://junct.dev/servers/coinmarketcap)
- [Server Info](https://coinmarketcap.mcp.junct.dev/)
- [llms.txt](https://coinmarketcap.mcp.junct.dev/llms.txt)
- [agents.md](https://coinmarketcap.mcp.junct.dev/agents.md)
- [MCP Discovery](https://coinmarketcap.mcp.junct.dev/.well-known/mcp/server.json)

---

*This server is automatically generated, hosted, and maintained by [Junct](https://junct.dev).*
