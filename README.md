# Albion Labs Token List

Standard [Uniswap tokenlist](https://tokenlists.org/) format for Albion royalty tokens on Base.

## Tokens

| Symbol | Name | Royalty Share | Contract |
|--------|------|---------------|----------|
| ALB-WR1-R1 | Wressle-1 Community Preview | 2.5% of 4.5% | [`0xf836a500...`](https://basescan.org/token/0xf836a500910453A397084ADe41321ee20a5AAde1) |
| ALB-WR1-R2 | Wressle-1 Investor Preview | 7.5% of 4.5% | [`0x1d57246f...`](https://basescan.org/token/0x1d57246fd0ba134d7cc78ddf3ed829379d95f4b7) |

## Usage

### Raindex / DEX Integration

Add to your `settings.yaml`:

```yaml
using-tokens-from:
  - https://raw.githubusercontent.com/albionlabs/tokenlist/main/albion.tokenlist.json
  - https://tokens.coingecko.com/base/all.json
```

### Direct JSON URL

```
https://raw.githubusercontent.com/albionlabs/tokenlist/main/albion.tokenlist.json
```

## Extended Metadata

Each token includes rich metadata in the `extensions` field:

- `underlying` - Physical asset backing the token
- `royaltyShare` - Percentage of royalty stream
- `operator` - Field operator
- `issuer` - Token issuer entity
- `maxSupply` - Maximum token supply
- `exchange` - Primary exchange URL

## Links

- [Albion Exchange](https://albion.exchange)
- [R1 on BaseScan](https://basescan.org/token/0xf836a500910453A397084ADe41321ee20a5AAde1)
- [R2 on BaseScan](https://basescan.org/token/0x1d57246fd0ba134d7cc78ddf3ed829379d95f4b7)
