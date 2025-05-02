# Act13SideArchivePlugin

**Namespace:** `Torappu.Activity.Act13Side`


## Methods

- `Act13SideArchivePrestigeUnlockCond _GetPrestigeUnlockConditionParam(ArchiveItemUnlockData)`

- `Act13SideArchiveStageUnlockCond _GetStageUnlockConditionParam(ArchiveItemUnlockData)`

- `Boolean _GetPrestigeUnlockStatus(String, Act13SideData, Act13SideArchivePrestigeUnlockCond, out)`

- `Boolean _GetStageUnlockStatus(String, Act13SideData, Act13SideArchiveStageUnlockCond, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13SideArchivePlugin : ActArchivePlugin
{
	private static DelegateBridge __Hotfix0_ConstructCompPlugin; // 0x0
	private static DelegateBridge __Hotfix0_GetArchiveEntryType; // 0x8
	private static DelegateBridge __Hotfix0_GetArchiveItemValidStatus; // 0x10
	private static DelegateBridge __Hotfix0_GetArchiveItemLockStatus; // 0x18
	private static DelegateBridge __Hotfix0_GetSceneParamToState; // 0x20
	private static DelegateBridge __Hotfix0__GetPrestigeUnlockConditionParam; // 0x28
	private static DelegateBridge __Hotfix0__GetStageUnlockConditionParam; // 0x30
	private static DelegateBridge __Hotfix0__GetPrestigeUnlockStatus; // 0x38
	private static DelegateBridge __Hotfix0__GetStageUnlockStatus; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x3425774 VA: 0x7595a3d774
	public override Void ConstructCompPlugin() { }
	// RVA: 0x3425930 VA: 0x7595a3d930
	public override ActArchiveType GetArchiveEntryType() { }
	// RVA: 0x3425998 VA: 0x7595a3d998
	public override Boolean GetArchiveItemValidStatus(String archiveId, String archiveItemId, ActArchiveType archiveItemType) { }
	// RVA: 0x3425a30 VA: 0x7595a3da30
	public override Boolean GetArchiveItemLockStatus(String archiveId, String archiveItemId, ActArchiveType archiveItemType, out String lockedToast) { }
	// RVA: 0x3426350 VA: 0x7595a3e350
	public override List`1 GetSceneParamToState(String archiveId) { }
	// RVA: 0x3425d80 VA: 0x7595a3dd80
	private Act13SideArchivePrestigeUnlockCond _GetPrestigeUnlockConditionParam(ArchiveItemUnlockData unlockData) { }
	// RVA: 0x342605c VA: 0x7595a3e05c
	private Act13SideArchiveStageUnlockCond _GetStageUnlockConditionParam(ArchiveItemUnlockData unlockData) { }
	// RVA: 0x3425e20 VA: 0x7595a3de20
	private Boolean _GetPrestigeUnlockStatus(String archiveId, Act13SideData data, Act13SideArchivePrestigeUnlockCond param, out String lockedToast) { }
	// RVA: 0x34260fc VA: 0x7595a3e0fc
	private Boolean _GetStageUnlockStatus(String archiveId, Act13SideData data, Act13SideArchiveStageUnlockCond param, out String lockedToast) { }
	// RVA: 0x3426920 VA: 0x7595a3e920
	public Void .ctor() { }
}
```