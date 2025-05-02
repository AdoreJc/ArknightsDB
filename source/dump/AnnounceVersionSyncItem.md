# AnnounceVersionSyncItem

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AnnounceVersionSyncItem : CommonSyncServiceItem`2
{
	private static DelegateBridge __Hotfix0_get_frequency; // 0x0
	private static DelegateBridge __Hotfix0_get_moduleMask; // 0x8
	private static DelegateBridge __Hotfix0_BuildRequestParam; // 0x10
	private static DelegateBridge __Hotfix0_FillResponseModel; // 0x18
	private static DelegateBridge __Hotfix0_HoldResponseModel; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override TrySyncFrequency frequency { get; }
	public override PlayerSyncModuleMask moduleMask { get; }

	// RVA: 0x21fd9bc VA: 0x75948159bc
	public override TrySyncFrequency get_frequency() { }
	// RVA: 0x21fda84 VA: 0x7594815a84
	public override PlayerSyncModuleMask get_moduleMask() { }
	// RVA: 0x21fdaec VA: 0x7594815aec
	protected override PlayerSyncParam BuildRequestParam() { }
	// RVA: 0x21fdb50 VA: 0x7594815b50
	protected override Void FillResponseModel(PlayerSyncStatusViewModel viewModel, PlayerSyncAnnounceVersionResult result) { }
	// RVA: 0x21fdbf8 VA: 0x7594815bf8
	protected override Void HoldResponseModel(PlayerSyncStatusViewModel curModel, PlayerSyncStatusViewModel prevModel) { }
	// RVA: 0x21fc938 VA: 0x7594814938
	public Void .ctor() { }
}
```