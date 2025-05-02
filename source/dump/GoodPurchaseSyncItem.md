# GoodPurchaseSyncItem

**Namespace:** ` `


## Fields

- `DateTime m_lastUpdatedTime`


## Methods

- `Boolean <>xLuaBaseProxy_CheckIfToSyncCustomized(DateTime)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class GoodPurchaseSyncItem : CommonSyncServiceItem`2
{
	private const Int64 UPDATE_INTERVAL_SECS; // 0x0
	private DateTime m_lastUpdatedTime; // 0x20
	private static DelegateBridge __Hotfix0_get_frequency; // 0x0
	private static DelegateBridge __Hotfix0_get_moduleMask; // 0x8
	private static DelegateBridge __Hotfix0_CheckIfToSyncCustomized; // 0x10
	private static DelegateBridge __Hotfix0__CheckIfToSync; // 0x18
	private static DelegateBridge __Hotfix0_BuildRequestParam; // 0x20
	private static DelegateBridge __Hotfix0_FillResponseModel; // 0x28
	private static DelegateBridge __Hotfix0_HoldResponseModel; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override TrySyncFrequency frequency { get; }
	public override PlayerSyncModuleMask moduleMask { get; }

	// RVA: 0x21fdff0 VA: 0x7594815ff0
	public override TrySyncFrequency get_frequency() { }
	// RVA: 0x21fe0b8 VA: 0x75948160b8
	public override PlayerSyncModuleMask get_moduleMask() { }
	// RVA: 0x21fe120 VA: 0x7594816120
	protected override Boolean CheckIfToSyncCustomized(DateTime curTime) { }
	// RVA: 0x21fe1b8 VA: 0x75948161b8
	private static Boolean _CheckIfToSync(DateTime curTime, DateTime lastTime) { }
	// RVA: 0x21fe3b8 VA: 0x75948163b8
	protected override PlayerSyncGoodPurchaseParam BuildRequestParam() { }
	// RVA: 0x21fe6d4 VA: 0x75948166d4
	protected override Void FillResponseModel(PlayerSyncStatusViewModel viewModel, PlayerSyncGoodPurchaseResult result) { }
	// RVA: 0x21fe768 VA: 0x7594816768
	protected override Void HoldResponseModel(PlayerSyncStatusViewModel curModel, PlayerSyncStatusViewModel prevModel) { }
	// RVA: 0x21fca8c VA: 0x7594814a8c
	public Void .ctor() { }
	// RVA: 0x21fe810 VA: 0x7594816810
	private Boolean <>xLuaBaseProxy_CheckIfToSyncCustomized(DateTime P0) { }
}
```