# Act25sideArchivePlugin

**Namespace:** `Torappu.Activity.Act25side`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideArchivePlugin : ActArchivePlugin, IHotfixable
{
	private static DelegateBridge __Hotfix0_GetArchiveEntryType; // 0x0
	private static DelegateBridge __Hotfix0_GetArchiveItemValidStatus; // 0x8
	private static DelegateBridge __Hotfix0_GetArchiveItemLockStatus; // 0x10
	private static DelegateBridge __Hotfix0_GetSceneParamToState; // 0x18
	private static DelegateBridge __Hotfix0_ConstructCompPlugin; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3272cfc VA: 0x759588acfc
	public override ActArchiveType GetArchiveEntryType() { }
	// RVA: 0x3272d60 VA: 0x759588ad60
	public override Boolean GetArchiveItemValidStatus(String archiveId, String archiveItemId, ActArchiveType archiveItemType) { }
	// RVA: 0x3272df8 VA: 0x759588adf8
	public override Boolean GetArchiveItemLockStatus(String archiveId, String archiveItemId, ActArchiveType archiveItemType, out String lockedToast) { }
	// RVA: 0x3272ee4 VA: 0x759588aee4
	public override List`1 GetSceneParamToState(String archiveId) { }
	// RVA: 0x3273170 VA: 0x759588b170
	public override Void ConstructCompPlugin() { }
	// RVA: 0x3273280 VA: 0x759588b280
	public Void .ctor() { }
}
```