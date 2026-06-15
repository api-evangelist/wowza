# Wowza (wowza)

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
