# BuildingStatusSyncItem

**Namespace:** ` `


## Methods

- `Boolean <>xLuaBaseProxy_CheckIfToSyncCustomized(DateTime)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class BuildingStatusSyncItem : CommonSyncServiceItem`2
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

	// RVA: 0x21feb54 VA: 0x7594816b54
	public override TrySyncFrequency get_frequency() { }
	// RVA: 0x21fec1c VA: 0x7594816c1c
	public override PlayerSyncModuleMask get_moduleMask() { }
	// RVA: 0x21fec84 VA: 0x7594816c84
	protected override Boolean CheckIfToSyncCustomized(DateTime curTime) { }
	// RVA: 0x21fed68 VA: 0x7594816d68
	protected override PlayerSyncParam BuildRequestParam() { }
	// RVA: 0x21fedcc VA: 0x7594816dcc
	protected override Void FillResponseModel(PlayerSyncStatusViewModel viewModel, PlayerSyncResult result) { }
	// RVA: 0x21fee4c VA: 0x7594816e4c
	protected override Void HoldResponseModel(PlayerSyncStatusViewModel curModel, PlayerSyncStatusViewModel prevModel) { }
	// RVA: 0x21fcc14 VA: 0x7594814c14
	public Void .ctor() { }
	// RVA: 0x21feecc VA: 0x7594816ecc
	private Boolean <>xLuaBaseProxy_CheckIfToSyncCustomized(DateTime P0) { }
}
```