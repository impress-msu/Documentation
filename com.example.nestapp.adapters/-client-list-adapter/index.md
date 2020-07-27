[app](../../index.md) / [com.example.nestapp.adapters](../index.md) / [ClientListAdapter](./index.md)

# ClientListAdapter

`class ClientListAdapter : `[`BaseAdapter`](https://developer.android.com/reference/android/widget/BaseAdapter.html)

Takes list of sent and received messages and
adds them to text view (log).

### Parameters

`context` - Context for the activity.

`mListItems` - ArrayList of sent and received messages.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ClientListAdapter(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, mListItems: `[`ArrayList`](https://developer.android.com/reference/java/util/ArrayList.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>)`<br>Takes list of sent and received messages and adds them to text view (log). |

### Functions

| Name | Summary |
|---|---|
| [getCount](get-count.md) | `fun getCount(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Returns the size of the list. |
| [getItem](get-item.md) | `fun getItem(i: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?`<br>Returns null, method unused. |
| [getItemId](get-item-id.md) | `fun getItemId(i: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Returns 0, method unused. |
| [getView](get-view.md) | `fun getView(position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, view: `[`View`](https://developer.android.com/reference/android/view/View.html)`?, viewGroup: `[`ViewGroup`](https://developer.android.com/reference/android/view/ViewGroup.html)`): `[`View`](https://developer.android.com/reference/android/view/View.html)<br>TODO |
