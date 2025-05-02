# AchievementItemModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String achievementId`

- `Int32 raritySortId`

- `Int32 sortId`

- `String achievementName`

- `String achievementRawDesc`

- `Int32 progressTarget`

- `Int32 progressValue`

- `Boolean isCompleted`


## Properties

- `Single progressPercent`

- `String achievementDesc`


## Methods

- `Single get_progressPercent()`

- `String get_achievementDesc()`

- `Int32 CompareTo(AchievementItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class AchievementItemModel : ArchiveItemModel, IComparable`1
{
	public String achievementId; // 0x30
	public List`1 achievementType; // 0x38
	public Int32 raritySortId; // 0x40
	public Int32 sortId; // 0x44
	public String achievementName; // 0x48
	public String achievementRawDesc; // 0x50
	public Int32 progressTarget; // 0x58
	public Int32 progressValue; // 0x5c
	public Boolean isCompleted; // 0x60
	private static DelegateBridge __Hotfix0_get_progressPercent; // 0x0
	private static DelegateBridge __Hotfix0_get_achievementDesc; // 0x8
	private static DelegateBridge __Hotfix0_GetFuncId; // 0x10
	private static DelegateBridge __Hotfix0_GetDesc; // 0x18
	private static DelegateBridge __Hotfix0_CompareTo; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Single progressPercent { get; }
	public String achievementDesc { get; }

	// RVA: 0x3015c14 VA: 0x759562dc14
	public Single get_progressPercent() { }
	// RVA: 0x3015afc VA: 0x759562dafc
	public String get_achievementDesc() { }
	// RVA: 0x3015d0c VA: 0x759562dd0c
	public override String GetFuncId() { }
	// RVA: 0x3015d74 VA: 0x759562dd74
	public override String GetDesc() { }
	// RVA: 0x3015ddc VA: 0x759562dddc
	public Int32 CompareTo(AchievementItemModel other) { }
	// RVA: 0x3015eec VA: 0x759562deec
	public Void .ctor() { }
}
```