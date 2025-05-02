# ActivityStatusSyncItem

**Namespace:** ` `


## Fields

- `Int64 m_lastUpdateTs`


## Methods

- `Boolean <>xLuaBaseProxy_CheckIfToSyncCustomized(DateTime)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ActivityStatusSyncItem : CommonSyncServiceItem`2
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

	// RVA: 0x21ff268 VA: 0x7594817268
	public override TrySyncFrequency get_frequency() { }
	// RVA: 0x21ff330 VA: 0x7594817330
	public override PlayerSyncModuleMask get_moduleMask() { }
	// RVA: 0x21ff398 VA: 0x7594817398
	protected override PlayerSyncParam BuildRequestParam() { }
	// RVA: 0x21ff3fc VA: 0x75948173fc
	protected override Void FillResponseModel(PlayerSyncStatusViewModel viewModel, PlayerSyncResult result) { }
	// RVA: 0x21ff47c VA: 0x759481747c
	protected override Void HoldResponseModel(PlayerSyncStatusViewModel curModel, PlayerSyncStatusViewModel prevModel) { }
	// RVA: 0x21ff4fc VA: 0x75948174fc
	protected override Boolean CheckIfToSyncCustomized(DateTime curTime) { }
	// RVA: 0x21ff5e0 VA: 0x75948175e0
	public override Void OnSyncStatusFinished(Int64 moduleMask, Int64 curTs) { }
	// RVA: 0x21fcd34 VA: 0x7594814d34
	public Void .ctor() { }
	// RVA: 0x21ff680 VA: 0x7594817680
	private Boolean <>xLuaBaseProxy_CheckIfToSyncCustomized(DateTime P0) { }
}
```