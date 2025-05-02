# CharacterLvlupVoucherViewModel

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `EvolvePhase evolvePhase`

- `String skinId`

- `Int32 potentialRank`

- `Int32 mainSkillLvl`

- `String powerId`

- `String charName`

- `String charNickName`

- `RarityRank rarity`

- `PlayerCharacter m_playerChar`

- `CharacterData m_charData`

- `UplevelAttribute currentAttr`

- `Int32 currentLevel`

- `UplevelAttribute maxAttr`

- `Int32 maxLevel`

- `RequireViewModel requireViewModel`


## Methods

- `Void LoadData(PlayerCharacter, CharacterData, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupVoucherViewModel : IHotfixable
{
	public EvolvePhase evolvePhase; // 0x10
	public String skinId; // 0x18
	public Int32 potentialRank; // 0x20
	public Int32 mainSkillLvl; // 0x24
	public String powerId; // 0x28
	public String charName; // 0x30
	public String charNickName; // 0x38
	public RarityRank rarity; // 0x40
	private PlayerCharacter m_playerChar; // 0x48
	private CharacterData m_charData; // 0x50
	public UplevelAttribute currentAttr; // 0x58
	public Int32 currentLevel; // 0x68
	public UplevelAttribute maxAttr; // 0x6c
	public Int32 maxLevel; // 0x7c
	public RequireViewModel requireViewModel; // 0x80
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2d62ecc VA: 0x759537aecc
	public Void LoadData(PlayerCharacter playerChar, CharacterData charData, String voucherItemId) { }
	// RVA: 0x2d633c4 VA: 0x759537b3c4
	public Void .ctor() { }
}
```