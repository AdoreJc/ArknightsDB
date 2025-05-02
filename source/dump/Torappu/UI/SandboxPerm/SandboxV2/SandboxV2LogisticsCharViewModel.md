# SandboxV2LogisticsCharViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Int32 charInstId`

- `CharacterData m_charData`

- `PlayerCharacter m_playerCharacter`

- `Int32 m_beanCount`


## Properties

- `String charName`

- `String charId`

- `Int32 charBeanCount`

- `ProfessionCategory professionCategory`

- `RarityRank rarity`

- `String skinId`


## Methods

- `String get_charName()`

- `String get_charId()`

- `Int32 get_charBeanCount()`

- `ProfessionCategory get_professionCategory()`

- `RarityRank get_rarity()`

- `String get_skinId()`

- `Int32 CompareTo(SandboxV2LogisticsCharViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2LogisticsCharViewModel : IHotfixable, IComparable`1
{
	public Int32 charInstId; // 0x10
	private CharacterData m_charData; // 0x18
	private PlayerCharacter m_playerCharacter; // 0x20
	private Int32 m_beanCount; // 0x28
	private static DelegateBridge __Hotfix0_get_charName; // 0x0
	private static DelegateBridge __Hotfix0_get_charId; // 0x8
	private static DelegateBridge __Hotfix0_get_charBeanCount; // 0x10
	private static DelegateBridge __Hotfix0_get_professionCategory; // 0x18
	private static DelegateBridge __Hotfix0_get_rarity; // 0x20
	private static DelegateBridge __Hotfix0_get_skinId; // 0x28
	private static DelegateBridge __Hotfix0_CompareTo; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public String charName { get; }
	public String charId { get; }
	public Int32 charBeanCount { get; }
	public ProfessionCategory professionCategory { get; }
	public RarityRank rarity { get; }
	public String skinId { get; }

	// RVA: 0x25d9dbc VA: 0x7594bf1dbc
	public String get_charName() { }
	// RVA: 0x25dc5b0 VA: 0x7594bf45b0
	public String get_charId() { }
	// RVA: 0x25dba54 VA: 0x7594bf3a54
	public Int32 get_charBeanCount() { }
	// RVA: 0x25db970 VA: 0x7594bf3970
	public ProfessionCategory get_professionCategory() { }
	// RVA: 0x25deb30 VA: 0x7594bf6b30
	public RarityRank get_rarity() { }
	// RVA: 0x25deba4 VA: 0x7594bf6ba4
	public String get_skinId() { }
	// RVA: 0x25dec1c VA: 0x7594bf6c1c
	public Int32 CompareTo(SandboxV2LogisticsCharViewModel obj) { }
	// RVA: 0x25de5b0 VA: 0x7594bf65b0
	public Void .ctor(SandboxV2Data gameData, Int32 charInstId, CharacterData characterData, PlayerCharacter playerCharacter) { }
}
```