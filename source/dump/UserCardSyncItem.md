# UserCardSyncItem

**Namespace:** ` `


## Fields

- `DateTime m_lastUpdateTime`


## Methods

- `Boolean <>xLuaBaseProxy_CheckIfToSyncCustomized(DateTime)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class UserCardSyncItem : CommonSyncServiceItem`2
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

	// RVA: 0x21fdcb0 VA: 0x7594815cb0
	public override TrySyncFrequency get_frequency() { }
	// RVA: 0x21fdd78 VA: 0x7594815d78
	protected override Boolean CheckIfToSyncCustomized(DateTime curTime) { }
	// RVA: 0x21fde20 VA: 0x7594815e20
	public override PlayerSyncModuleMask get_moduleMask() { }
	// RVA: 0x21fde88 VA: 0x7594815e88
	protected override PlayerSyncParam BuildRequestParam() { }
	// RVA: 0x21fdeec VA: 0x7594815eec
	protected override Void FillResponseModel(PlayerSyncStatusViewModel viewModel, PlayerSyncResult result) { }
	// RVA: 0x21fdf6c VA: 0x7594815f6c
	protected override Void HoldResponseModel(PlayerSyncStatusViewModel curModel, PlayerSyncStatusViewModel prevModel) { }
	// RVA: 0x21fc9c8 VA: 0x75948149c8
	public Void .ctor() { }
	// RVA: 0x21fdfec VA: 0x7594815fec
	private Boolean <>xLuaBaseProxy_CheckIfToSyncCustomized(DateTime P0) { }
}
```