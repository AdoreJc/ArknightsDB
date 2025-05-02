# TuningArchivePlugin

**Namespace:** `Torappu.UI.Tuning`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningArchivePlugin : ActArchivePlugin, IHotfixable
{
	private static DelegateBridge __Hotfix0_GetArchiveEntryType; // 0x0
	private static DelegateBridge __Hotfix0_GetArchiveItemValidStatus; // 0x8
	private static DelegateBridge __Hotfix0_GetArchiveItemLockStatus; // 0x10
	private static DelegateBridge __Hotfix0_GetSceneParamToState; // 0x18
	private static DelegateBridge __Hotfix0_ConstructCompPlugin; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2311700 VA: 0x7594929700
	public override ActArchiveType GetArchiveEntryType() { }
	// RVA: 0x2311764 VA: 0x7594929764
	public override Boolean GetArchiveItemValidStatus(String archiveId, String archiveItemId, ActArchiveType archiveItemType) { }
	// RVA: 0x23117fc VA: 0x75949297fc
	public override Boolean GetArchiveItemLockStatus(String archiveId, String archiveItemId, ActArchiveType archiveItemType, out String lockedToast) { }
	// RVA: 0x2311aec VA: 0x7594929aec
	public override List`1 GetSceneParamToState(String archiveId) { }
	// RVA: 0x2311e88 VA: 0x7594929e88
	public override Void ConstructCompPlugin() { }
	// RVA: 0x2311f98 VA: 0x7594929f98
	public Void .ctor() { }
}
```