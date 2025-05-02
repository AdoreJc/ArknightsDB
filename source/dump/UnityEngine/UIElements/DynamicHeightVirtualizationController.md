# DynamicHeightVirtualizationController

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Int32 m_HighestCachedIndex`

- `Int32 m_ForcedFirstVisibleItem`

- `Int32 m_ForcedLastVisibleItem`

- `Boolean m_StickToBottom`

- `VirtualizationChange m_LastChange`

- `ScrollDirection m_ScrollDirection`

- `Vector2 m_DelayedScrollOffset`

- `Single m_AccumulatedHeight`

- `Single m_MinimumItemHeight`

- `Action m_FillCallback`

- `Action m_ScrollCallback`

- `Action m_ScrollResetCallback`

- `IVisualElementScheduledItem m_ScheduledItem`

- `IVisualElementScheduledItem m_ScrollScheduledItem`

- `IVisualElementScheduledItem m_ScrollResetScheduledItem`


## Properties

- `Single defaultExpectedHeight`

- `Single contentPadding`

- `Single contentHeight`

- `Int32 anchoredIndex`

- `Single anchorOffset`

- `Single viewportMaxOffset`


## Methods

- `Single get_defaultExpectedHeight()`

- `Single get_contentPadding()`

- `Void set_contentPadding(Single)`

- `Single get_contentHeight()`

- `Void set_contentHeight(Single)`

- `Int32 get_anchoredIndex()`

- `Void set_anchoredIndex(Int32)`

- `Single get_anchorOffset()`

- `Void set_anchorOffset(Single)`

- `Single get_viewportMaxOffset()`

- `Void OnScrollUpdate()`

- `Void CycleItems(Int32)`

- `Boolean NeedsFill()`

- `Void Fill()`

- `Void UpdateScrollViewContainer(Single, Single)`

- `Void ApplyScrollViewUpdate(Boolean)`

- `Void UpdateAnchor()`

- `Void ScheduleFill()`

- `Void ScheduleScroll()`

- `Void ScheduleScrollDirectionReset()`

- `Void ResetScroll()`

- `Int32 GetFirstVisibleItem(Single)`

- `Single GetContentHeightForIndex(Int32)`

- `ContentHeightCacheInfo GetCachedContentHeight(Int32)`

- `Void RegisterItemHeight(Int32, Single)`

- `Void UnregisterItemHeight(Int32)`

- `Void CleanItemHeightCache()`

- `Void OnRecycledItemGeometryChanged(ReusableCollectionItem)`

- `Boolean UpdateRegisteredHeight(ReusableCollectionItem)`

- `Void HideItem(Int32)`

- `Void MarkWaitingForLayout(T)`

- `Boolean IsIndexOutOfBounds(Int32)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class DynamicHeightVirtualizationController`1 : VerticalVirtualizationController`1
{
	private Int32 m_HighestCachedIndex; // 0x0
	private readonly Dictionary`2 m_ItemHeightCache; // 0x0
	private readonly Dictionary`2 m_ContentHeightCache; // 0x0
	private readonly HashSet`1 m_WaitingCache; // 0x0
	private Int32 m_ForcedFirstVisibleItem; // 0x0
	private Int32 m_ForcedLastVisibleItem; // 0x0
	private Boolean m_StickToBottom; // 0x0
	private VirtualizationChange m_LastChange; // 0x0
	private ScrollDirection m_ScrollDirection; // 0x0
	private Vector2 m_DelayedScrollOffset; // 0x0
	private Single m_AccumulatedHeight; // 0x0
	private Single m_MinimumItemHeight; // 0x0
	private Action m_FillCallback; // 0x0
	private Action m_ScrollCallback; // 0x0
	private Action m_ScrollResetCallback; // 0x0
	private Action`1 m_GeometryChangedCallback; // 0x0
	private IVisualElementScheduledItem m_ScheduledItem; // 0x0
	private IVisualElementScheduledItem m_ScrollScheduledItem; // 0x0
	private IVisualElementScheduledItem m_ScrollResetScheduledItem; // 0x0
	private Predicate`1 m_IndexOutOfBoundsPredicate; // 0x0

	private Single defaultExpectedHeight { get; }
	private Single contentPadding { get; set; }
	private Single contentHeight { get; set; }
	private Int32 anchoredIndex { get; set; }
	private Single anchorOffset { get; set; }
	private Single viewportMaxOffset { get; }
	protected override Boolean alwaysRebindOnRefresh { get; }

	// RVA: 0x VA: 0x0
	private Single get_defaultExpectedHeight() { }
	// RVA: 0x VA: 0x0
	private Single get_contentPadding() { }
	// RVA: 0x VA: 0x0
	private Void set_contentPadding(Single value) { }
	// RVA: 0x VA: 0x0
	private Single get_contentHeight() { }
	// RVA: 0x VA: 0x0
	private Void set_contentHeight(Single value) { }
	// RVA: 0x VA: 0x0
	private Int32 get_anchoredIndex() { }
	// RVA: 0x VA: 0x0
	private Void set_anchoredIndex(Int32 value) { }
	// RVA: 0x VA: 0x0
	private Single get_anchorOffset() { }
	// RVA: 0x VA: 0x0
	private Void set_anchorOffset(Single value) { }
	// RVA: 0x VA: 0x0
	private Single get_viewportMaxOffset() { }
	// RVA: 0x VA: 0x0
	protected override Boolean get_alwaysRebindOnRefresh() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(BaseVerticalCollectionView collectionView) { }
	// RVA: 0x VA: 0x0
	public override Void Refresh(Boolean rebuild) { }
	// RVA: 0x VA: 0x0
	public override Void ScrollToItem(Int32 index) { }
	// RVA: 0x VA: 0x0
	public override Void Resize(Vector2 size) { }
	// RVA: 0x VA: 0x0
	public override Void OnScroll(Vector2 scrollOffset) { }
	// RVA: 0x VA: 0x0
	private Void OnScrollUpdate() { }
	// RVA: 0x VA: 0x0
	private Void CycleItems(Int32 firstIndex) { }
	// RVA: 0x VA: 0x0
	private Boolean NeedsFill() { }
	// RVA: 0x VA: 0x0
	private Void Fill() { }
	// RVA: 0x VA: 0x0
	private Void UpdateScrollViewContainer(Single previousHeight, Single newHeight) { }
	// RVA: 0x VA: 0x0
	private Void ApplyScrollViewUpdate(Boolean dimensionsOnly) { }
	// RVA: 0x VA: 0x0
	private Void UpdateAnchor() { }
	// RVA: 0x VA: 0x0
	private Void ScheduleFill() { }
	// RVA: 0x VA: 0x0
	private Void ScheduleScroll() { }
	// RVA: 0x VA: 0x0
	private Void ScheduleScrollDirectionReset() { }
	// RVA: 0x VA: 0x0
	private Void ResetScroll() { }
	// RVA: 0x VA: 0x0
	public override Int32 GetIndexFromPosition(Vector2 position) { }
	// RVA: 0x VA: 0x0
	public override Single GetExpectedItemHeight(Int32 index) { }
	// RVA: 0x VA: 0x0
	private Int32 GetFirstVisibleItem(Single offset) { }
	// RVA: 0x VA: 0x0
	public override Single GetExpectedContentHeight() { }
	// RVA: 0x VA: 0x0
	private Single GetContentHeightForIndex(Int32 lastIndex) { }
	// RVA: 0x VA: 0x0
	private ContentHeightCacheInfo GetCachedContentHeight(Int32 index) { }
	// RVA: 0x VA: 0x0
	private Void RegisterItemHeight(Int32 index, Single height) { }
	// RVA: 0x VA: 0x0
	private Void UnregisterItemHeight(Int32 index) { }
	// RVA: 0x VA: 0x0
	private Void CleanItemHeightCache() { }
	// RVA: 0x VA: 0x0
	private Void OnRecycledItemGeometryChanged(ReusableCollectionItem item) { }
	// RVA: 0x VA: 0x0
	private Boolean UpdateRegisteredHeight(ReusableCollectionItem item) { }
	// RVA: 0x VA: 0x0
	internal override T GetOrMakeItemAtIndex(Int32 activeItemIndex, Int32 scrollViewIndex) { }
	// RVA: 0x VA: 0x0
	internal override Void ReleaseItem(Int32 activeItemsIndex) { }
	// RVA: 0x VA: 0x0
	internal override Void StartDragItem(ReusableCollectionItem item) { }
	// RVA: 0x VA: 0x0
	internal override Void EndDrag(Int32 dropIndex) { }
	// RVA: 0x VA: 0x0
	private Void HideItem(Int32 activeItemsIndex) { }
	// RVA: 0x VA: 0x0
	private Void MarkWaitingForLayout(T item) { }
	// RVA: 0x VA: 0x0
	private Boolean IsIndexOutOfBounds(Int32 i) { }
}
```