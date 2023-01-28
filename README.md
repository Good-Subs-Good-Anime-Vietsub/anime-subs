# Some Good Subtitles for Good Anime

## Muxing
Use [MKVToolNix](https://mkvtoolnix.download/)'s "Multiplexer" tab to combine/mux your encode with the relevant ".ass" sub file (required), all fonts (required). Subtitle and Encode must have the **same aspect ratio**. Otherwise, Typesetting part will be displayed in the wrong position.

## Playback
Highly recommended to use mpv for playback since it use [libass](https://github.com/libass/libass) as subtitle renderer. This is [official version](https://mpv.io/), but there are still GUI versions:
- [mpc-qt](https://github.com/mpc-qt/mpc-qt/releases) attempts to replicate the MPC-HC interface while internally running mpv.
- [mpv.net](https://github.com/mpvnet-player/mpv.net/releases)
- [IINA](https://iina.io/) is a macOS-only player.

In addition, [MPC-HC](https://codecguide.com/download_k-lite_codec_pack_mega.htm) (K-Lite) with [XySubfilter](https://github.com/pinterf/xy-VSFilter/releases) is also a good choice.