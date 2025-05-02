# ArchiveEndbookEntryPickerView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `InertiaScrollViewPager _viewPager`

- `UIRecycleLayoutGroup _content`

- `ArchiveEndbookEntryItemView _itemPrefab`

- `Single _minFlingSpd`

- `Single _maxFlingSpd`

- `Boolean m_isInited`

- `PagerAdapter m_adapter`

- `Int32 m_cachedIndex`

- `ArchiveEndbookPickerViewModel m_cachedViewModel`


## Methods

- `Void Render(ArchiveEndbookPickerViewModel, Boolean)`

- `Void Update()`

- `Void _InitIfNot()`

- `Void _InitViewPager()`

- `Void _OnScrollPagerStateChanged(State)`

- `Void _OnPageChangeEnd(Single)`

- `Void _OnpageChangeBegin(Single)`

- `Void _OnItemClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveEndbookEntryPickerView : MonoBehaviour, IHotfixable
{
	private InertiaScrollViewPager _viewPager; // 0x18
	private UIRecycleLayoutGroup _content; // 0x20
	private ArchiveEndbookEntryItemView _itemPrefab; // 0x28
	private Single _minFlingSpd; // 0x30
	private Single _maxFlingSpd; // 0x34
	private Boolean m_isInited; // 0x38
	private PagerAdapter m_adapter; // 0x40
	private Int32 m_cachedIndex; // 0x48
	private List`1 m_maxAttainableFrameList; // 0x50
	private ArchiveEndbookPickerViewModel m_cachedViewModel; // 0x58
	public Action`1 onIndexUpdate; // 0x60
	public Action`1 onIndexConfirm; // 0x68
	public Action`1 onItemClick; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__InitViewPager; // 0x18
	private static DelegateBridge __Hotfix0__OnScrollPagerStateChanged; // 0x20
	private static DelegateBridge __Hotfix0__OnPageChangeEnd; // 0x28
	private static DelegateBridge __Hotfix0__OnpageChangeBegin; // 0x30
	private static DelegateBridge __Hotfix0__OnItemClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x304f3c4 VA: 0x75956673c4
	public Void Render(ArchiveEndbookPickerViewModel pickerViewModel, Boolean isInit) { }
	// RVA: 0x304fa6c VA: 0x7595667a6c
	private Void Update() { }
	// RVA: 0x304f5f0 VA: 0x75956675f0
	private Void _InitIfNot() { }
	// RVA: 0x304fe44 VA: 0x7595667e44
	private Void _InitViewPager() { }
	// RVA: 0x304ffb8 VA: 0x7595667fb8
	private Void _OnScrollPagerStateChanged(State state) { }
	// RVA: 0x3050080 VA: 0x7595668080
	private Void _OnPageChangeEnd(Single index) { }
	// RVA: 0x30501dc VA: 0x75956681dc
	private Void _OnpageChangeBegin(Single index) { }
	// RVA: 0x3050350 VA: 0x7595668350
	private Void _OnItemClick(Int32 index) { }
	// RVA: 0x3050478 VA: 0x7595668478
	public Void .ctor() { }
}
```