# ArchiveAchievementListTypeFilterViewModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String m_selectedType`


## Methods

- `Boolean IsTypeSelected(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveAchievementListTypeFilterViewModel : ArchiveAchievementListFilterViewModel
{
	public List`1 achievementTypeList; // 0x18
	private String m_selectedType; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_CheckIfItemValid; // 0x8
	private static DelegateBridge __Hotfix0_SetSelection; // 0x10
	private static DelegateBridge __Hotfix0_IsTypeSelected; // 0x18


	// RVA: 0x30161d0 VA: 0x759562e1d0
	public Void .ctor(List`1 typeDataList) { }
	// RVA: 0x3016388 VA: 0x759562e388
	public override Boolean CheckIfItemValid(AchievementItemModel itemModel) { }
	// RVA: 0x301643c VA: 0x759562e43c
	public override Void SetSelection(String selection) { }
	// RVA: 0x30165e4 VA: 0x759562e5e4
	public Boolean IsTypeSelected(String type) { }
}
```