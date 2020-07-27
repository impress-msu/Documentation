[app](../../index.md) / [com.example.nestapp.fragments](../index.md) / [PasswordDialogFragment](./index.md)

# PasswordDialogFragment

`class PasswordDialogFragment : DialogFragment`

A fragment that handles password override to server.

### Types

| Name | Summary |
|---|---|
| [OnCompleteListener](-on-complete-listener/index.md) | `interface OnCompleteListener` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `PasswordDialogFragment()`<br>A fragment that handles password override to server. |

### Functions

| Name | Summary |
|---|---|
| [onAttach](on-attach.md) | `fun onAttach(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Attaches fragment to the context (MainActivity), and sets mListener. |
| [onCreate](on-create.md) | `fun onCreate(savedInstanceState: `[`Bundle`](https://developer.android.com/reference/android/os/Bundle.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>When fragment is called, sets mErrorMessage, mLastMessage, and mHideSwitches |
| [onCreateView](on-create-view.md) | `fun onCreateView(inflater: `[`LayoutInflater`](https://developer.android.com/reference/android/view/LayoutInflater.html)`, container: `[`ViewGroup`](https://developer.android.com/reference/android/view/ViewGroup.html)`?, savedInstanceState: `[`Bundle`](https://developer.android.com/reference/android/os/Bundle.html)`?): `[`View`](https://developer.android.com/reference/android/view/View.html)`?`<br>Creates the view of the fragment. |

### Companion Object Functions

| Name | Summary |
|---|---|
| [newInstance](new-instance.md) | `fun newInstance(errorMessage: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, serverMessage: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, hideSwitches: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`PasswordDialogFragment`](./index.md)<br>Sets the default bundle. |
