# Royal Mail (royal-mail)

Royal Mail provides a suite of REST APIs for businesses to integrate shipping, tracking, label generation, barcode allocation, and Click & Drop order management directly into their fulfilment systems. APIs cover domestic and international shipment creation, label printing, manifest submission, pre-allocated tracking numbers, offline barcode ranges, local collect options, and delivery office lookup.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/royal-mail/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/royal-mail/refs/heads/main/apis.yml)

## Tags

- Shipping
- Postal Services
- Labels
- Tracking
- Logistics
- Barcodes
- Click and Drop
- UK

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Royal Mail API Shipping V2 (REST)

A fully RESTful service enabling account customers to create domestic and international shipments, produce shipping labels, print customs documents, manifest shipments, pre-allocate tracking numbers, and request offline barcode ranges. Requires an Online Business Account (OBA).

- **Human URL:** [https://developer.royalmail.net/taxonomy/term/91](https://developer.royalmail.net/taxonomy/term/91)
- **Base URL:** `https://api.royalmail.net/shipping/v2`

#### Tags

- Shipping
- Labels
- Manifests
- Barcodes
- International

#### Properties

- [Documentation](https://developer.royalmail.net/taxonomy/term/91)
- [Authentication](https://developer.royalmail.net/start)

### Royal Mail Click & Drop API

REST API for Click & Drop and ChannelShipper customers to import orders, retrieve order details, generate PDF shipping labels, manifest eligible orders, and create return shipments. Supports up to 2,000 orders per request and up to 5 API calls per second.

- **Human URL:** [https://help.parcel.royalmail.com/hc/en-gb/articles/360011462338-Integrating-with-the-Click-Drop-API](https://help.parcel.royalmail.com/hc/en-gb/articles/360011462338-Integrating-with-the-Click-Drop-API)
- **Base URL:** `https://api.parcel.royalmail.com/api/v1`

#### Tags

- Click and Drop
- Orders
- Labels
- Manifests
- Returns

#### Properties

- [Documentation](https://api.parcel.royalmail.com/doc/v1/click-and-drop-api-v1.yaml)
- [OpenAPI](https://api.parcel.royalmail.com/doc/v1/click-and-drop-api-v1.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Royal Mail Tracking V2 (REST)

Allows account customers to receive track-and-trace information for mail items, including current status, delivery history, and proof of delivery for single or multiple items. Intended for server-side application use.

- **Human URL:** [https://developer.royalmail.net/product/175625/api/76888](https://developer.royalmail.net/product/175625/api/76888)
- **Base URL:** `https://api.royalmail.net`

#### Tags

- Tracking
- Delivery
- Proof of Delivery

#### Properties

- [Documentation](https://developer.royalmail.net/product/175625/api/76888)
- [Authentication](https://developer.royalmail.net/start)

### Royal Mail Barcode Allocation V1 (REST)

A RESTful web service that enables API consumers to request a pre-allocated range of Royal Mail barcodes for offline use in shipping processes. No usage costs to customers; development costs are covered by the customer.

- **Human URL:** [https://developer.royalmail.net/taxonomy/term/61](https://developer.royalmail.net/taxonomy/term/61)
- **Base URL:** `https://api.royalmail.net`

#### Tags

- Barcodes
- Offline
- Shipping

#### Properties

- [Documentation](https://developer.royalmail.net/taxonomy/term/61)
- [Authentication](https://developer.royalmail.net/start)

### Royal Mail Local Collect V3 (REST)

Enables customers to benefit from Click and Collect delivery options by retrieving current lists of participating Post Offices and Royal Mail Customer Service Points where tracked and special delivery parcels can be collected. No usage costs to customers.

- **Human URL:** [https://developer.royalmail.net/product](https://developer.royalmail.net/product)
- **Base URL:** `https://api.royalmail.net`

#### Tags

- Local Collect
- Click and Collect
- Post Office
- Locations

#### Properties

- [Documentation](https://developer.royalmail.net/product)
- [Authentication](https://developer.royalmail.net/start)

### Royal Mail Delivery Office Finder V1 (REST)

Enables Royal Mail customers to obtain details of the delivery office dedicated to a provided postcode, including location name, address, available facilities, and opening hours.

- **Human URL:** [https://developer.royalmail.net/product](https://developer.royalmail.net/product)
- **Base URL:** `https://api.royalmail.net`

#### Tags

- Delivery Office
- Locations
- Postcode

#### Properties

- [Documentation](https://developer.royalmail.net/product)
- [Authentication](https://developer.royalmail.net/start)

## Common Properties

- [Portal](https://developer.royalmail.net/)
- [Documentation](https://developer.royalmail.net/api)
- [Getting Started](https://developer.royalmail.net/start)
- [Support](https://developer.royalmail.net/help)
- [Plans](https://developer.royalmail.net/product)
- [Rate Limits](https://developer.royalmail.net/help)
- [Terms of Service](https://developer.royalmail.net/)
- [Authentication](https://developer.royalmail.net/start)
- [Contact](https://developer.royalmail.net/help)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
