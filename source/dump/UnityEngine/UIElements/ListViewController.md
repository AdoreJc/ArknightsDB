# ListViewController

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Action itemsSourceSizeChanged`


## Properties

- `ListView listView`


## Methods

- `Void add_itemsSourceSizeChanged(Action)`

- `Void remove_itemsSourceSizeChanged(Action)`

- `Void add_itemsAdded(Action`1)`

- `Void remove_itemsAdded(Action`1)`

- `Void add_itemsRemoved(Action`1)`

- `Void remove_itemsRemoved(Action`1)`

- `ListView get_listView()`

- `Void RaiseOnSizeChanged()`

- `Void RaiseItemsAdded(IEnumerable`1)`

- `Void RaiseItemsRemoved(IEnumerable`1)`

- `Void Swap(Int32, Int32)`

- `Void EnsureItemSourceCanBeResized()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class ListViewController : CollectionViewController
{
	private Action itemsSourceSizeChanged; // 0x30
	private Action`1 itemsAdded; // 0x38
	private Action`1 itemsRemoved; // 0x40

	private ListView listView { get; }

	// RVA: 0x699e10c VA: 0x7598fb610c
	public Void add_itemsSourceSizeChanged(Action value) { }
	// RVA: 0x699e1a8 VA: 0x7598fb61a8
	public Void remove_itemsSourceSizeChanged(Action value) { }
	// RVA: 0x699e244 VA: 0x7598fb6244
	public Void add_itemsAdded(Action`1 value) { }
	// RVA: 0x699e2f4 VA: 0x7598fb62f4
	public Void remove_itemsAdded(Action`1 value) { }
	// RVA: 0x699e3a4 VA: 0x7598fb63a4
	public Void add_itemsRemoved(Action`1 value) { }
	// RVA: 0x699e454 VA: 0x7598fb6454
	public Void remove_itemsRemoved(Action`1 value) { }
	// RVA: 0x699e504 VA: 0x7598fb6504
	private ListView get_listView() { }
	// RVA: 0x699e580 VA: 0x7598fb6580
	internal override Void InvokeMakeItem(ReusableCollectionItem reusableItem) { }
	// RVA: 0x699ea84 VA: 0x7598fb6a84
	internal override Void InvokeBindItem(ReusableCollectionItem reusableItem, Int32 index) { }
	// RVA: 0x699eb74 VA: 0x7598fb6b74
	public virtual Boolean NeedsDragHandle(Int32 index) { }
	// RVA: 0x699eb7c VA: 0x7598fb6b7c
	public virtual Void AddItems(Int32 itemCount) { }
	// RVA: 0x699f5b4 VA: 0x7598fb75b4
	public virtual Void Move(Int32 index, Int32 newIndex) { }
	// RVA: 0x699f8f8 VA: 0x7598fb78f8
	public virtual Void RemoveItem(Int32 index) { }
	// RVA: 0x699faa8 VA: 0x7598fb7aa8
	public virtual Void RemoveItems(List`1 indices) { }
	// RVA: 0x699febc VA: 0x7598fb7ebc
	internal virtual Void RemoveItems(Int32 itemCount) { }
	// RVA: 0x699f598 VA: 0x7598fb7598
	protected Void RaiseOnSizeChanged() { }
	// RVA: 0x699f57c VA: 0x7598fb757c
	protected Void RaiseItemsAdded(IEnumerable`1 indices) { }
	// RVA: 0x699fea0 VA: 0x7598fb7ea0
	protected Void RaiseItemsRemoved(IEnumerable`1 indices) { }
	// RVA: 0x699f3e4 VA: 0x7598fb73e4
	private static Array AddToArray(Array source, Int32 itemCount) { }
	// RVA: 0x699fcec VA: 0x7598fb7cec
	private static Array RemoveFromArray(Array source, List`1 indicesToRemove) { }
	// RVA: 0x699f700 VA: 0x7598fb7700
	private Void Swap(Int32 lhs, Int32 rhs) { }
	// RVA: 0x699f2cc VA: 0x7598fb72cc
	private Void EnsureItemSourceCanBeResized() { }
	// RVA: 0x69a00b0 VA: 0x7598fb80b0
	public Void .ctor() { }
	// RVA: 0x699f4bc VA: 0x7598fb74bc
	internal static Boolean <AddItems>g__IsGenericList|14_0(Type t) { }
}
```