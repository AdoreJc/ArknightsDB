# ActMainSSEntryZonePlugin

**Namespace:** `Torappu.Activity.ActMainSS`


## Fields

- `GameObject _panelActive`

- `GameObject _panelRetro`

- `GameObject _panelLockedTip`

- `Text _textPoint`

- `Text _textLockedTip`

- `UIStringEvent _eventOnJumpToZone`

- `ActMainSSEntryZoneViewModel m_cachedModel`


## Methods

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMainSS
public class ActMainSSEntryZonePlugin : TemplateActivityCommonPlugin, IHotfixable
{
	private GameObject _panelActive; // 0x28
	private GameObject _panelRetro; // 0x30
	private GameObject _panelLockedTip; // 0x38
	private Text _textPoint; // 0x40
	private Text _textLockedTip; // 0x48
	private UIStringEvent _eventOnJumpToZone; // 0x50
	private ActMainSSEntryZoneViewModel m_cachedModel; // 0x58
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x318c948 VA: 0x75957a4948
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x318cb08 VA: 0x75957a4b08
	public Void EventOnClicked() { }
	// RVA: 0x318cc5c VA: 0x75957a4c5c
	public Void .ctor() { }
}
```