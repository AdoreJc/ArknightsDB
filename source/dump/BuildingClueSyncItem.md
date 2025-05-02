# BuildingClueSyncItem

**Namespace:** ` `


## Fields

- `DateTime m_lastUpdateTime`


## Methods

- `Boolean <>xLuaBaseProxy_CheckIfToSyncCustomized(DateTime)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class BuildingClueSyncItem : CommonSyncServiceItem`2
{
	private DateTime m_lastUpdateTime; // 0x20
	private static DelegateBridge __Hotfix0_get_frequency; // 0x0
	private static DelegateBridge __Hotfix0_CheckIfToSyncCustomized; // 0x8
	private static DelegateBridge __Hotfix0_get_moduleMask; // 0x10
	private static DelegateBridge __Hotfix0_BuildRequestParam; // 0x18
	private static DelegateBridge __Hotfix0_FillResponseModel; // 0x20
	private static DelegateBridge __Hotfix0_HoldResponseModel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override TrySyncFrequency frequency { get; }
	public override PlayerSyncModuleMask moduleMask { get; }

	// RVA: 0x21fe814 VA: 0x7594816814
	public override TrySyncFrequency get_frequency() { }
	// RVA: 0x21fe8dc VA: 0x75948168dc
	protected override Boolean CheckIfToSyncCustomized(DateTime curTime) { }
	// RVA: 0x21fe984 VA: 0x7594816984
	public override PlayerSyncModuleMask get_moduleMask() { }
	// RVA: 0x21fe9ec VA: 0x75948169ec
	protected override PlayerSyncParam BuildRequestParam() { }
	// RVA: 0x21fea50 VA: 0x7594816a50
	protected override Void FillResponseModel(PlayerSyncStatusViewModel viewModel, PlayerSyncResult result) { }
	// RVA: 0x21fead0 VA: 0x7594816ad0
	protected override Void HoldResponseModel(PlayerSyncStatusViewModel curModel, PlayerSyncStatusViewModel prevModel) { }
	// RVA: 0x21fcb50 VA: 0x7594814b50
	public Void .ctor() { }
	// RVA: 0x21feb50 VA: 0x7594816b50
	private Boolean <>xLuaBaseProxy_CheckIfToSyncCustomized(DateTime P0) { }
}
```