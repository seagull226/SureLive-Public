# SureLive Review Guide

Version: 0.1.7. Single purpose: help users learn English and supported target languages (Japanese, French, Spanish, German, Chinese) through video subtitles, sentence seeking and replay, dictionary lookup, vocabulary frequency guidance, saved items and study-card export.

SureLive integrates and customizes [asbplayer](https://github.com/asbplayer/asbplayer) under its MIT license. It is independently maintained by SureLive Studio, not an official asbplayer release. Applicable copyright and license notices accompany the extension. The upstream baseline is commit [`4b29212a`](https://github.com/asbplayer/asbplayer/commit/4b29212afa25d519286b2eeffd8a91dc18572f98), described by Git as `v1.20.0-50-g4b29212a`: a development commit after v1.20.0, not the v1.20.0 release itself.

Interface options include Simplified Chinese, English, Japanese, German, French, Spanish and Russian. Target learning support covers English as well as Japanese, French, Spanish, German and Chinese subtitle analysis and frequency reference.

Verified platforms are listed in the steps below. Inherited website integrations and generic video detection theoretically support additional video websites, but these have not been verified; results depend on the player and subtitle sources.

**Theoretical support — not verified in this release:** Netflix, Amazon Prime Video, Disney+, Hulu, Crunchyroll, TVer, Bandai Channel, U-NEXT, Viki, Max / HBO Max, Twitch, Stremio, Plex, Emby, Jellyfin, and other websites with compatible web players. These may work through inherited website integrations or generic video detection; individual features depend on the player, subtitle sources and website restrictions.

## Steps

1. Install the submitted package and open the SureLive icon and settings. Core learning does not require account registration or a self-hosted server.
2. Open a YouTube, Bilibili or Baidu Netdisk video with available subtitles. Select subtitles, click a sentence to seek, and repeat it.
3. Open Local Cinema and select a browser-playable video with SRT, VTT or ASS subtitles (or use the optional local speech-to-subtitle helper if installed on the local machine). Check playback, sound, subtitles, seeking, speed and fullscreen.
4. Look up and save a word, then reopen Saved to view it.
5. Use export to create an Anki APKG deck. Included media depends on source availability, browser permissions and recording conditions.

Example online page: https://www.youtube.com/watch?v=aP9fXhqI6vI . Video and subtitle availability may change; another subtitled video can be used. Use local media that the reviewer is entitled to use.

## Permission Purposes

| Permission | Purpose |
| --- | --- |
| tabs, activeTab | Identify video tabs and perform user-initiated page and image-capture actions |
| storage, unlimitedStorage | Retain settings, saved items and local image/audio history with quota and eviction protection |
| contextMenus, sidePanel | Subtitle context-menu actions and the native browser sidebar |
| tabCapture, offscreen | User-initiated audio recording, media processing and export |
| nativeMessaging | Communicate with the optional user-installed local speech-to-subtitle helper on the user's device |
| declarativeNetRequestWithHostAccess, bilivideo.com | Set required headers for the extension's own Bilibili media requests |
| All-site, all-frame content scripts | Detect videos/subtitles in pages and embedded players and show learning controls; verified platforms are not the full access scope |

Dictionary, translation, online subtitle search and configured AI services send relevant text online. Custom AI requires the user's service credentials. Local media compatibility depends on the browser's native codec support.

[Privacy policy](privacy-policy.md) · [Third-party notices](THIRD_PARTY_NOTICES.md) · [中文](reviewer-guide.zh-CN.md)
