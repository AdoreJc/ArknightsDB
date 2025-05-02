# ArchiveAchievementListGotFilterViewModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `GotType m_type`


## Methods

- `Boolean CheckIfItemValid(AchievementItemModel)`

- `Void SetSelection(GotType)`

- `GotType GetGotType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveAchievementListGotFilterViewModel : IHotfixable
{
	private GotType m_type; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_CheckIfItemValid; // 0x8
	private static DelegateBridge __Hotfix0_SetSelection; // 0x10
	private static DelegateBridge __Hotfix0_GetGotType; // 0x18


	// RVA: 0x3016034 VA: 0x759562e034
	public Void .ctor() { }
	// RVA: 0x30160ac VA: 0x759562e0ac
	public Boolean CheckIfItemValid(AchievementItemModel itemModel) { }
	// RVA: 0x3011764 VA: 0x7595629764
	public Void SetSelection(GotType selection) { }
	// RVA: 0x3016168 VA: 0x759562e168
	public GotType GetGotType() { }
}
```