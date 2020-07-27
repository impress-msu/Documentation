[app](../../index.md) / [com.example.nestapp.models](../index.md) / [Machine](index.md) / [fromJsonString](./from-json-string.md)

# fromJsonString

`fun fromJsonString(systemStatus: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Updates state to match state of NEST received as string.

### Parameters

`systemStatus` - Status of the NEST.

### Exceptions

`JSONException` - jsonObject is not in correct format or is null.