# HomeCharRotationPresetSkinItemViewModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `String charId`

- `RarityRank charRarityRank`

- `String skinId`

- `String avatarId`

- `String skinName`

- `String charName`

- `Int32 skinSortId`

- `Boolean isProfileSkinId`

- `Int32 charSelectedSkinCount`


## Methods

- `Void LoadData(String)`

- `Int32 CompareTo(HomeCharRotationPresetSkinItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCharRotationPresetSkinItemViewModel : IComparable`1, IHotfixable
{
	public String charId; // 0x10
	public RarityRank charRarityRank; // 0x18
	public String skinId; // 0x20
	public String avatarId; // 0x28
	public String skinName; // 0x30
	public String charName; // 0x38
	public Int32 skinSortId; // 0x40
	public Boolean isProfileSkinId; // 0x44
	public Int32 charSelectedSkinCount; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_CompareTo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x27e0780 VA: 0x7594df8780
	public Void LoadData(String skin) { }
	// RVA: 0x27e09e0 VA: 0x7594df89e0
	public Int32 CompareTo(HomeCharRotationPresetSkinItemViewModel other) { }
	// RVA: 0x27e0b8c VA: 0x7594df8b8c
	public Void .ctor() { }
}
```