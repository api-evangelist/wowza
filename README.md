# Wowza (wowza)

Wowza is a Denver, Colorado-based video streaming infrastructure provider that has been simplifying live and on-demand streaming since 2007. The platform spans three flagship products — **Wowza Streaming Engine** (a self-hosted, on-prem/cloud/edge media server supporting RTMP, RTSP, SRT, WebRTC, HLS, and MPEG-DASH), **Wowza Video** (a fully managed cloud streaming platform with a v2.0 REST API for live streams, transcoders, stream sources, stream targets, schedules, real-time streams, videos, categories, viewer analytics, ingest data, engagement, popularity, and QoE monitoring), and **Wowza Flowplayer** (a commercial-grade HTML5 video player with iOS, tvOS, and Android SDKs, DRM, ad insertion, and 30+ modular plugins). Wowza powers over 200,000 streaming instances across 140 countries, serving security and surveillance, law enforcement, government and defense, sports and live events, smart cities, industrial monitoring, healthcare, and OTT customers.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/wowza/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Video, Streaming, Live Streaming, Video On Demand, Transcoding, Media Server, RTMP, RTSP, SRT, WebRTC, HLS, MPEG-DASH, Real-Time Streaming, Low Latency, Video Player, HTML5 Player, DRM, CDN, Video Analytics, QoE, Webhooks, Edge, Surveillance, OTT

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## Base URL

`https://api.video.wowza.com/api/v2.0` (Wowza Video) and `http://localhost:8087` (default Wowza Streaming Engine REST endpoint).

Sign up for a free trial at [wowza.com/free-trial](https://www.wowza.com/free-trial). The Wowza Video console is available at [cloud.wowza.com](https://cloud.wowza.com/).

## APIs

### Wowza Video REST API
REST API v2.0 (~129 paths) for the Wowza Video cloud platform — manage live streams, transcoders, stream sources, stream targets, schedules, real-time streams, videos, and categories; retrieve viewer metrics, ingest data, engagement, popularity, and quality-of-experience analytics; and access account-level usage statistics. Served from `https://api.video.wowza.com/api/v2.0`.

**Human URL:** [https://developer.wowza.com/docs/wowza-video/api/video/openapi](https://developer.wowza.com/docs/wowza-video/api/video/openapi)

- [API Reference](https://developer.wowza.com/docs/wowza-video/api/video/openapi)
- [Documentation — About Wowza Video](https://developer.wowza.com/docs/wowza-video/about-wowza-video/)
- [Documentation — Wowza Video API Overview](https://developer.wowza.com/docs/wowza-video/api/video/current/overview/)
- [OpenAPI (local)](openapi/wowza-video-openapi.yml)
- [OpenAPI (upstream)](https://developer.wowza.com/_bundle/docs/wowza-video/api/video/@current/openapi.yaml?download)
- [Quickstart — RTMP Live Stream](https://www.wowza.com/docs/quick-start-for-an-rtmp-live-stream-in-wowza-video)
- [REST API Lifecycle Management](https://www.wowza.com/docs/wowza-video-rest-api-lifecycle-management)
- [Release Notes](https://www.wowza.com/docs/wowza-video-release-notes)

### Wowza Streaming Engine REST API
REST API (~164 paths) for the self-hosted Wowza Streaming Engine media server — manage applications, virtual hosts, stream targets, push publishing, transcoder, server listeners, server users, media cache, server publishers, nDVR recording stores, monitoring, machine stats, licenses, configuration, and webhooks. Served from the local Engine instance (default `http://localhost:8087`); spec auto-converted from the Engine's native Swagger 1.2 endpoint.

**Human URL:** [https://www.wowza.com/docs/wowza-streaming-engine-rest-api](https://www.wowza.com/docs/wowza-streaming-engine-rest-api)

- [Documentation](https://www.wowza.com/docs/wowza-streaming-engine-rest-api)
- [API Reference Access](https://www.wowza.com/docs/how-to-access-documentation-for-wowza-streaming-engine-rest-api)
- [Documentation — Postman Access](https://www.wowza.com/docs/how-to-access-wowza-streaming-engine-rest-api-reference-documentation-with-postman)
- [Documentation — Swagger Codegen](https://www.wowza.com/docs/how-to-access-wowza-streaming-engine-swagger-documentation-with-swagger-codegen)
- [OpenAPI (local)](openapi/wowza-streaming-engine-openapi.yml)
- [OpenAPI (upstream)](https://developer.wowza.com/_bundle/docs/wowza-engine/rest-api/@current/openapi.yaml?download)
- [Quickstart — Install and Configure](https://www.wowza.com/docs/how-to-install-and-configure-wowza-streaming-engine)
- [SDK — wse-rest-library-php](https://github.com/WowzaMediaSystems/wse-rest-library-php)

### Wowza Streaming Engine Java API
Native Java API for extending and customizing the Wowza Streaming Engine media server via server listeners, application modules, HTTP providers, and Media Reader/Writer plugins. The Java API is the foundation for the dozens of open-source WSE plugins published in the WowzaMediaSystems GitHub organization.

**Human URL:** [https://www.wowza.com/docs/wowza-streaming-engine-java-api-reference-documentation](https://www.wowza.com/docs/wowza-streaming-engine-java-api-reference-documentation)

- [API Reference](https://www.wowza.com/docs/wowza-streaming-engine-java-api-reference-documentation)
- [Documentation — About the Java API](https://www.wowza.com/docs/about-the-wowza-streaming-engine-java-api)
- [Documentation — Wowza IDE](https://www.wowza.com/docs/how-to-extend-wowza-streaming-engine-using-the-wowza-ide)

### Wowza Flowplayer
Commercial-grade HTML5 video player with iOS, tvOS, and Android SDKs, DRM (Widevine, FairPlay, PlayReady), ad insertion, real-time streaming at scale plugin support, and 30+ modular plugins. Ships standalone or bundled with Wowza Video subscriptions and integrates with Wowza Streaming Engine.

**Human URL:** [https://developer.wowza.com/docs/wowza-flowplayer/](https://developer.wowza.com/docs/wowza-flowplayer/)

- [Documentation](https://developer.wowza.com/docs/wowza-flowplayer/)
- [Portal](https://www.wowza.com/video/player)
- [Flowplayer Developer Docs](https://flowplayer.com/developers)

### Wowza GoCoder SDK
Wowza GoCoder broadcasting SDK for iOS and Android — capture, encode, and stream live video and audio from mobile devices directly to Wowza Streaming Engine or Wowza Video. Official sample repositories on the WowzaMediaSystems GitHub organization demonstrate capture, real-time filters, and Camera2 shader integration.

**Human URL:** [https://github.com/WowzaMediaSystems/gocoder-sdk-samples-ios](https://github.com/WowzaMediaSystems/gocoder-sdk-samples-ios)

- [SDK — iOS Samples](https://github.com/WowzaMediaSystems/gocoder-sdk-samples-ios)
- [SDK — Android Samples](https://github.com/WowzaMediaSystems/gocoder-sdk-samples-android)
- [SDK — Camera2 Shaders](https://github.com/WowzaMediaSystems/gocoder-sdk-camera2-shaders)

### Wowza Real-Time Streaming SDK
WebRTC-based SDK for delivering sub-second-latency live streams at scale through the Wowza Real-Time Streaming service. Public documentation repo and WebRTC sample applications are hosted in the WowzaMediaSystems GitHub organization.

**Human URL:** [https://github.com/WowzaMediaSystems/wowza-rts-docs](https://github.com/WowzaMediaSystems/wowza-rts-docs)

- [Documentation](https://github.com/WowzaMediaSystems/wowza-rts-docs)
- [SDK — WebRTC Examples](https://github.com/WowzaMediaSystems/webrtc-examples)

## Common Properties

- [Portal](https://www.wowza.com)
- [Developer Portal](https://developer.wowza.com/)
- [Documentation](https://www.wowza.com/docs)
- [Developer APIs and SDKs Hub](https://www.wowza.com/docs/wowza-developer-apis-and-sdks)
- [Wowza Video API Reference](https://developer.wowza.com/docs/wowza-video/api/video/openapi)
- [Free Trial / Sign Up](https://www.wowza.com/free-trial)
- [Wowza Video Console](https://cloud.wowza.com/)
- [Pricing](https://www.wowza.com/pricing)
- [Wowza Video Pricing](https://www.wowza.com/pricing/video)
- [Wowza Store](https://store.wowza.com/)
- [Terms of Use](https://www.wowza.com/legal/terms-of-use)
- [Privacy Policy](https://www.wowza.com/legal/privacy)
- [System Status](https://status.wowza.com)
- [Support Center](https://support.wowza.com/hc)
- [Community Forums](https://www.wowza.com/community/index.html)
- [Blog](https://www.wowza.com/blog)
- [Release Notes (Wowza Video)](https://www.wowza.com/docs/wowza-video-release-notes)
- [About Wowza](https://www.wowza.com/about)
- [GitHub Organization — WowzaMediaSystems](https://github.com/WowzaMediaSystems)
- [Postman Collections — Wowza Video API Demos](https://github.com/WowzaMediaSystems/wowza-video-api-demos-postman)
- [SDK — wse-rest-library-php](https://github.com/WowzaMediaSystems/wse-rest-library-php)
- [SDK — wsc-sdk-java (archived)](https://github.com/WowzaMediaSystems/wsc-sdk-java)
- [SDK — wsc-sdk-ruby (archived)](https://github.com/WowzaMediaSystems/wsc-sdk-ruby)
- [SDK — wsc-api-examples-ruby](https://github.com/WowzaMediaSystems/wsc-api-examples-ruby)
- [SDK — Wowza Streaming Engine MCP Server](https://github.com/WowzaMediaSystems/wowza-streaming-engine-mcp)
- [SDK — Wowza Video Intelligence Framework](https://github.com/WowzaMediaSystems/wowza-video-intelligence-framework)
- [SDK — Wowza Developer Guides](https://github.com/WowzaMediaSystems/dev-guides)
- [LinkedIn](https://www.linkedin.com/company/wowza-media-systems)
- [X / Twitter](https://twitter.com/wowzamedia)
- [YouTube](https://www.youtube.com/user/WowzaMediaSystems)

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com
- **X:** [https://x.com/kinlane](https://x.com/kinlane)
