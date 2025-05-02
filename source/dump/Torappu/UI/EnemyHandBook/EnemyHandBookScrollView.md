# EnemyHandBookScrollView

**Namespace:** `Torappu.UI.EnemyHandBook`


## Fields

- `EnemyHandBookScrollListAdapter _listAdapter`

- `LoopVerticalScrollRect _scrollRect`

- `EnemyHandBookDetailView _detailView`

- `GridLayoutGroup _layoutGroup`

- `GameObject _emptyPart`

- `GameObject _emptyView`

- `Boolean m_hasInited`

- `Int32 m_rowCount`

- `Tween m_cachedTween`

- `ShufflePatch m_patch`

- `Boolean <needScroll>k__BackingField`


## Properties

- `Boolean needScroll`


## Methods

- `Boolean get_needScroll()`

- `Void set_needScroll(Boolean)`

- `Void set_onSelectedChanged(Action`1)`

- `Void _ScrollToSelection(Int32, Boolean)`

- `Void _InitIfNot()`

- `Void _OnItemClick(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyHandBook
public class EnemyHandBookScrollView : DataBinder`1
{
	private const Single FOCUS_DURATION; // 0x0
	private const Int32 SLIDE_MAX_ROW; // 0x0
	private EnemyHandBookScrollListAdapter _listAdapter; // 0x20
	private LoopVerticalScrollRect _scrollRect; // 0x28
	private EnemyHandBookDetailView _detailView; // 0x30
	private GridLayoutGroup _layoutGroup; // 0x38
	private GameObject _emptyPart; // 0x40
	private GameObject _emptyView; // 0x48
	private Boolean m_hasInited; // 0x50
	private Int32 m_rowCount; // 0x54
	private Tween m_cachedTween; // 0x58
	private ShufflePatch m_patch; // 0x60
	private Boolean <needScroll>k__BackingField; // 0x68
	private Action`1 <onSelectedChanged>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_needScroll; // 0x0
	private static DelegateBridge __Hotfix0_set_needScroll; // 0x8
	private static DelegateBridge __Hotfix0_get_onSelectedChanged; // 0x10
	private static DelegateBridge __Hotfix0_set_onSelectedChanged; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0__ScrollToSelection; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__OnItemClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Boolean needScroll { get; set; }
	private Action`1 onSelectedChanged { get; set; }

	// RVA: 0x293711c VA: 0x7594f4f11c
	public Boolean get_needScroll() { }
	// RVA: 0x2937184 VA: 0x7594f4f184
	public Void set_needScroll(Boolean value) { }
	// RVA: 0x2937204 VA: 0x7594f4f204
	private Action`1 get_onSelectedChanged() { }
	// RVA: 0x293726c VA: 0x7594f4f26c
	public Void set_onSelectedChanged(Action`1 value) { }
	// RVA: 0x29372f0 VA: 0x7594f4f2f0
	public override Void OnValueChanged(EnemyHandBookShowProperty property) { }
	// RVA: 0x2937c2c VA: 0x7594f4fc2c
	private Void _ScrollToSelection(Int32 selectIndex, Boolean shufflePatchFlag) { }
	// RVA: 0x2937638 VA: 0x7594f4f638
	private Void _InitIfNot() { }
	// RVA: 0x2937d4c VA: 0x7594f4fd4c
	private Void _OnItemClick(String id) { }
	// RVA: 0x2937e04 VA: 0x7594f4fe04
	public Void .ctor() { }
}
```