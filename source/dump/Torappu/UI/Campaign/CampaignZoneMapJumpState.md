# CampaignZoneMapJumpState

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `CampaignZoneMapJumpStateBean m_stateBean`

- `CampaignZoneMapJumpView _jumpView`

- `CampaignZoneJumpViewModel m_jumpViewModel`


## Methods

- `Void JumpToStage(CampaignZoneJumpViewModel)`

- `Void <RegisterToDataListener>b__5_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignZoneMapJumpState : PopupFloatState
{
	private CampaignZoneMapJumpStateBean m_stateBean; // 0x70
	private CampaignZoneMapJumpView _jumpView; // 0x78
	private CampaignZoneJumpViewModel m_jumpViewModel; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0_JumpToStage; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2e4ce08 VA: 0x7595464e08
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2e4ce70 VA: 0x7595464e70
	protected override Void OnEnter() { }
	// RVA: 0x2e4d644 VA: 0x7595465644
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2e4d7bc VA: 0x75954657bc
	public Void JumpToStage(CampaignZoneJumpViewModel jumpToViewModel) { }
	// RVA: 0x2e4d854 VA: 0x7595465854
	public Void .ctor() { }
	// RVA: 0x2e4d900 VA: 0x7595465900
	private Void <RegisterToDataListener>b__5_0(IStateBean stateBean) { }
	// RVA: 0x2e4d990 VA: 0x7595465990
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2e4d998 VA: 0x7595465998
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```