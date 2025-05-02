# OpenServerV2TotalCheckinView

**Namespace:** `Torappu.UI.Home.Activity`


## Fields

- `Text _txtDesc`

- `SimpleLayoutContent _itemLayoutContent`

- `SimpleLayoutContent _charLayoutContent`

- `ScrollRect _scrollRect`

- `GridLayoutGroup _layout`

- `UILayoutDimensionListener _listener`

- `UIStateFinder m_stateFinder`

- `OpenServerV2TotalCheckinViewModel m_viewModel`

- `CharBlockAdapter m_adapter`

- `TotalLoginAdapter m_itemAdapter`

- `Boolean m_isInited`

- `Tween m_cachedTween`


## Methods

- `Void _InitIfNot()`

- `Void _OnItemClick(Int32)`

- `Void _OnCharClick(Int32)`

- `Void _FocusToItem(Int32, Int32)`

- `Single <_FocusToItem>b__20_0()`

- `Void <_FocusToItem>b__20_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Activity
public class OpenServerV2TotalCheckinView : OpenServerV2FuncAbstractView
{
	private const Single FOCUS_DURATION; // 0x0
	private Text _txtDesc; // 0x18
	private SimpleLayoutContent _itemLayoutContent; // 0x20
	private SimpleLayoutContent _charLayoutContent; // 0x28
	private ScrollRect _scrollRect; // 0x30
	private GridLayoutGroup _layout; // 0x38
	private UILayoutDimensionListener _listener; // 0x40
	private UIStateFinder m_stateFinder; // 0x48
	private OpenServerV2TotalCheckinViewModel m_viewModel; // 0x58
	private CharBlockAdapter m_adapter; // 0x60
	private TotalLoginAdapter m_itemAdapter; // 0x68
	private Boolean m_isInited; // 0x70
	private Tween m_cachedTween; // 0x78
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__OnItemClick; // 0x10
	private static DelegateBridge __Hotfix0__OnCharClick; // 0x18
	private static DelegateBridge __Hotfix0__FocusToItem; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2856ed4 VA: 0x7594e6eed4
	public override Void Render(OpenServerV2MainViewModel viewModel, Boolean isInit) { }
	// RVA: 0x285710c VA: 0x7594e6f10c
	private Void _InitIfNot() { }
	// RVA: 0x285749c VA: 0x7594e6f49c
	private Void _OnItemClick(Int32 index) { }
	// RVA: 0x28575a8 VA: 0x7594e6f5a8
	private Void _OnCharClick(Int32 index) { }
	// RVA: 0x285771c VA: 0x7594e6f71c
	private Void _FocusToItem(Int32 targetIndex, Int32 totalCount) { }
	// RVA: 0x2857a08 VA: 0x7594e6fa08
	public Void .ctor() { }
	// RVA: 0x2857a74 VA: 0x7594e6fa74
	private Single <_FocusToItem>b__20_0() { }
	// RVA: 0x2857a90 VA: 0x7594e6fa90
	private Void <_FocusToItem>b__20_1(Single val) { }
}
```