# RL04FragmentCharSelectDialog

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Text _textSelect`

- `Text _textWeightLimit`

- `GameObject _panelEmpty`

- `GameObject _panelNotEmpty`

- `RL04FragmentCharSelectListAdapter _adapter`

- `GameObject _panelScrollbar`

- `RL04FragmentCharSelectModel m_viewModel`

- `Boolean m_hasConfirmed`


## Methods

- `Void _Render()`

- `Void _OnCharCardClicked(Int32)`

- `Void _SendFragmentSelectCharRequest()`

- `Void _OnFragmentSelectCharResponse(RL04SetFragmentCharResponse)`

- `Void EventOnBackBtnClicked()`

- `Void EventOnConfirmClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentCharSelectDialog : UICompDialog`1
{
	private static readonly List`1 PROFESSION_ORDER_LIST; // 0x0
	private Text _textSelect; // 0x48
	private Text _textWeightLimit; // 0x50
	private GameObject _panelEmpty; // 0x58
	private GameObject _panelNotEmpty; // 0x60
	private RL04FragmentCharSelectListAdapter _adapter; // 0x68
	private GameObject _panelScrollbar; // 0x70
	private RL04FragmentCharSelectModel m_viewModel; // 0x78
	private List`1 m_cachedSelectedChar; // 0x80
	private Boolean m_hasConfirmed; // 0x88
	private static DelegateBridge __Hotfix0__Render; // 0x8
	private static DelegateBridge __Hotfix0__OnCharCardClicked; // 0x10
	private static DelegateBridge __Hotfix0__SendFragmentSelectCharRequest; // 0x18
	private static DelegateBridge __Hotfix0__OnFragmentSelectCharResponse; // 0x20
	private static DelegateBridge __Hotfix0_OnRender; // 0x28
	private static DelegateBridge __Hotfix0_EventOnBackBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2b1d1a8 VA: 0x75951351a8
	private Void _Render() { }
	// RVA: 0x2b1d71c VA: 0x759513571c
	private Void _OnCharCardClicked(Int32 index) { }
	// RVA: 0x2b1d9d0 VA: 0x75951359d0
	private Void _SendFragmentSelectCharRequest() { }
	// RVA: 0x2b1dd10 VA: 0x7595135d10
	private Void _OnFragmentSelectCharResponse(RL04SetFragmentCharResponse response) { }
	// RVA: 0x2b1de20 VA: 0x7595135e20
	protected override Void OnRender(Options input) { }
	// RVA: 0x2b1e308 VA: 0x7595136308
	public Void EventOnBackBtnClicked() { }
	// RVA: 0x2b1e3c4 VA: 0x75951363c4
	public Void EventOnConfirmClicked() { }
	// RVA: 0x2b1e460 VA: 0x7595136460
	public Void .ctor() { }
	// RVA: 0x2b1e554 VA: 0x7595136554
	private static Void .cctor() { }
}
```