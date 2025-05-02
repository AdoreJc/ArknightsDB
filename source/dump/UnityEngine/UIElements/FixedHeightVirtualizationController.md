# FixedHeightVirtualizationController

**Namespace:** `UnityEngine.UIElements`


## Properties

- `Single resolvedItemHeight`


## Methods

- `Single get_resolvedItemHeight()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class FixedHeightVirtualizationController`1 : VerticalVirtualizationController`1
{

	private Single resolvedItemHeight { get; }

	// RVA: 0x VA: 0x0
	private Single get_resolvedItemHeight() { }
	// RVA: 0x VA: 0x0
	protected override Boolean VisibleItemPredicate(T i) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(BaseVerticalCollectionView collectionView) { }
	// RVA: 0x VA: 0x0
	public override Int32 GetIndexFromPosition(Vector2 position) { }
	// RVA: 0x VA: 0x0
	public override Single GetExpectedItemHeight(Int32 index) { }
	// RVA: 0x VA: 0x0
	public override Single GetExpectedContentHeight() { }
	// RVA: 0x VA: 0x0
	public override Void ScrollToItem(Int32 index) { }
	// RVA: 0x VA: 0x0
	public override Void Resize(Vector2 size) { }
	// RVA: 0x VA: 0x0
	public override Void OnScroll(Vector2 scrollOffset) { }
	// RVA: 0x VA: 0x0
	internal override T GetOrMakeItemAtIndex(Int32 activeItemIndex, Int32 scrollViewIndex) { }
	// RVA: 0x VA: 0x0
	internal override Void EndDrag(Int32 dropIndex) { }
}
```