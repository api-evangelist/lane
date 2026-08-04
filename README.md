# Lane

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

Lane is a workplace experience platform for commercial real estate, now operated as **VTS Activate** after VTS acquired the company. Tenants use a single mobile and web app for keyless building, suite and room access, booking amenities and shared spaces such as meeting rooms, fitness studios and desks, inviting and checking in visitors, receiving building information, maintenance updates and alerts, and RSVPing to events or ordering and paying for retail and food service. Landlords and property managers run it as the tenant-facing layer over the VTS commercial real estate platform.

The legal entity behind the apps is **VTS LANE INC.**, and application traffic on joinlane.com is served by the VTS Activate platform at activate.vts.com.

## API program

**None.** Lane publishes no developer portal, no API documentation, no OpenAPI or AsyncAPI definition, no SDKs, no CLI and no MCP server. The application is backed by an internal GraphQL API that is not publicly documented. `developer.joinlane.com`, `api.joinlane.com`, `docs.joinlane.com`, `developer.vts.com` and `docs.vts.com` do not resolve.

## Links

- Website — https://joinlane.com/
- Application — https://app.joinlane.com/
- Status page — https://status.vts.com/ (the "Activate" component is Lane)
- Privacy policy — https://vts.com/privacy
- iOS app — https://apps.apple.com/us/app/vts-activate/id1049113820
- Android app — https://play.google.com/store/apps/details?id=com.lane.lane

## Artifacts

| Artifact | File |
|---|---|
| Lifecycle | `lifecycle/lane-lifecycle.yml` |
| Authentication (observed) | `authentication/lane-authentication.yml` |
| Domain security | `security/lane-domain-security.yml` |
| Well-known probe record | `well-known/lane-well-known.yml` |
| llms.txt | `llms/lane-llms.txt` |

Backed by: techstars. Acquired by: VTS. Related profile: `all/vts`.
