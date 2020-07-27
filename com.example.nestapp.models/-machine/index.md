[app](../../index.md) / [com.example.nestapp.models](../index.md) / [Machine](./index.md)

# Machine

`class Machine`

Data model to manage state of the NEST.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Machine()`<br>Data model to manage state of the NEST. |

### Properties

| Name | Summary |
|---|---|
| [isDoorOpen](is-door-open.md) | `var isDoorOpen: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Doors opened or closed. |
| [isOn](is-on.md) | `var isOn: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>System power on or off. |
| [isPadExtended](is-pad-extended.md) | `var isPadExtended: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Pad extended or retracted. |
| [isPadRaised](is-pad-raised.md) | `var isPadRaised: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Pad raised or lowered. |
| [isRoofOpen](is-roof-open.md) | `var isRoofOpen: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Roof opened or closed. |

### Functions

| Name | Summary |
|---|---|
| [fromJsonString](from-json-string.md) | `fun fromJsonString(systemStatus: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Updates state to match state of NEST received as string. |
