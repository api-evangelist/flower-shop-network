# Flower Shop Network (flower-shop-network)

Flower Shop Network is a platform that connects customers with local florists across the country. They provide an online marketplace where users can browse and purchase a wide variety of floral arrangements for all occasions, including weddings, birthdays, and funerals. Flower Shop Network also exposes a JSON API used by florist POS systems and partners to integrate with the FSN florist network.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/flower-shop-network/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Florists, Flowers, Wire Orders, Point of Sale

## Timestamps

- **Created:** 2025-02-24
- **Modified:** 2026-04-28

## APIs

### Flower Shop Network JSON API

The FSN JSON API is a REST-style HTTPS interface for florist POS systems and partners to authenticate, retrieve product data, search filling florists, and send, receive, accept, refuse, and confirm wire orders. Production base URL `https://api.flowershopnetwork.com/api/`; development base URL `https://dev-api.flowershopnetwork.com/api/`. All requests require a `__token` parameter obtained via `API/ForeignSystem.apiGetPosToken`.

**Human URL:** [https://api.flowershopnetwork.com/](https://api.flowershopnetwork.com/)

#### Tags

- Florists, Flowers, Orders, Wire Orders, Point of Sale

#### Properties

- [Documentation](https://api.flowershopnetwork.com/)
- [OpenAPI](openapi/flower-shop-network-openapi.yml)

## Common Properties

- [Website](https://www.flowershopnetwork.com/)
- [Documentation](https://api.flowershopnetwork.com/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
