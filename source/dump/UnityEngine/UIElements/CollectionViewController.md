# CollectionViewController

**Namespace:** `UnityEngine.UIElements`


## Fields

- `BaseVerticalCollectionView m_View`

- `IList m_ItemsSource`

- `Action itemsSourceChanged`


## Properties

- `IList itemsSource`

- `BaseVerticalCollectionView view`


## Methods

- `Void add_itemsSourceChanged(Action)`

- `Void remove_itemsSourceChanged(Action)`

- `Void add_itemIndexChanged(Action`2)`

- `Void remove_itemIndexChanged(Action`2)`

- `IList get_itemsSource()`

- `Void set_itemsSource(IList)`

- `Void SetItemsSourceWithoutNotify(IList)`

- `BaseVerticalCollectionView get_view()`

- `Void SetView(BaseVerticalCollectionView)`

- `Void RaiseItemsSourceChanged()`

- `Void RaiseItemIndexChanged(Int32, Int32)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class CollectionViewController
{
	private BaseVerticalCollectionView m_View; // 0x10
	private IList m_ItemsSource; // 0x18
	private Action itemsSourceChanged; // 0x20
	private Action`2 itemIndexChanged; // 0x28

	public IList itemsSource { get; set; }
	protected BaseVerticalCollectionView view { get; }

	// RVA: 0x699d6ac VA: 0x7598fb56ac
	public Void add_itemsSourceChanged(Action value) { }
	// RVA: 0x699d748 VA: 0x7598fb5748
	public Void remove_itemsSourceChanged(Action value) { }
	// RVA: 0x699d7e4 VA: 0x7598fb57e4
	public Void add_itemIndexChanged(Action`2 value) { }
	// RVA: 0x699d894 VA: 0x7598fb5894
	public Void remove_itemIndexChanged(Action`2 value) { }
	// RVA: 0x699d944 VA: 0x7598fb5944
	public IList get_itemsSource() { }
	// RVA: 0x699d94c VA: 0x7598fb594c
	public Void set_itemsSource(IList value) { }
	// RVA: 0x699d9a8 VA: 0x7598fb59a8
	protected Void SetItemsSourceWithoutNotify(IList source) { }
	// RVA: 0x699d9b0 VA: 0x7598fb59b0
	protected BaseVerticalCollectionView get_view() { }
	// RVA: 0x699d9b8 VA: 0x7598fb59b8
	public Void SetView(BaseVerticalCollectionView view) { }
	// RVA: 0x699da5c VA: 0x7598fb5a5c
	public virtual Int32 GetItemsCount() { }
	// RVA: 0x699db0c VA: 0x7598fb5b0c
	public virtual Int32 GetIndexForId(Int32 id) { }
	// RVA: 0x699db14 VA: 0x7598fb5b14
	public virtual Int32 GetIdForIndex(Int32 index) { }
	// RVA: 0x699db4c VA: 0x7598fb5b4c
	public virtual Object GetItemForIndex(Int32 index) { }
	// RVA: 0x699dc88 VA: 0x7598fb5c88
	internal virtual Void InvokeMakeItem(ReusableCollectionItem reusableItem) { }
	// RVA: 0x699dcc0 VA: 0x7598fb5cc0
	internal virtual Void InvokeBindItem(ReusableCollectionItem reusableItem, Int32 index) { }
	// RVA: 0x699dd8c VA: 0x7598fb5d8c
	internal virtual Void InvokeUnbindItem(ReusableCollectionItem reusableItem, Int32 index) { }
	// RVA: 0x699ddb0 VA: 0x7598fb5db0
	internal virtual Void InvokeDestroyItem(ReusableCollectionItem reusableItem) { }
	// RVA: 0x699ddd4 VA: 0x7598fb5dd4
	public virtual VisualElement MakeItem() { }
	// RVA: 0x699deb0 VA: 0x7598fb5eb0
	protected virtual Void BindItem(VisualElement element, Int32 index) { }
	// RVA: 0x699e080 VA: 0x7598fb6080
	public virtual Void UnbindItem(VisualElement element, Int32 index) { }
	// RVA: 0x699e0b4 VA: 0x7598fb60b4
	public virtual Void DestroyItem(VisualElement element) { }
	// RVA: 0x699d98c VA: 0x7598fb598c
	protected Void RaiseItemsSourceChanged() { }
	// RVA: 0x699e0e8 VA: 0x7598fb60e8
	protected Void RaiseItemIndexChanged(Int32 srcIndex, Int32 dstIndex) { }
	// RVA: 0x699e104 VA: 0x7598fb6104
	public Void .ctor() { }
}
```