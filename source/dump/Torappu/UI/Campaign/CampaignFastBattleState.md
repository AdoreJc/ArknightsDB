# CampaignFastBattleState

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `Transform _confirmViewHolder`

- `CampaignFastBattleConfirmView _confirmViewPrefab`

- `CampaignFastBattleStateBean m_stateBean`

- `CampaignFastBattleConfirmView m_confirmView`

- `Boolean m_isInited`

- `Boolean m_isBattleStarted`


## Methods

- `Void _OnStartBattleClicked()`

- `Void _OnCancelClicked()`

- `Void _InitIfNot()`

- `Boolean _CheckIfCanFastCampAndAlert()`

- `Void _DoStartFastCamp()`

- `Void _OnFastCampServiceSuc(CampaignFinishBattleResponse, PlayerStatus)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_DealWithOtherStateBeforeTransStart(TransactionContext, Boolean)`

- `Void <>xLuaBaseProxy_DealWithOtherStateWenTransEnd(TransactionContext, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignFastBattleState : PopupFadeState
{
	private Transform _confirmViewHolder; // 0x70
	private CampaignFastBattleConfirmView _confirmViewPrefab; // 0x78
	private CampaignFastBattleStateBean m_stateBean; // 0x80
	private CampaignFastBattleConfirmView m_confirmView; // 0x88
	private Boolean m_isInited; // 0x90
	private Boolean m_isBattleStarted; // 0x91
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__OnStartBattleClicked; // 0x10
	private static DelegateBridge __Hotfix0__OnCancelClicked; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__CheckIfCanFastCampAndAlert; // 0x28
	private static DelegateBridge __Hotfix0__DoStartFastCamp; // 0x30
	private static DelegateBridge __Hotfix0__OnFastCampServiceSuc; // 0x38
	private static DelegateBridge __Hotfix0_DealWithOtherStateBeforeTransStart; // 0x40
	private static DelegateBridge __Hotfix0_DealWithOtherStateWenTransEnd; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2ddc6ac VA: 0x75953f46ac
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ddc714 VA: 0x75953f4714
	protected override Void OnEnter() { }
	// RVA: 0x2ddca04 VA: 0x75953f4a04
	private Void _OnStartBattleClicked() { }
	// RVA: 0x2ddce14 VA: 0x75953f4e14
	private Void _OnCancelClicked() { }
	// RVA: 0x2ddc7ec VA: 0x75953f47ec
	private Void _InitIfNot() { }
	// RVA: 0x2ddcab4 VA: 0x75953f4ab4
	private Boolean _CheckIfCanFastCampAndAlert() { }
	// RVA: 0x2ddcb78 VA: 0x75953f4b78
	private Void _DoStartFastCamp() { }
	// RVA: 0x2ddd038 VA: 0x75953f5038
	private Void _OnFastCampServiceSuc(CampaignFinishBattleResponse response, PlayerStatus statusBeforeBattle) { }
	// RVA: 0x2ddd1dc VA: 0x75953f51dc
	protected override Void DealWithOtherStateBeforeTransStart(TransactionContext context, Boolean isFastMode) { }
	// RVA: 0x2ddd2f0 VA: 0x75953f52f0
	protected override Void DealWithOtherStateWenTransEnd(TransactionContext context, Boolean isFastMode) { }
	// RVA: 0x2ddd404 VA: 0x75953f5404
	public Void .ctor() { }
	// RVA: 0x2ddd55c VA: 0x75953f555c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2ddd564 VA: 0x75953f5564
	private Void <>xLuaBaseProxy_DealWithOtherStateBeforeTransStart(TransactionContext P0, Boolean P1) { }
	// RVA: 0x2ddd590 VA: 0x75953f5590
	private Void <>xLuaBaseProxy_DealWithOtherStateWenTransEnd(TransactionContext P0, Boolean P1) { }
}
```