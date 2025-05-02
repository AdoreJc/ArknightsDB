# StoryCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `StoryProperty story`


## Methods

- `StoryItemModel GetStoryItemInfo(String)`

- `Void SetSelectedStoryItem(String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class StoryCompInfo : ActArchiveCompInfo
{
	public StoryProperty story; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetStoryItemInfo; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedStoryItem; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x20
	private static DelegateBridge __Hotfix0_IsValid; // 0x28
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x30


	// RVA: 0x3082bb0 VA: 0x759569abb0
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x3082c38 VA: 0x759569ac38
	public StoryItemModel GetStoryItemInfo(String storyId) { }
	// RVA: 0x3082d1c VA: 0x759569ad1c
	public Void SetSelectedStoryItem(String storyID, Boolean isInit) { }
	// RVA: 0x3082e94 VA: 0x759569ae94
	public override Void LoadData(String archiveId) { }
	// RVA: 0x3082fd4 VA: 0x759569afd4
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x3083088 VA: 0x759569b088
	public override Boolean IsValid() { }
	// RVA: 0x3083114 VA: 0x759569b114
	public override Void NotifyUpdate() { }
}
```