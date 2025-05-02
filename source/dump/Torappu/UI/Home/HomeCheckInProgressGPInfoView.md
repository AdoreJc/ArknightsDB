# HomeCheckInProgressGPInfoView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Text _textTitle`

- `Text _textRemainDay`

- `Image _imgIcon`

- `SimpleLayoutContent _content`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `UIStateFinder m_stateFinder`


## Methods

- `Void OnClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCheckInProgressGPInfoView : DataBinder`1, IHotfixable
{
	private Text _textTitle; // 0x20
	private Text _textRemainDay; // 0x28
	private Image _imgIcon; // 0x30
	private SimpleLayoutContent _content; // 0x38
	private Boolean m_hasInited; // 0x40
	private Adapter m_adapter; // 0x48
	private List`1 m_itemDataList; // 0x50
	private UIStateFinder m_stateFinder; // 0x58
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x283153c VA: 0x7594e4953c
	public override Void OnValueChanged(HomeCheckInProperty property) { }
	// RVA: 0x28318a0 VA: 0x7594e498a0
	public Void OnClick() { }
	// RVA: 0x28317d0 VA: 0x7594e497d0
	private Void _InitIfNot() { }
	// RVA: 0x28319d8 VA: 0x7594e499d8
	public Void .ctor() { }
}
```