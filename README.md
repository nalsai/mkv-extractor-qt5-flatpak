# MKV-Extractor-Qt5 Flatpak

📦 Flatpak Package of MKV-Extractor-Qt5 for Linux

<https://github.com/Hizoka76/MKV-Extractor-Qt5>

## Installing

I'm hosting this Flatpak on my own Flatpak Repo. You can install it from there like this:

```bash
flatpak install https://flatpak.nils.moe/com.github.mkv-extractor-qt5.flatpakref
```

You can also install it from the bundle in Releases on GitHub, but you won't get updates that way.

## Building

### Install SDK, Platform and ffmpeg Extension

```bash
flatpak install flathub org.freedesktop.Platform.ffmpeg-full//20.08
flatpak-builder --install-deps-from=flathub --force-clean build-dir com.github.mkv-extractor-qt5.yml
```
