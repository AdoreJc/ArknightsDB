# StageCampaignRuleState

**Namespace:** `Torappu.UI.Stage`


## Fields

- `CampaignRuleView _campaignRuleView`

- `StageCampaignRuleStateBean _stateBean`


## Methods

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageCampaignRuleState : PopupFloatState
{
	private CampaignRuleView _campaignRuleView; // 0x70
	private StageCampaignRuleStateBean _stateBean; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f646d0 VA: 0x759557c6d0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2f64738 VA: 0x759557c738
	protected override Void OnEnter() { }
	// RVA: 0x2f64810 VA: 0x759557c810
	protected override Void OnExit() { }
	// RVA: 0x2f6487c VA: 0x759557c87c
	public Void .ctor() { }
	// RVA: 0x2f648ec VA: 0x759557c8ec
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2f648f4 VA: 0x759557c8f4
	private Void <>xLuaBaseProxy_OnExit() { }
}
```