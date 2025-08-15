# FFmpeg Kit Binaries

This repository hosts FFmpeg Kit binaries for React Native projects.

## Version
- FFmpeg Kit: 6.0-2
- Package: Audio (LGPL)
- Size: ~151KB (audio-only, much smaller than full 40MB package)

## Usage

Add to your Android project's `android/build.gradle`:

```gradle
allprojects {
    repositories {
        // Add BEFORE other repositories
        maven { 
            url "https://raw.githubusercontent.com/EdifyMedical/ffmpeg-binaries/main/"
        }
        // ... other repositories
    }
}
```

## Repository Structure
```
com/arthenica/ffmpeg-kit-audio/6.0-2/
├── ffmpeg-kit-audio-6.0-2.aar     # Android library
├── ffmpeg-kit-audio-6.0-2.pom     # Maven metadata
└── checksums (md5, sha1)
```

## License
FFmpeg Kit is distributed under LGPL v3.0 which is safe for commercial use.
- You can use this in proprietary apps
- No need to open-source your code
- Must provide FFmpeg license notice to users

## Maintenance
Binary artifacts archived from the last public release before retirement (Jan 6, 2025).