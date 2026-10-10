# Nosmai Effects SDK for Android

[![Android API 24+](https://img.shields.io/badge/Android-API%2024%2B-green)](https://developer.android.com/about/versions/nougat)
[![Version 3.0.6](https://img.shields.io/badge/version-3.0.6-blue)](../../releases/tag/v3.0.6)
[![ABI arm64-v8a and armeabi-v7a](https://img.shields.io/badge/ABI-arm64--v8a%20%7C%20armeabi--v7a-lightgrey)](https://developer.android.com/ndk/guides/abis)

Nosmai Effects SDK for Android is a real-time Android camera effects SDK for AR
face filters, beauty filters, virtual makeup, face reshaping, background
replacement, interactive camera games, filtered video recording, and live
streaming integrations.

It is designed for native Android camera, social media, video, live streaming,
video chat, virtual makeup, and branded AR applications.

## Main features

| Capability | Android SDK features |
| --- | --- |
| Real-time camera filters | GPU-accelerated preview, LUT filters, color grading, brightness, contrast, hue, saturation, RGB, and white balance |
| Beauty filters | Skin smoothing, skin whitening, sharpening, teeth whitening, and adjustable intensity |
| Virtual makeup | Lipstick, blusher, eyeshadow, eyelashes, eyebrows, and eye color |
| Face reshape | Face slimming plus adjustable eyes, nose, chin, jaw, lips, forehead, and brows |
| AR face effects | Face-tracked 2D and 3D masks, stickers, particles, animations, and protected `.nosmai` packages |
| Background effects | Background segmentation, blur, solid color, image, video, and authored background packages |
| Interactive games | Camera-based `.nosmai` games with tap input, lifecycle controls, and game-event callbacks |
| Local and cloud effects | Bundled packages plus catalog browsing, downloading, caching, applying, and removal |
| Recording and streaming | Filtered video recording plus processed texture and frame output for live-streaming integrations |
| Camera controls | Front and back camera switching, preview lifecycle, active-effect state, and typed removal controls |

## Built for

- Camera and photo applications
- Social, live-streaming, and video experiences
- Virtual makeup and beauty experiences
- Branded AR effects and interactive campaigns
- Interactive camera games and gamified experiences
- Background blur, replacement, and segmentation

## On-device processing

Effects and camera frames are processed on the device for responsive previews.
Internet access may still be required for licensing and cloud-delivered effect
packages.

## Requirements

| Item | Requirement |
| --- | --- |
| SDK version | `3.0.6` |
| Minimum Android version | Android 7.0, API 24 |
| Supported ABIs | `arm64-v8a`, `armeabi-v7a` |
| Java compatibility | Java 11 |
| Native page size | 16 KB compatible |

A valid Nosmai commercial license and license key are required.

## Download

Download `nosmai-sdk-3.0.6.aar` and `SHA256SUMS` from the
[latest GitHub release](https://github.com/nosmai/nosmai_effects_sdk_android/releases/latest).

| Artifact | Size | SHA-256 |
| --- | ---: | --- |
| `nosmai-sdk-3.0.6.aar` | 40,362,644 bytes (38.5 MiB) | `dd08b7de748c7e32846da1cbd46a8213cd3d3093431c89a65738bb9ef1114e06` |

Verify the downloaded artifact before integration:

```bash
shasum -a 256 -c SHA256SUMS
```

## What's new in 3.0.6

- Improved beauty filter quality and visual consistency.
- Added new built-in beauty filters.
- Improved overall performance and runtime stability.

See [CHANGELOG.md](CHANGELOG.md) for release history.

## Documentation

See the [complete Android integration guide](https://nosmai.com/docs/effects/installation/android/)
for installation, permissions, camera lifecycle, effects, recording, streaming,
and troubleshooting.

## Support

Contact Nosmai for commercial licensing, integration assistance, and support.

## License

Nosmai Effects SDK is proprietary commercial software. Public access to this
repository or its release assets does not grant a license to use, modify,
redistribute, sublicense, reverse engineer, or resell the SDK.

See [LICENSE](LICENSE) for the complete proprietary notice. Third-party
components remain subject to their respective license terms.
