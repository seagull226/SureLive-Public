# SureLive Review Guide

Version: 0.1.6. Single purpose: help users learn English through video subtitles, sentence seeking and replay, dictionary lookup, saved items and study-card export.

## Steps

1. Install the submitted package and open the SureLive icon and settings. Core learning does not require account registration or a self-hosted server.
2. Open a YouTube, Bilibili or Baidu Netdisk video with available subtitles. Select subtitles, click a sentence to seek, and repeat it.
3. Open Local Cinema and select an Edge-playable video with SRT, VTT or ASS subtitles. Check playback, sound, subtitles, seeking, speed and fullscreen.
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
| declarativeNetRequestWithHostAccess, bilivideo.com | Set required headers for the extension's own Bilibili media requests |
| All-site, all-frame content scripts | Detect videos/subtitles in pages and embedded players and show learning controls; verified platforms are not the full access scope |

Dictionary, translation and configured AI services send relevant text online. Custom AI requires the user's service credentials. Local media compatibility depends on Edge's native codec support.

[Privacy policy](privacy-policy.md) · [Third-party notices](THIRD_PARTY_NOTICES.DRAFT.md) · [中文](reviewer-guide.zh-CN.md)
