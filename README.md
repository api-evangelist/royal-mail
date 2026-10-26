# Royal Mail (royal-mail)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
