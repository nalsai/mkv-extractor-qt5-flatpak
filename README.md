# MKV-Extractor-Qt5 Flatpak

> [!CAUTION]
>
> Replaced by [MKV-Extractor-Qt6-Flatpak](https://github.com/nalsai/MKV-Extractor-Qt6-Flatpak)  
> Therefore this repository is no longer maintained.


📦 Flatpak Package of MKV-Extractor-Qt5 for Linux

<https://github.com/Hizoka76/MKV-Extractor-Qt5>

## Installing

I'm hosting this Flatpak on my own Flatpak Repo. You can install it from there like this:

```bash
flatpak install https://flatpak.nils.moe/repo/appstream/com.github.mkv-extractor-qt5.flatpakref
```

You also need to install the ffmepg extension:

```bash
flatpak install flathub org.freedesktop.Platform.ffmpeg-full//23.08
```

## Building

### Install SDK, Platform and ffmpeg Extension

```bash
flatpak install flathub org.freedesktop.Platform.ffmpeg-full//23.08
flatpak-builder --install-deps-from=flathub --force-clean build-dir com.github.mkv-extractor-qt5.yml
```
