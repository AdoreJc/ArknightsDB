# Act17sideArchivePlugin

**Namespace:** `Torappu.Activity.Act17side`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act17side
public class Act17sideArchivePlugin : ActArchivePlugin, IHotfixable
{
	private static DelegateBridge __Hotfix0_GetArchiveEntryType; // 0x0
	private static DelegateBridge __Hotfix0_GetArchiveItemValidStatus; // 0x8
	private static DelegateBridge __Hotfix0_GetArchiveItemLockStatus; // 0x10
	private static DelegateBridge __Hotfix0_GetSceneParamToState; // 0x18
	private static DelegateBridge __Hotfix0_ConstructCompPlugin; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3418c58 VA: 0x7595a30c58
	public override ActArchiveType GetArchiveEntryType() { }
	// RVA: 0x3418cc0 VA: 0x7595a30cc0
	public override Boolean GetArchiveItemValidStatus(String archiveId, String archiveItemId, ActArchiveType archiveItemType) { }
	// RVA: 0x3418d58 VA: 0x7595a30d58
	public override Boolean GetArchiveItemLockStatus(String archiveId, String archiveItemId, ActArchiveType archiveItemType, out String lockedToast) { }
	// RVA: 0x3419150 VA: 0x7595a31150
	public override List`1 GetSceneParamToState(String archiveId) { }
	// RVA: 0x34193dc VA: 0x7595a313dc
	public override Void ConstructCompPlugin() { }
	// RVA: 0x34194ec VA: 0x7595a314ec
	public Void .ctor() { }
}
```