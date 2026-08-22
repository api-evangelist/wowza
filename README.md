# Wowza (wowza)

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

Wowza is a Denver, Colorado-based video streaming infrastructure provider that has been simplifying live and on-demand streaming since 2007. The platform spans three flagship products — Wowza Streaming Engine (a self-hosted, on-prem/cloud/edge media server supporting RTMP, RTSP, SRT, WebRTC, HLS, and MPEG-DASH), Wowza Video (a fully managed, cloud-based streaming platform with a v2.0 REST API for live streams, transcoders, stream sources, stream targets, schedules, real-time streams, videos, categories, viewer analytics, ingest data, engagement, popularity, and quality-of-experience monitoring), and Wowza Flowplayer (a commercial-grade HTML5 video player with iOS, tvOS, and Android SDKs, DRM, ad insertion, and 30+ modular plugins). Wowza powers over 200,000 streaming instances across 140 countries, serving security and surveillance, law enforcement, government and defense, sports and live events, smart cities, industrial monitoring, healthcare, and OTT customers. Developer surface includes a public OpenAPI 3.0 specification for Wowza Video, a Swagger-derived OpenAPI 3.0 specification for Wowza Streaming Engine's REST API (default base http://localhost:8087), a Java API for extending Streaming Engine via plugins, a Wowza IDE, Postman collections, and a large public WowzaMediaSystems GitHub organization of plugins, modules, sample apps, and language SDKs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/wowza/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/wowza/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Video
- Streaming
- Live Streaming
- Video On Demand
- Transcoding
- Media Server
- RTMP
- RTSP
- SRT
- WebRTC
- HLS
- MPEG-DASH
- Real-Time Streaming
- Low Latency
- Video Player
- HTML5 Player
- DRM
- CDN
- Video Analytics
- QoE
- Webhooks
- Edge
- Surveillance
- OTT

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Wowza Video REST API

REST API v2.0 (~129 paths) for the Wowza Video cloud platform — manage live streams, transcoders, stream sources, stream targets, schedules, real-time streams, videos, and categories; retrieve viewer metrics, ingest data, engagement, popularity, and quality-of-experience analytics; and access account-level usage statistics. Served from https://api.video.wowza.com/api/v2.0.

- **Human URL:** [https://developer.wowza.com/docs/wowza-video/api/video/openapi](https://developer.wowza.com/docs/wowza-video/api/video/openapi)
- **Base URL:** `https://api.video.wowza.com/api/v2.0`

#### Tags

- Video
- Streaming
- Live Streaming
- Video On Demand
- Transcoders
- Stream Targets
- Real-Time Streaming
- Analytics
- QoE

#### Properties

- [API Reference](https://developer.wowza.com/docs/wowza-video/api/video/openapi)
- [Documentation](https://developer.wowza.com/docs/wowza-video/about-wowza-video/)
- [Documentation](https://developer.wowza.com/docs/wowza-video/api/video/current/overview/)
- [OpenAPI](openapi/wowza-video-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wowza-video.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wowza-video.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://developer.wowza.com/_bundle/docs/wowza-video/api/video/@current/openapi.yaml?download) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Quickstart](https://www.wowza.com/docs/quick-start-for-an-rtmp-live-stream-in-wowza-video)
- [Documentation](https://www.wowza.com/docs/wowza-video-rest-api-lifecycle-management)
- [Documentation](https://www.wowza.com/docs/wowza-video-rest-api)
- [Changelog](https://www.wowza.com/docs/wowza-video-release-notes)

### Wowza Streaming Engine REST API

REST API (~164 paths) for the self-hosted Wowza Streaming Engine media server — manage applications, virtual hosts, stream targets, push publishing, transcoder, server listeners, server users, media cache, server publishers, nDVR recording stores, monitoring, machine stats, licenses, configuration, and webhooks. Served from the local Engine instance (default http://localhost:8087); spec auto-converted from the Engine's native Swagger 1.2 endpoint.

- **Human URL:** [https://www.wowza.com/docs/wowza-streaming-engine-rest-api](https://www.wowza.com/docs/wowza-streaming-engine-rest-api)
- **Base URL:** `http://localhost:8087`

#### Tags

- Streaming
- Media Server
- Self-Hosted
- Applications
- Transcoder
- Webhooks
- Stream Targets
- nDVR
- Media Cache

#### Properties

- [Documentation](https://www.wowza.com/docs/wowza-streaming-engine-rest-api)
- [API Reference](https://www.wowza.com/docs/how-to-access-documentation-for-wowza-streaming-engine-rest-api)
- [Documentation](https://www.wowza.com/docs/how-to-access-wowza-streaming-engine-rest-api-reference-documentation-with-postman)
- [Documentation](https://www.wowza.com/docs/how-to-access-wowza-streaming-engine-swagger-documentation-with-swagger-codegen)
- [OpenAPI](openapi/wowza-streaming-engine-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wowza-streaming-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wowza-streaming-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://developer.wowza.com/_bundle/docs/wowza-engine/rest-api/@current/openapi.yaml?download) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Quickstart](https://www.wowza.com/docs/how-to-install-and-configure-wowza-streaming-engine)
- [SDK](https://github.com/WowzaMediaSystems/wse-rest-library-php)

### Wowza Streaming Engine Java API

Native Java API for extending and customizing the Wowza Streaming Engine media server via server listeners, application modules, HTTP providers, and Media Reader/Writer plugins. The Java API is the foundation for the dozens of open-source WSE plugins published in the WowzaMediaSystems GitHub organization.

- **Human URL:** [https://www.wowza.com/docs/wowza-streaming-engine-java-api-reference-documentation](https://www.wowza.com/docs/wowza-streaming-engine-java-api-reference-documentation)
- **Base URL:** `https://www.wowza.com`

#### Tags

- Streaming
- Media Server
- Java
- Plugins
- SDK

#### Properties

- [API Reference](https://www.wowza.com/docs/wowza-streaming-engine-java-api-reference-documentation)
- [Documentation](https://www.wowza.com/docs/about-the-wowza-streaming-engine-java-api)
- [Documentation](https://www.wowza.com/docs/how-to-extend-wowza-streaming-engine-using-the-wowza-ide)
- [Postman Collection](collections/wowza-streaming-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wowza-streaming-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/wowza-video.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wowza-video.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Wowza Flowplayer

Commercial-grade HTML5 video player with iOS, tvOS, and Android SDKs, DRM (Widevine, FairPlay, PlayReady), ad insertion, real-time streaming at scale plugin support, and 30+ modular plugins. Ships standalone or bundled with Wowza Video subscriptions and integrates with Wowza Streaming Engine.

- **Human URL:** [https://developer.wowza.com/docs/wowza-flowplayer/](https://developer.wowza.com/docs/wowza-flowplayer/)
- **Base URL:** `https://www.wowza.com/video/player`

#### Tags

- Video Player
- HTML5
- HLS
- MPEG-DASH
- DRM
- SDK
- iOS
- Android
- tvOS

#### Properties

- [Documentation](https://developer.wowza.com/docs/wowza-flowplayer/)
- [Portal](https://www.wowza.com/video/player)
- [Documentation](https://flowplayer.com/developers)
- [Postman Collection](collections/wowza-streaming-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wowza-streaming-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/wowza-video.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wowza-video.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Wowza GoCoder SDK

Wowza GoCoder broadcasting SDK for iOS and Android — capture, encode, and stream live video and audio from mobile devices directly to Wowza Streaming Engine or Wowza Video. Official sample repositories on the WowzaMediaSystems GitHub organization demonstrate capture, real-time filters, and Camera2 shader integration.

- **Human URL:** [https://github.com/WowzaMediaSystems/gocoder-sdk-samples-ios](https://github.com/WowzaMediaSystems/gocoder-sdk-samples-ios)
- **Base URL:** `https://www.wowza.com`

#### Tags

- Mobile
- SDK
- iOS
- Android
- Live Streaming
- Capture

#### Properties

- [SDK](https://github.com/WowzaMediaSystems/gocoder-sdk-samples-ios)
- [SDK](https://github.com/WowzaMediaSystems/gocoder-sdk-samples-android)
- [SDK](https://github.com/WowzaMediaSystems/gocoder-sdk-camera2-shaders)
- [Postman Collection](collections/wowza-streaming-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wowza-streaming-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/wowza-video.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wowza-video.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Wowza Real-Time Streaming SDK

WebRTC-based SDK for delivering sub-second-latency live streams at scale through the Wowza Real-Time Streaming service. Public documentation repo and WebRTC sample applications are hosted in the WowzaMediaSystems GitHub organization.

- **Human URL:** [https://github.com/WowzaMediaSystems/wowza-rts-docs](https://github.com/WowzaMediaSystems/wowza-rts-docs)
- **Base URL:** `https://www.wowza.com`

#### Tags

- WebRTC
- Real-Time
- Sub-Second
- SDK
- Live Streaming

#### Properties

- [Documentation](https://github.com/WowzaMediaSystems/wowza-rts-docs)
- [SDK](https://github.com/WowzaMediaSystems/webrtc-examples)
- [Postman Collection](collections/wowza-streaming-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wowza-streaming-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/wowza-video.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wowza-video.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://www.wowza.com)
- [Documentation](https://developer.wowza.com/)
- [Documentation](https://www.wowza.com/docs)
- [Documentation](https://www.wowza.com/docs/wowza-developer-apis-and-sdks)
- [API Reference](https://developer.wowza.com/docs/wowza-video/api/video/openapi)
- [Sign Up](https://www.wowza.com/free-trial)
- [Console](https://cloud.wowza.com/)
- [Pricing](https://www.wowza.com/pricing)
- [Pricing](https://www.wowza.com/pricing/video)
- [Pricing](https://store.wowza.com/)
- [Terms of Service](https://www.wowza.com/legal/terms-of-use)
- [Privacy Policy](https://www.wowza.com/legal/privacy)
- [Status Page](https://status.wowza.com)
- [Support](https://support.wowza.com/hc)
- [Forum](https://www.wowza.com/community/index.html)
- [Blog](https://www.wowza.com/blog)
- [Changelog](https://www.wowza.com/docs/wowza-video-release-notes)
- [About](https://www.wowza.com/about)
- [GitHub Organization](https://github.com/WowzaMediaSystems)
- [SDK](https://github.com/WowzaMediaSystems/wowza-video-api-demos-postman)
- [SDK](https://github.com/WowzaMediaSystems/wse-rest-library-php)
- [SDK](https://github.com/WowzaMediaSystems/wsc-sdk-java)
- [SDK](https://github.com/WowzaMediaSystems/wsc-sdk-ruby)
- [SDK](https://github.com/WowzaMediaSystems/wsc-api-examples-ruby)
- [SDK](https://github.com/WowzaMediaSystems/wowza-streaming-engine-mcp)
- [SDK](https://github.com/WowzaMediaSystems/wowza-video-intelligence-framework)
- [SDK](https://github.com/WowzaMediaSystems/dev-guides)
- [LinkedIn](https://www.linkedin.com/company/wowza-media-systems)
- [Twitter](https://twitter.com/wowzamedia)
- [YouTube](https://www.youtube.com/user/WowzaMediaSystems)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
