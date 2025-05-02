# RecruitSpecialGachaUpCharCardViewModel

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `String charId`

- `RarityRank rarity`

- `ProfessionCategory profession`

- `String charName`

- `String portraitId`


## Methods

- `Void LoadData(String, RarityRank)`

- `Boolean IsEmpty()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitSpecialGachaUpCharCardViewModel : IHotfixable
{
	public String charId; // 0x10
	public RarityRank rarity; // 0x18
	public ProfessionCategory profession; // 0x1c
	public String charName; // 0x20
	public String portraitId; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_IsEmpty; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2701bfc VA: 0x7594d19bfc
	public Void LoadData(String charId, RarityRank rank) { }
	// RVA: 0x2703a68 VA: 0x7594d1ba68
	public Boolean IsEmpty() { }
	// RVA: 0x2701b8c VA: 0x7594d19b8c
	public Void .ctor() { }
}
```