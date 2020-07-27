[app](../../index.md) / [com.example.nestapp.network](../index.md) / [StreamClient](./index.md)

# StreamClient

`class StreamClient`

Handles all communication with server for displaying
camera videos and landing images.

### Parameters

`c` - Context for the activity.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `StreamClient(c: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`)`<br>Handles all communication with server for displaying camera videos and landing images. |

### Properties

| Name | Summary |
|---|---|
| [imagePort](image-port.md) | `var imagePort: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Server port for landing image feeds. |
| [mWebView](m-web-view.md) | `lateinit var mWebView: `[`WebView`](https://developer.android.com/reference/android/webkit/WebView.html)<br>WebView for stream set in MainActivity. |
| [serverIP](server-i-p.md) | `var serverIP: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Server IP set in MainActivity. |
| [videoPort](video-port.md) | `var videoPort: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Server port for video feeds. |

### Functions

| Name | Summary |
|---|---|
| [startStream](start-stream.md) | `fun startStream(isVideo: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Starts a stream. |
| [stopStream](stop-stream.md) | `fun stopStream(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Stops a stream. |
| [switchStreams](switch-streams.md) | `fun switchStreams(cam: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, isVideo: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Switches to and starts a new stream. |
