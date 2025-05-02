# ActivityStatusFixedIntervalSyncItem

**Namespace:** ` `


## Fields

- `Int64 m_lastUpdateTs`


## Methods

- `Boolean <>xLuaBaseProxy_CheckIfToSyncCustomized(DateTime)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ActivityStatusFixedIntervalSyncItem : CommonSyncServiceItem`2
{
	private Int64 m_lastUpdateTs; // 0x20
	private static DelegateBridge __Hotfix0_get_frequency; // 0x0
	private static DelegateBridge __Hotfix0_get_moduleMask; // 0x8
	private static DelegateBridge __Hotfix0_BuildRequestParam; // 0x10
	private static DelegateBridge __Hotfix0_FillResponseModel; // 0x18
	private static DelegateBridge __Hotfix0_HoldResponseModel; // 0x20
	private static DelegateBridge __Hotfix0_CheckIfToSyncCustomized; // 0x28
	private static DelegateBridge __Hotfix0_OnSyncStatusFinished; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override TrySyncFrequency frequency { get; }
	public override PlayerSyncModuleMask moduleMask { get; }

	// RVA: 0x21ff684 VA: 0x7594817684
	public override TrySyncFrequency get_frequency() { }
	// RVA: 0x21ff74c VA: 0x759481774c
	public override PlayerSyncModuleMask get_moduleMask() { }
	// RVA: 0x21ff7b4 VA: 0x75948177b4
	protected override PlayerSyncParam BuildRequestParam() { }
	// RVA: 0x21ff818 VA: 0x7594817818
	protected override Void FillResponseModel(PlayerSyncStatusViewModel viewModel, PlayerSyncResult result) { }
	// RVA: 0x21ff898 VA: 0x7594817898
	protected override Void HoldResponseModel(PlayerSyncStatusViewModel curModel, PlayerSyncStatusViewModel prevModel) { }
	// RVA: 0x21ff918 VA: 0x7594817918
	protected override Boolean CheckIfToSyncCustomized(DateTime curTime) { }
	// RVA: 0x21ffae0 VA: 0x7594817ae0
	public override Void OnSyncStatusFinished(Int64 moduleMask, Int64 curTs) { }
	// RVA: 0x21fcef4 VA: 0x7594814ef4
	public Void .ctor() { }
	// RVA: 0x21ffb80 VA: 0x7594817b80
	private Boolean <>xLuaBaseProxy_CheckIfToSyncCustomized(DateTime P0) { }
}
```