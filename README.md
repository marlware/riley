# Riley
Riley is a homelab media platform for nostalgic home videos. It serves custom Roku and Android TV clients.

- [`riley`](https://github.com/marlware/riley) is the backend repo
- [`riley-roku`](https://github.com/marlware/riley-roku) is the Roku client repo
- [`riley-android-tv`](https://github.com/marlware/riley-android-tv) is the Android TV repo


<img src="/riley-logo.png" alt="Riley logo" width="150">


## Tech stack

Riley is a self-hosted connected-TV streaming platform with...

- clients
  - Roku [`riley-roku`](https://github.com/marlware/riley-roku)
    - BrightScript
    - SceneGraph
  - Android TV [`riley-android-tv`](https://github.com/marlware/riley-android-tv)
    - Kotlin
    - Media3
- backed by a homelab media platform
  - my old laptop with 4GB RAM
- that will implement
  - HLS transcoding
  - content discovery
  - playback-state synchronization
  - thumbnail pipelines
  - quality-of-experience telemetry

for a multi-device family video library.