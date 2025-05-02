# UIPortraitChooseCharCardViewModel

**Namespace:** `Torappu.UI.ChooseChar`


## Fields

- `String charId`

- `String charName`

- `ProfessionCategory profession`

- `RarityRank rarityRank`

- `String portraitId`

- `Boolean isOwned`

- `Int32 potentialRank`


## Methods

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ChooseChar
public class UIPortraitChooseCharCardViewModel : IHotfixable
{
	public String charId; // 0x10
	public String charName; // 0x18
	public ProfessionCategory profession; // 0x20
	public RarityRank rarityRank; // 0x24
	public String portraitId; // 0x28
	public Boolean isOwned; // 0x30
	public Int32 potentialRank; // 0x34
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2c3f1cc VA: 0x75952571cc
	public Void LoadData(String charId) { }
	// RVA: 0x2c3f3e8 VA: 0x75952573e8
	public Void .ctor() { }
}
```