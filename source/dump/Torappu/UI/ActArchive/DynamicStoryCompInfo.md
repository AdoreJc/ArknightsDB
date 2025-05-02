# DynamicStoryCompInfo

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
public class DynamicStoryCompInfo : ActArchiveCompInfo
{
	public StoryProperty story; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetStoryItemInfo; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedStoryItem; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x20
	private static DelegateBridge __Hotfix0_IsValid; // 0x28
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x30


	// RVA: 0x30831bc VA: 0x759569b1bc
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x3083244 VA: 0x759569b244
	public StoryItemModel GetStoryItemInfo(String storyId) { }
	// RVA: 0x3083328 VA: 0x759569b328
	public Void SetSelectedStoryItem(String storyID, Boolean isInit) { }
	// RVA: 0x30834a0 VA: 0x759569b4a0
	public override Void LoadData(String archiveId) { }
	// RVA: 0x30835e0 VA: 0x759569b5e0
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x3083694 VA: 0x759569b694
	public override Boolean IsValid() { }
	// RVA: 0x3083720 VA: 0x759569b720
	public override Void NotifyUpdate() { }
}
```