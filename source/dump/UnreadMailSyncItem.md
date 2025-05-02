# UnreadMailSyncItem

**Namespace:** ` `


## Fields

- `DateTime m_lastSyncDateTime`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class UnreadMailSyncItem : CommonSyncServiceItem`2
{
	private DateTime m_lastSyncDateTime; // 0x20
	private static DelegateBridge __Hotfix0_get_frequency; // 0x0
	private static DelegateBridge __Hotfix0_get_moduleMask; // 0x8
	private static DelegateBridge __Hotfix0_BuildRequestParam; // 0x10
	private static DelegateBridge __Hotfix0_FillResponseModel; // 0x18
	private static DelegateBridge __Hotfix0_HoldResponseModel; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override TrySyncFrequency frequency { get; }
	public override PlayerSyncModuleMask moduleMask { get; }

	// RVA: 0x21fd494 VA: 0x7594815494
	public override TrySyncFrequency get_frequency() { }
	// RVA: 0x21fd55c VA: 0x759481555c
	public override PlayerSyncModuleMask get_moduleMask() { }
	// RVA: 0x21fd5c4 VA: 0x75948155c4
	protected override PlayerSyncParam BuildRequestParam() { }
	// RVA: 0x21fd628 VA: 0x7594815628
	protected override Void FillResponseModel(PlayerSyncStatusViewModel viewModel, PlayerSyncResult result) { }
	// RVA: 0x21fd6a8 VA: 0x75948156a8
	protected override Void HoldResponseModel(PlayerSyncStatusViewModel curModel, PlayerSyncStatusViewModel prevModel) { }
	// RVA: 0x21fc818 VA: 0x7594814818
	public Void .ctor() { }
}
```