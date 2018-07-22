
## HTTP Live Streaming Examples


This repository contains a collection of samples showcasing of [HTTP Live Streaming](https://developer.apple.com/streaming/).

### What's HTTP Live Streaming?

HLS lets you deploy content using ordinary web servers and content delivery networks. HLS is designed for reliability and dynamically adapts to network conditions by optimizing playback for the available speed of wired and wireless connections.

#### Manifest – M3U8

Apple HTTP Live Streaming (HLS) uses an M3U8 playlist as its manifest, typically a variant of a stream is quality of the stream in a specific bitrate and/or resolution. Variant playlists are structured in the following that there is one root M3U8 that references other M3U8s that describe the individual variants (qualities).

### Samples Overview

It’s good to have a variety of streams available when you are testing your adaptive streaming solution to ensure you are covering all aspects of your playback. Below you will find list of publicly available HLS examples, test streams and datasets to help you through your development process.

This repository contains a few categories of samples:

| .m3u8 | EXT-X-KEY | 
| --------|---------| 
| [Skate Phantom 4k](http://sample.vodobox.com/skate_phantom_flex_4k/skate_phantom_flex_4k.m3u8)  | -| 
| [Planete Interdite](http://sample.vodobox.com/planete_interdite_hevc/planete_interdite_hevc.m3u8)  | -| 
| [Pipe Dream Tahiti](http://sample.vodobox.com/pipe_dream_tahiti/pipe_dream_tahiti.m3u8)  | -| 
| [We Are Blood 4k](http://sample.vodobox.com/we_are_blood_4k/we_are_blood_4k.m3u8)  | -| 
| [Caminande 2k](http://sample.vodobox.com/caminandes_3_2k/caminandes_3_2k.m3u8)  | -| 
| [Caminandes 4k](http://sample.vodobox.com/caminandes_1_4k/caminandes_1_4k.m3u8)  | -| 
| [Big Buck Bunny](http://sample.vodobox.com/big_buck_bunny_4k/big_buck_bunny_4k.m3u8)  | -| 
| [Oceans](http://playertest.longtailvideo.com/adaptive/oceans_aes/oceans_aes.m3u8)  | -| 
| [Playlist](http://playertest.longtailvideo.com/adaptive/captions/playlist.m3u8)  | -| 
| [Livestream Metadata](http://playertest.longtailvideo.com/adaptive/wowzaid3/playlist.m3u8)  | -| 
| [Tears of Steel 4k](http://content.jwplatform.com/manifests/vM7nH0Kl.m3u8)  | -| 
| [Artbeats](http://cdn-fms.rbs.com.br/hls-vod/sample1_1500kbps.f4v.m3u8)  | -|

## Apiary API streaming list mock

A REST service that you can use whenever you need some fake data.
It's great for faking a server, sharing code examples, testing your MVP.

 ```bash
https://private-cd8f11-httplivestreaming.apiary-mock.com/streaming
 ```



