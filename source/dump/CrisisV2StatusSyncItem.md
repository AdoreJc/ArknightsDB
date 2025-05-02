# CrisisV2StatusSyncItem

**Namespace:** ` `


## Methods

- `Boolean <>xLuaBaseProxy_CheckIfToSyncCustomized(DateTime)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CrisisV2StatusSyncItem : CommonSyncServiceItem`2
{
	private static DelegateBridge __Hotfix0_get_frequency; // 0x0
	private static DelegateBridge __Hotfix0_get_moduleMask; // 0x8
	private static DelegateBridge __Hotfix0_CheckIfToSyncCustomized; // 0x10
	private static DelegateBridge __Hotfix0_BuildRequestParam; // 0x18
	private static DelegateBridge __Hotfix0_FillResponseModel; // 0x20
	private static DelegateBridge __Hotfix0_HoldResponseModel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override TrySyncFrequency frequency { get; }
	public override PlayerSyncModuleMask moduleMask { get; }

	// RVA: 0x21feed0 VA: 0x7594816ed0
	public override TrySyncFrequency get_frequency() { }
	// RVA: 0x21fef98 VA: 0x7594816f98
	public override PlayerSyncModuleMask get_moduleMask() { }
	// RVA: 0x21ff000 VA: 0x7594817000
	protected override Boolean CheckIfToSyncCustomized(DateTime curTime) { }
	// RVA: 0x21ff100 VA: 0x7594817100
	protected override PlayerSyncParam BuildRequestParam() { }
	// RVA: 0x21ff164 VA: 0x7594817164
	protected override Void FillResponseModel(PlayerSyncStatusViewModel viewModel, PlayerSyncResult result) { }
	// RVA: 0x21ff1e4 VA: 0x75948171e4
	protected override Void HoldResponseModel(PlayerSyncStatusViewModel curModel, PlayerSyncStatusViewModel prevModel) { }
	// RVA: 0x21fcca4 VA: 0x7594814ca4
	public Void .ctor() { }
	// RVA: 0x21ff264 VA: 0x7594817264
	private Boolean <>xLuaBaseProxy_CheckIfToSyncCustomized(DateTime P0) { }
}
```