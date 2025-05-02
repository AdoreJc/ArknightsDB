# ArchiveQuestListView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `GameObject _mainPanel`

- `GameObject _sidePanel`

- `LoopScrollRect _loopRect`

- `ArchiveQuestListLoopAdapter _loopAdapter`

- `GridLayoutGroup _loopLayout`

- `CanvasGroup _loopGroup`

- `Single _focusDuration`

- `Boolean m_hasInited`

- `Int32 m_cachedFocusIndex`

- `Tween m_focusTween`


## Methods

- `Void set_itemSelectEvent(Action`1)`

- `Void InitItems(SandboxV2ArchiveQuestType, List`1)`

- `Void UpdateItems(Int32)`

- `Void _SetFirstAndLast()`

- `Void _GenerateMainItems(List`1)`

- `Void _GenerateSideItems(List`1)`

- `ViewParam _GenerateItemView(Int32, ArchiveQuestItemModel)`

- `Tween _FocusOnItemIndex(Int32)`

- `Void _InitIfNot()`

- `Single <_FocusOnItemIndex>b__22_3()`

- `Void <_FocusOnItemIndex>b__22_4(Single)`

- `Single <_FocusOnItemIndex>b__22_5()`

- `Void <_FocusOnItemIndex>b__22_6(Single)`

- `Void <_FocusOnItemIndex>b__22_8()`

- `Single <_FocusOnItemIndex>b__22_0()`

- `Void <_FocusOnItemIndex>b__22_1(Single)`

- `Void <_FocusOnItemIndex>b__22_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveQuestListView : MonoBehaviour, IHotfixable
{
	private const Int32 FOCUS_HALF_RANGE; // 0x0
	private GameObject _mainPanel; // 0x18
	private GameObject _sidePanel; // 0x20
	private LoopScrollRect _loopRect; // 0x28
	private ArchiveQuestListLoopAdapter _loopAdapter; // 0x30
	private GridLayoutGroup _loopLayout; // 0x38
	private CanvasGroup _loopGroup; // 0x40
	private Single _focusDuration; // 0x48
	private Boolean m_hasInited; // 0x4c
	private List`1 m_viewParams; // 0x50
	private Int32 m_cachedFocusIndex; // 0x58
	private Tween m_focusTween; // 0x60
	private Action`1 <itemSelectEvent>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_itemSelectEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_itemSelectEvent; // 0x8
	private static DelegateBridge __Hotfix0_InitItems; // 0x10
	private static DelegateBridge __Hotfix0_UpdateItems; // 0x18
	private static DelegateBridge __Hotfix0__SetFirstAndLast; // 0x20
	private static DelegateBridge __Hotfix0__GenerateMainItems; // 0x28
	private static DelegateBridge __Hotfix0__GenerateSideItems; // 0x30
	private static DelegateBridge __Hotfix0__GenerateItemView; // 0x38
	private static DelegateBridge __Hotfix0__FocusOnItemIndex; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Action`1 itemSelectEvent { get; set; }

	// RVA: 0x3074b3c VA: 0x759568cb3c
	private Action`1 get_itemSelectEvent() { }
	// RVA: 0x30721ac VA: 0x759568a1ac
	public Void set_itemSelectEvent(Action`1 value) { }
	// RVA: 0x3071500 VA: 0x7595689500
	public Void InitItems(SandboxV2ArchiveQuestType type, List`1 items) { }
	// RVA: 0x3071fec VA: 0x7595689fec
	public Void UpdateItems(Int32 focusIndex) { }
	// RVA: 0x30756e8 VA: 0x759568d6e8
	private Void _SetFirstAndLast() { }
	// RVA: 0x3074cbc VA: 0x759568ccbc
	private Void _GenerateMainItems(List`1 items) { }
	// RVA: 0x3074ea4 VA: 0x759568cea4
	private Void _GenerateSideItems(List`1 items) { }
	// RVA: 0x30757a4 VA: 0x759568d7a4
	private ViewParam _GenerateItemView(Int32 index, ArchiveQuestItemModel item) { }
	// RVA: 0x3075054 VA: 0x759568d054
	private Tween _FocusOnItemIndex(Int32 index) { }
	// RVA: 0x3074ba4 VA: 0x759568cba4
	private Void _InitIfNot() { }
	// RVA: 0x307588c VA: 0x759568d88c
	public Void .ctor() { }
	// RVA: 0x30758fc VA: 0x759568d8fc
	private Single <_FocusOnItemIndex>b__22_3() { }
	// RVA: 0x3075918 VA: 0x759568d918
	private Void <_FocusOnItemIndex>b__22_4(Single val) { }
	// RVA: 0x3075934 VA: 0x759568d934
	private Single <_FocusOnItemIndex>b__22_5() { }
	// RVA: 0x3075950 VA: 0x759568d950
	private Void <_FocusOnItemIndex>b__22_6(Single val) { }
	// RVA: 0x307596c VA: 0x759568d96c
	private Void <_FocusOnItemIndex>b__22_8() { }
	// RVA: 0x307598c VA: 0x759568d98c
	private Single <_FocusOnItemIndex>b__22_0() { }
	// RVA: 0x30759a8 VA: 0x759568d9a8
	private Void <_FocusOnItemIndex>b__22_1(Single val) { }
	// RVA: 0x30759c4 VA: 0x759568d9c4
	private Void <_FocusOnItemIndex>b__22_2() { }
}
```