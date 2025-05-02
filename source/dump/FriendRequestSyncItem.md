# FriendRequestSyncItem

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class FriendRequestSyncItem : CommonSyncServiceItem`2
{
	private static DelegateBridge __Hotfix0_get_frequency; // 0x0
	private static DelegateBridge __Hotfix0_get_moduleMask; // 0x8
	private static DelegateBridge __Hotfix0_BuildRequestParam; // 0x10
	private static DelegateBridge __Hotfix0_FillResponseModel; // 0x18
	private static DelegateBridge __Hotfix0_HoldResponseModel; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override TrySyncFrequency frequency { get; }
	public override PlayerSyncModuleMask moduleMask { get; }

	// RVA: 0x21fd728 VA: 0x7594815728
	public override TrySyncFrequency get_frequency() { }
	// RVA: 0x21fd7f0 VA: 0x75948157f0
	public override PlayerSyncModuleMask get_moduleMask() { }
	// RVA: 0x21fd858 VA: 0x7594815858
	protected override PlayerSyncParam BuildRequestParam() { }
	// RVA: 0x21fd8bc VA: 0x75948158bc
	protected override Void FillResponseModel(PlayerSyncStatusViewModel viewModel, PlayerSyncResult result) { }
	// RVA: 0x21fd93c VA: 0x759481593c
	protected override Void HoldResponseModel(PlayerSyncStatusViewModel curModel, PlayerSyncStatusViewModel prevModel) { }
	// RVA: 0x21fc8a8 VA: 0x75948148a8
	public Void .ctor() { }
}
```