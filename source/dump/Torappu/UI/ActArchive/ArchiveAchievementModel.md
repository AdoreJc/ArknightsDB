# ArchiveAchievementModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveAchievementListGotFilterViewModel gotFilterViewModel`


## Methods

- `Void LoadData(String, Dictionary`2, ActArchiveInfo)`

- `Void _LoadAchievementFilterModels(String, ActArchiveInfo)`

- `Void _CollectRarityCount()`

- `Void RefreshDisplayItemList()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveAchievementModel : IHotfixable
{
	public Dictionary`2 achievementRarityCountDict; // 0x10
	public Dictionary`2 filters; // 0x18
	public List`1 achievementItemDisplayList; // 0x20
	public ArchiveAchievementListGotFilterViewModel gotFilterViewModel; // 0x28
	private List`1 m_achievementItems; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__LoadAchievementFilterModels; // 0x8
	private static DelegateBridge __Hotfix0__CollectRarityCount; // 0x10
	private static DelegateBridge __Hotfix0_RefreshDisplayItemList; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30166fc VA: 0x759562e6fc
	public Void LoadData(String archiveId, Dictionary`2 achievementData, ActArchiveInfo archiveInfo) { }
	// RVA: 0x3016eb0 VA: 0x759562eeb0
	private Void _LoadAchievementFilterModels(String archiveId, ActArchiveInfo archiveInfo) { }
	// RVA: 0x3016cac VA: 0x759562ecac
	private Void _CollectRarityCount() { }
	// RVA: 0x30117e0 VA: 0x75956297e0
	public Void RefreshDisplayItemList() { }
	// RVA: 0x3016fe8 VA: 0x759562efe8
	public Void .ctor() { }
}
```