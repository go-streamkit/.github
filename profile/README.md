# go-streamkit

**Site-agnostic transport for streaming media, in pure Go (CGO=0).**

- [`streamkit`](https://github.com/go-streamkit/streamkit): a retrying,
  rate-limited HTTP client (`httpx`); an HLS playlist parser and writer (`hls`)
  and an MPEG-DASH manifest reader and writer (`dash`). The writers (v0.1.0)
  produce VOD playlists and static MPDs for CMAF/fMP4 and WebVTT segments, such
  as the ones go-avkit's `container.Segment` cuts; live, encoding ladders and
  encryption are not covered.

Website: <https://go-streamkit.github.io> ·
Documentation: <https://go-streamkit.github.io/docs/>
