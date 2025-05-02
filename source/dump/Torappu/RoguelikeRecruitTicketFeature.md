# RoguelikeRecruitTicketFeature

**Namespace:** `Torappu`


## Fields

- `String id`

- `ProfessionCategory profession`

- `RarityRankMask rarity`

- `Int32 extraEliteNum`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RoguelikeRecruitTicketFeature
{
	public String id; // 0x10
	public ProfessionCategory profession; // 0x18
	public RarityRankMask rarity; // 0x1c
	public List`1 professionList; // 0x20
	public List`1 rarityList; // 0x28
	public Int32 extraEliteNum; // 0x30
	public List`1 extraFreeRarity; // 0x38
	public List`1 extraCharIds; // 0x40


	// RVA: 0x34a8b44 VA: 0x7595ac0b44
	public Void .ctor() { }
}
```