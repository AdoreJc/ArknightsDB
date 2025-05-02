# SetDatePagerView

**Namespace:** `Torappu.UI`


## Fields

- `InertiaScrollViewPager _wheelPager`

- `UIRecycleLayoutGroup _content`

- `SetDateItemView itemPrefab`

- `Boolean m_isInited`

- `Int64 m_dragContextID`

- `PagerAdapter m_adapter`

- `Int32 m_cachedPage`


## Methods

- `Void Render(SetDateListViewModel, Boolean)`

- `Void Update()`

- `Void _InitIfNot()`

- `Void _ResetScrollIfNecessary(SetDateListViewModel, Boolean)`

- `Void _OnScrollPagerStateChanged(State)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class SetDatePagerView : MonoBehaviour, IHotfixable
{
	private InertiaScrollViewPager _wheelPager; // 0x18
	private UIRecycleLayoutGroup _content; // 0x20
	public Action`1 onItemClicked; // 0x28
	public SetDateItemView itemPrefab; // 0x30
	private Boolean m_isInited; // 0x38
	private Int64 m_dragContextID; // 0x40
	private PagerAdapter m_adapter; // 0x48
	private Int32 m_cachedPage; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__ResetScrollIfNecessary; // 0x18
	private static DelegateBridge __Hotfix0__OnScrollPagerStateChanged; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x223d3e0 VA: 0x75948553e0
	public Void Render(SetDateListViewModel model, Boolean showImmediate) { }
	// RVA: 0x223dbe8 VA: 0x7594855be8
	private Void Update() { }
	// RVA: 0x223d538 VA: 0x7594855538
	private Void _InitIfNot() { }
	// RVA: 0x223db0c VA: 0x7594855b0c
	private Void _ResetScrollIfNecessary(SetDateListViewModel model, Boolean showImmediate) { }
	// RVA: 0x223de60 VA: 0x7594855e60
	private Void _OnScrollPagerStateChanged(State state) { }
	// RVA: 0x223df48 VA: 0x7594855f48
	public Void .ctor() { }
}
```