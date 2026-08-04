# Bird

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Bird (formerly MessageBird) is an omnichannel customer communications platform offering REST APIs for email, SMS, WhatsApp, RCS, push notifications, voice, and data management across customer communication channels. Trusted by more than 450,000 developers, Bird provides enterprise-grade connectivity through a global carrier network alongside a full customer engagement and marketing automation suite.

## APIs

- **Channels API** - Send and receive messages across SMS, WhatsApp, RCS, email, push, and voice via a unified REST interface
- **Customer Data API** - Sync contacts and build 360-degree customer profiles in real time
- **Phone Numbers API** - Search, purchase, and manage phone number inventory
- **Identity Verification API** - Verify customer identities for 2FA and fraud prevention
- **Touchpoints API** - Build dynamic customer journeys and automated flow sequences
- **Accounts API** - Manage organizations, workspaces, users, roles, and access keys

## Links

- **Website**: https://bird.com
- **API Documentation**: https://docs.bird.com/api
- **API Reference**: https://bird.com/en-us/api-reference
- **Developer Hub (legacy)**: https://developers.messagebird.com
- **GitHub**: https://github.com/messagebird
- **OpenAPI Specs**: https://github.com/messagebird/openapi-specs
- **Status Page**: https://status.bird.com
- **Pricing**: https://bird.com/en-us/pricing
- **Blog**: https://bird.com/blog
- **LinkedIn**: https://www.linkedin.com/company/birdhq/
- **X**: https://x.com/messagebird

## Authentication

All API requests use access key authentication via the `Authorization: AccessKey <token>` HTTP header. Access keys are managed at https://app.bird.com/settings/security/access-keys and are scoped to roles for fine-grained permission control.

## SDKs

Official SDKs are available for Java, PHP, Python, Ruby, Go, Node.js, Swift, and Android via the [messagebird GitHub organization](https://github.com/messagebird).
