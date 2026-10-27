# SureLive Privacy Policy

Updated October 27, 2026. Applies to the SureLive browser extension (version 0.1.7 and subsequent 0.1.x releases), developed by SureLive Studio.

## Local Data

SureLive processes subtitles, queried words and sentences, playback information and learning settings. Saved items, settings and related media history are stored locally in your browser; media history may include images and audio. Keys or tokens for configured services and optional feature authorization are stored locally and used to authenticate requests to those services. Local Cinema reads video and subtitle files you select. Optional local speech-to-subtitle generation (Local ASR) processes audio locally on your device through a user-installed local helper and does not upload your video or audio files to a SureLive server.

You can delete saved items or clear extension data. Uninstalling the extension or clearing browser data may remove records you have not backed up. Exported files remain in the location you selected.

## Online Requests

- Translation sends relevant subtitle text and language parameters to the selected service, including Google or Microsoft.
- Dictionary lookup sends queried words and language to FreeDictionaryAPI.com or DictionaryAPI.dev. Pronunciation playback may access audio URLs returned by the service.
- Online subtitle search (when initiated by the user, such as via Subdl) sends media query terms and configured API credentials to the selected subtitle service.
- Configured AI sends relevant text, context and request credentials to the configured HTTPS service, such as DeepSeek.
- Optional license or feature verification (when enabled) sends necessary authorization status requests to the verification endpoint.
- Online video and export access the video's website and its subtitle and media services.

These services receive connection information such as IP addresses and apply their own privacy and retention policies. Deleting local records does not delete information already sent to third parties. Do not send sensitive content or use untrusted service endpoints.

## Website Access And Permissions

The extension detects videos, reads available subtitles and displays learning controls on matching websites and embedded frames. Its actual access scope is not limited to the verified websites.

Tab permissions associate videos with user actions. Local storage permissions retain settings, saved items and media history. Context-menu and sidebar permissions support their learning interfaces. Tab audio capture and background documents support user-initiated media recording and export. Native messaging (`nativeMessaging`) communicates exclusively with the optional user-installed local speech-to-subtitle helper on your device. Bilibili media-host and request-rule permissions support the extension's own media requests.

You can manage website access in browser extension settings; restricting access may affect features on those websites.

## Contact

For questions or privacy inquiries, use [SureLive-Public Issues](https://github.com/seagull226/SureLive-Public/issues). Reports are public: do not include keys, account credentials or private media.

[中文](privacy-policy.zh-CN.md) · [Help](support.md)
