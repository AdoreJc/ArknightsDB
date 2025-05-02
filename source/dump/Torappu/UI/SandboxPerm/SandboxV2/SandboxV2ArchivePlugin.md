# SandboxV2ArchivePlugin

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ArchivePlugin : ActArchivePlugin
{
	public const String KEY_IS_FROM_SANDBOX_V2_DUNGEON; // 0x0
	private static DelegateBridge __Hotfix0_GetArchiveEntryType; // 0x0
	private static DelegateBridge __Hotfix0_GetArchiveItemValidStatus; // 0x8
	private static DelegateBridge __Hotfix0_GetArchiveItemLockStatus; // 0x10
	private static DelegateBridge __Hotfix0_GetSceneParamToState; // 0x18
	private static DelegateBridge __Hotfix0_ConstructCompPlugin; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x24faf50 VA: 0x7594b12f50
	public override ActArchiveType GetArchiveEntryType() { }
	// RVA: 0x24fafb8 VA: 0x7594b12fb8
	public override Boolean GetArchiveItemValidStatus(String archiveId, String archiveItemId, ActArchiveType archiveItemType) { }
	// RVA: 0x24fb050 VA: 0x7594b13050
	public override Boolean GetArchiveItemLockStatus(String archiveId, String archiveItemId, ActArchiveType archiveItemType, out String lockedToast) { }
	// RVA: 0x24fb2a4 VA: 0x7594b132a4
	public override List`1 GetSceneParamToState(String archiveId) { }
	// RVA: 0x24fb780 VA: 0x7594b13780
	public override Void ConstructCompPlugin() { }
	// RVA: 0x24fb9e8 VA: 0x7594b139e8
	public Void .ctor() { }
}
```