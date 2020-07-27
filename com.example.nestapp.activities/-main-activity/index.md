[app](../../index.md) / [com.example.nestapp.activities](../index.md) / [MainActivity](./index.md)

# MainActivity

`class MainActivity : AppCompatActivity, `[`OnClickListener`](https://developer.android.com/reference/android/view/View/OnClickListener.html)`, `[`OnCompleteListener`](../../com.example.nestapp.fragments/-password-dialog-fragment/-on-complete-listener/index.md)

The main (and only) activity of the app.
Extends AppCompatActivity and OnClickListener.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MainActivity()`<br>The main (and only) activity of the app. Extends AppCompatActivity and OnClickListener. |

### Functions

| Name | Summary |
|---|---|
| [onClick](on-click.md) | `fun onClick(v: `[`View`](https://developer.android.com/reference/android/view/View.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Handles clicks for activity. |
| [onComplete](on-complete.md) | `fun onComplete(password: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Called when password override fragment completes |
| [onCreate](on-create.md) | `fun onCreate(savedInstanceState: `[`Bundle`](https://developer.android.com/reference/android/os/Bundle.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Called when app is first opened (created). |
| [onPause](on-pause.md) | `fun onPause(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Called when app is minimized. Cancels all remaining requests and stops video. |
| [onStop](on-stop.md) | `fun onStop(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Called when app is closed. Cancels all remaining requests and stops video. |
| [showBurgerPopup](show-burger-popup.md) | `fun showBurgerPopup(v: `[`View`](https://developer.android.com/reference/android/view/View.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Shows burger menu and handles clicks. |
