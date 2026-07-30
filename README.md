# Lane

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
