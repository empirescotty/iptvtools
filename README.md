# IPTVTools

[![PyPI version](https://badge.fury.io/py/iptvtools.svg)](https://badge.fury.io/py/iptvtools)

Scripts currently provided:

- [iptv-filter](https://github.com/huxuan/iptvtools/wiki/iptv%E2%80%90filter)
  - Merge from different resources.
  - Check the tcp/udp connectivity.
  - Filter by custom criteria, e.g. resolution.
  - Match with templates and EPG.
  - Format the url with UDPxy if provided.
  - Unify channels' titles.

Features planned on the road:

- [ ] Scan certain ip and port range to find new channels.
- [ ] Establish a lightweight database for routine maintenance.

Besides, all scripts should be lightweight and able to keep running regularly after proper configuration.

Last but not least, any ideas, comments and suggestions are welcome!

## Prerequisites

To filter by stream information, e.g., resolution/height, [ffmpeg](https://www.ffmpeg.org/) (or [ffprobe](https://www.ffmpeg.org/ffprobe.html) more precisely) is needed, please install according to the [documentation](https://www.ffmpeg.org/download.html).

## Installation

```shell
pip install -U iptvtools
```

## Usage

Please refer to the [wiki](https://github.com/huxuan/iptvtools/wiki) page.
