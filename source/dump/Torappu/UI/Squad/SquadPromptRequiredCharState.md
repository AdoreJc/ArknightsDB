# SquadPromptRequiredCharState

**Namespace:** `Torappu.UI.Squad`


## Fields

- `Text _textRequiredChar`

- `GameObject _goCompleteRequiredChar`

- `Text _textRequiredEvovle`

- `GameObject _goCompleteRequiredEvlove`

- `StateBean m_stateBean`


## Methods

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadPromptRequiredCharState : PopupFloatState
{
	private Text _textRequiredChar; // 0x70
	private GameObject _goCompleteRequiredChar; // 0x78
	private Text _textRequiredEvovle; // 0x80
	private GameObject _goCompleteRequiredEvlove; // 0x88
	private StateBean m_stateBean; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x238aeac VA: 0x75949a2eac
	public override IStateBean GetCacheBean() { }
	// RVA: 0x238af14 VA: 0x75949a2f14
	protected override Void OnEnter() { }
	// RVA: 0x238b0e0 VA: 0x75949a30e0
	protected override Void OnExit() { }
	// RVA: 0x238b250 VA: 0x75949a3250
	public Void .ctor() { }
	// RVA: 0x238b36c VA: 0x75949a336c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x238b374 VA: 0x75949a3374
	private Void <>xLuaBaseProxy_OnExit() { }
}
```