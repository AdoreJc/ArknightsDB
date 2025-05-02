# HomeMailArchiveListView

**Namespace:** `Torappu.UI.Home`


## Fields

- `GameObject _panelEmpty`

- `GameObject _panelNotEmpty`

- `HomeMailArchiveListAdapter _listAdapter`

- `LoopVerticalScrollRect _listScrollRect`

- `HomeMailArchiveBarListAdapter _barAdapter`

- `Tween m_cacheTween`

- `Boolean m_hasInited`


## Methods

- `Void Render(HomeMailArchiveViewModel)`

- `Void FocusListToItem(Int32)`

- `Void EventOnScrollValueChanged(Vector2)`

- `Void _ToBarPosWithReset(Int32)`

- `Single <_ToBarPosWithReset>b__12_0()`

- `Void <_ToBarPosWithReset>b__12_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMailArchiveListView : MonoBehaviour, IHotfixable
{
	private const Int32 LIST_NEAR_INDEX_DIST; // 0x0
	private const Single LIST_ITEM_HEIGHT; // 0x0
	private GameObject _panelEmpty; // 0x18
	private GameObject _panelNotEmpty; // 0x20
	private HomeMailArchiveListAdapter _listAdapter; // 0x28
	private LoopVerticalScrollRect _listScrollRect; // 0x30
	private HomeMailArchiveBarListAdapter _barAdapter; // 0x38
	private Tween m_cacheTween; // 0x40
	private Boolean m_hasInited; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_FocusListToItem; // 0x8
	private static DelegateBridge __Hotfix0_EventOnScrollValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__ToBarPosWithReset; // 0x18
	private static DelegateBridge __Hotfix0__CalcIndexFromScrollValue; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2846efc VA: 0x7594e5eefc
	public Void Render(HomeMailArchiveViewModel model) { }
	// RVA: 0x28470a0 VA: 0x7594e5f0a0
	public Void FocusListToItem(Int32 index) { }
	// RVA: 0x2847458 VA: 0x7594e5f458
	public Void EventOnScrollValueChanged(Vector2 value) { }
	// RVA: 0x2847120 VA: 0x7594e5f120
	private Void _ToBarPosWithReset(Int32 index) { }
	// RVA: 0x28475c0 VA: 0x7594e5f5c0
	private static Int32 _CalcIndexFromScrollValue(Single val, Int32 totalCount, Single countInOnePage) { }
	// RVA: 0x2847714 VA: 0x7594e5f714
	public Void .ctor() { }
	// RVA: 0x2847784 VA: 0x7594e5f784
	private Single <_ToBarPosWithReset>b__12_0() { }
	// RVA: 0x28477a0 VA: 0x7594e5f7a0
	private Void <_ToBarPosWithReset>b__12_1(Single val) { }
}
```