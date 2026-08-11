# Nosmai Effects SDK for Android

[![Android API 21+](https://img.shields.io/badge/Android-API%2021%2B-green)](https://developer.android.com/about/versions/android-5.0)
[![Version 3.0.1](https://img.shields.io/badge/version-3.0.1-blue)](../../releases/tag/v3.0.1)
[![ABI arm64-v8a](https://img.shields.io/badge/ABI-arm64--v8a-lightgrey)](https://developer.android.com/ndk/guides/abis)

Nosmai Effects SDK brings real-time AR effects, beauty filters, virtual makeup,
face reshaping, background effects, recording, and processed frame output to
Android applications.

## Use cases

- Camera and photo applications
- Social, live-streaming, and video experiences
- Virtual makeup and beauty experiences
- Branded AR effects and interactive campaigns
- Background blur, replacement, and segmentation

## Key features

- GPU-accelerated real-time effects and color filters
- Face-tracked 2D and 3D masks, stickers, particles, and animations
- Adjustable beauty, makeup, and face-reshape controls
- Background blur, solid color, image, video, and authored packages
- Local and cloud-delivered `.nosmai` effect packages
- Filtered video recording and processed output for streaming integrations

## On-device processing

Effects and camera frames are processed on the device for responsive previews.
Internet access may still be required for licensing and cloud-delivered effect
packages.

## Requirements

| Item | Requirement |
| --- | --- |
| SDK version | `3.0.1` |
| Minimum Android version | Android 5.0, API 21 |
| Supported ABI | `arm64-v8a` |
| Java compatibility | Java 11 |
| Native page size | 16 KB compatible |

A valid Nosmai commercial license and license key are required.

## Download

Download `nosmai-sdk-3.0.1.aar` and `SHA256SUMS` from the
[latest GitHub release](https://github.com/nosmai/nosmai_effects_sdk_android/releases/latest).

Verify the downloaded artifact before integration:

```bash
shasum -a 256 -c SHA256SUMS
```

## Documentation

See the [complete Android integration guide](https://nosmai.com/docs/effects/android/)
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
