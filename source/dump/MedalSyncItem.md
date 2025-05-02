# MedalSyncItem

**Namespace:** ` `


## Fields

- `Int64 m_lastSyncTs`


## Methods

- `Boolean <>xLuaBaseProxy_CheckIfToSyncCustomized(DateTime)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MedalSyncItem : CommonSyncServiceItem`2
{
	private Int64 m_lastSyncTs; // 0x20
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

	// RVA: 0x21ffb84 VA: 0x7594817b84
	public override TrySyncFrequency get_frequency() { }
	// RVA: 0x21ffc4c VA: 0x7594817c4c
	public override PlayerSyncModuleMask get_moduleMask() { }
	// RVA: 0x21ffcb4 VA: 0x7594817cb4
	protected override PlayerSyncParam BuildRequestParam() { }
	// RVA: 0x21ffd18 VA: 0x7594817d18
	protected override Void FillResponseModel(PlayerSyncStatusViewModel viewModel, PlayerSyncResult result) { }
	// RVA: 0x21ffd98 VA: 0x7594817d98
	protected override Void HoldResponseModel(PlayerSyncStatusViewModel curModel, PlayerSyncStatusViewModel prevModel) { }
	// RVA: 0x21ffe18 VA: 0x7594817e18
	protected override Boolean CheckIfToSyncCustomized(DateTime curTime) { }
	// RVA: 0x21ffeec VA: 0x7594817eec
	public override Void OnSyncStatusFinished(Int64 moduleMask, Int64 curTs) { }
	// RVA: 0x21fcdcc VA: 0x7594814dcc
	public Void .ctor() { }
	// RVA: 0x21fff70 VA: 0x7594817f70
	private Boolean <>xLuaBaseProxy_CheckIfToSyncCustomized(DateTime P0) { }
}
```