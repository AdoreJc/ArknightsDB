# OpenServerV2ChainLoginView

**Namespace:** `Torappu.UI.Home.Activity`


## Fields

- `Text _txtDesc`

- `SimpleLayoutContent _itemLayoutContent`

- `SimpleLayoutContent _charLayoutContent`

- `Image _imgBkg`

- `OpenServerV2ChainLoginViewModel m_viewModel`

- `ChainLoginAdapter m_itemAdapter`

- `UIStateFinder m_stateFinder`

- `CharBlockAdapter m_blockAdapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _OnItemClick(Int32)`

- `Void _OnCharClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Activity
public class OpenServerV2ChainLoginView : OpenServerV2FuncAbstractView
{
	private Text _txtDesc; // 0x18
	private SimpleLayoutContent _itemLayoutContent; // 0x20
	private SimpleLayoutContent _charLayoutContent; // 0x28
	private Image _imgBkg; // 0x30
	private OpenServerV2ChainLoginViewModel m_viewModel; // 0x38
	private ChainLoginAdapter m_itemAdapter; // 0x40
	private UIStateFinder m_stateFinder; // 0x48
	private CharBlockAdapter m_blockAdapter; // 0x58
	private Boolean m_isInited; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__OnItemClick; // 0x10
	private static DelegateBridge __Hotfix0__OnCharClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2853828 VA: 0x7594e6b828
	public override Void Render(OpenServerV2MainViewModel viewModel, Boolean isInit) { }
	// RVA: 0x28539f8 VA: 0x7594e6b9f8
	private Void _InitIfNot() { }
	// RVA: 0x2853c44 VA: 0x7594e6bc44
	private Void _OnItemClick(Int32 index) { }
	// RVA: 0x2853d50 VA: 0x7594e6bd50
	public Void _OnCharClick(Int32 index) { }
	// RVA: 0x2853ec4 VA: 0x7594e6bec4
	public Void .ctor() { }
}
```