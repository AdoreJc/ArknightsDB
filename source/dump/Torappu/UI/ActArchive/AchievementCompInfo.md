# AchievementCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveAchievementProperty achievement`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class AchievementCompInfo : ActArchiveCompInfo
{
	public ArchiveAchievementProperty achievement; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x10
	private static DelegateBridge __Hotfix0_IsValid; // 0x18
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x20
	private static DelegateBridge __Hotfix0_GetRarityCountDict; // 0x28


	// RVA: 0x3017224 VA: 0x759562f224
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x3017338 VA: 0x759562f338
	public override Void LoadData(String archiveId) { }
	// RVA: 0x3017524 VA: 0x759562f524
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x301759c VA: 0x759562f59c
	public override Boolean IsValid() { }
	// RVA: 0x3017628 VA: 0x759562f628
	public override Void NotifyUpdate() { }
	// RVA: 0x30176d0 VA: 0x759562f6d0
	public Dictionary`2 GetRarityCountDict() { }
}
```