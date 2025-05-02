# CheckForbiddenSyncItem

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CheckForbiddenSyncItem : CommonSyncServiceItem`2
{
	private static DelegateBridge __Hotfix0_get_frequency; // 0x0
	private static DelegateBridge __Hotfix0_get_moduleMask; // 0x8
	private static DelegateBridge __Hotfix0_FillResponseModel; // 0x10
	private static DelegateBridge __Hotfix0_HoldResponseModel; // 0x18
	private static DelegateBridge __Hotfix0_BuildRequestParam; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override TrySyncFrequency frequency { get; }
	public override PlayerSyncModuleMask moduleMask { get; }

	// RVA: 0x21fff74 VA: 0x7594817f74
	public override TrySyncFrequency get_frequency() { }
	// RVA: 0x220003c VA: 0x759481803c
	public override PlayerSyncModuleMask get_moduleMask() { }
	// RVA: 0x22000a4 VA: 0x75948180a4
	protected override Void FillResponseModel(PlayerSyncStatusViewModel viewModel, PlayerCheckForbiddenResult result) { }
	// RVA: 0x2200138 VA: 0x7594818138
	protected override Void HoldResponseModel(PlayerSyncStatusViewModel curModel, PlayerSyncStatusViewModel prevModel) { }
	// RVA: 0x22001e0 VA: 0x75948181e0
	protected override PlayerSyncParam BuildRequestParam() { }
	// RVA: 0x21fce64 VA: 0x7594814e64
	public Void .ctor() { }
}
```