# CampaignMissionState

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `CampaignMissionView _view`

- `Boolean m_inited`

- `CampaignMissionStateBean m_stateBean`


## Methods

- `Void EventOnJumpToRotateClicked()`

- `Void EventOnBackClicked()`

- `Void _EventOnPermanentObjClicked(CampaignPermanentMissionViewModel)`

- `Void _EventOnCommonObjClicked(CampaignCommonMissionViewModel)`

- `Void _InitIfNot()`

- `Void <_EventOnCommonObjClicked>b__8_0(CampaignGetCommonMissionRewardResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignMissionState : PopupFloatState
{
	private CampaignMissionView _view; // 0x70
	private Boolean m_inited; // 0x78
	private CampaignMissionStateBean m_stateBean; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_EventOnJumpToRotateClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBackClicked; // 0x18
	private static DelegateBridge __Hotfix0__EventOnPermanentObjClicked; // 0x20
	private static DelegateBridge __Hotfix0__EventOnCommonObjClicked; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2dce538 VA: 0x75953e6538
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2dce5a0 VA: 0x75953e65a0
	protected override Void OnEnter() { }
	// RVA: 0x2dcec18 VA: 0x75953e6c18
	public Void EventOnJumpToRotateClicked() { }
	// RVA: 0x2dced10 VA: 0x75953e6d10
	public Void EventOnBackClicked() { }
	// RVA: 0x2dced7c VA: 0x75953e6d7c
	private Void _EventOnPermanentObjClicked(CampaignPermanentMissionViewModel permanentMission) { }
	// RVA: 0x2dcee7c VA: 0x75953e6e7c
	private Void _EventOnCommonObjClicked(CampaignCommonMissionViewModel commonMission) { }
	// RVA: 0x2dce634 VA: 0x75953e6634
	private Void _InitIfNot() { }
	// RVA: 0x2dcf1ec VA: 0x75953e71ec
	public Void .ctor() { }
	// RVA: 0x2dcf3ac VA: 0x75953e73ac
	private Void <_EventOnCommonObjClicked>b__8_0(CampaignGetCommonMissionRewardResponse response) { }
	// RVA: 0x2dcf57c VA: 0x75953e757c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```