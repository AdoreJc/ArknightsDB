# HomeIllustrateStateBean

**Namespace:** `Torappu.UI.HomeIllustrate`


## Fields

- `HomeIllustStruct homeIllust`

- `String <charId>k__BackingField`

- `EvolvePhase <evolvePhase>k__BackingField`

- `CharacterData <charData>k__BackingField`

- `PlayerCharacter <playerChar>k__BackingField`

- `Int32 <selectedIndex>k__BackingField`


## Properties

- `String charId`

- `EvolvePhase evolvePhase`

- `CharacterData charData`

- `PlayerCharacter playerChar`

- `Int32 selectedIndex`


## Methods

- `String get_charId()`

- `Void set_charId(String)`

- `EvolvePhase get_evolvePhase()`

- `Void set_evolvePhase(EvolvePhase)`

- `CharacterData get_charData()`

- `Void set_charData(CharacterData)`

- `PlayerCharacter get_playerChar()`

- `Void set_playerChar(PlayerCharacter)`

- `Int32 get_selectedIndex()`

- `Void set_selectedIndex(Int32)`

- `Void InitData()`

- `String GetSelectedSkinId()`

- `Void _LoadIllusts()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HomeIllustrate
public class HomeIllustrateStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public HomeIllustStruct homeIllust; // 0x18
	private String <charId>k__BackingField; // 0x20
	private EvolvePhase <evolvePhase>k__BackingField; // 0x28
	private CharacterData <charData>k__BackingField; // 0x30
	private PlayerCharacter <playerChar>k__BackingField; // 0x38
	private Int32 <selectedIndex>k__BackingField; // 0x40
	private List`1 m_skins; // 0x48
	private static DelegateBridge __Hotfix0_get_charId; // 0x0
	private static DelegateBridge __Hotfix0_set_charId; // 0x8
	private static DelegateBridge __Hotfix0_get_evolvePhase; // 0x10
	private static DelegateBridge __Hotfix0_set_evolvePhase; // 0x18
	private static DelegateBridge __Hotfix0_get_charData; // 0x20
	private static DelegateBridge __Hotfix0_set_charData; // 0x28
	private static DelegateBridge __Hotfix0_get_playerChar; // 0x30
	private static DelegateBridge __Hotfix0_set_playerChar; // 0x38
	private static DelegateBridge __Hotfix0_get_selectedIndex; // 0x40
	private static DelegateBridge __Hotfix0_set_selectedIndex; // 0x48
	private static DelegateBridge __Hotfix0_InitData; // 0x50
	private static DelegateBridge __Hotfix0_GetSelectedSkinId; // 0x58
	private static DelegateBridge __Hotfix0__LoadIllusts; // 0x60
	private static DelegateBridge __Hotfix0__LoadSelectableUISkins; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public String charId { get; set; }
	public EvolvePhase evolvePhase { get; set; }
	public CharacterData charData { get; set; }
	public PlayerCharacter playerChar { get; set; }
	public Int32 selectedIndex { get; set; }

	// RVA: 0x27d636c VA: 0x7594dee36c
	public String get_charId() { }
	// RVA: 0x27d63d4 VA: 0x7594dee3d4
	private Void set_charId(String value) { }
	// RVA: 0x27d6458 VA: 0x7594dee458
	public EvolvePhase get_evolvePhase() { }
	// RVA: 0x27d64c0 VA: 0x7594dee4c0
	private Void set_evolvePhase(EvolvePhase value) { }
	// RVA: 0x27d653c VA: 0x7594dee53c
	public CharacterData get_charData() { }
	// RVA: 0x27d65a4 VA: 0x7594dee5a4
	private Void set_charData(CharacterData value) { }
	// RVA: 0x27d6628 VA: 0x7594dee628
	public PlayerCharacter get_playerChar() { }
	// RVA: 0x27d6690 VA: 0x7594dee690
	private Void set_playerChar(PlayerCharacter value) { }
	// RVA: 0x27d6714 VA: 0x7594dee714
	public Int32 get_selectedIndex() { }
	// RVA: 0x27d677c VA: 0x7594dee77c
	private Void set_selectedIndex(Int32 value) { }
	// RVA: 0x27d67f8 VA: 0x7594dee7f8
	public Void InitData() { }
	// RVA: 0x27d6cf4 VA: 0x7594deecf4
	public String GetSelectedSkinId() { }
	// RVA: 0x27d6b9c VA: 0x7594deeb9c
	private Void _LoadIllusts() { }
	// RVA: 0x27d6d94 VA: 0x7594deed94
	private static Void _LoadSelectableUISkins(PlayerCharacter playerChar, ref List`1 skins) { }
	// RVA: 0x27d708c VA: 0x7594def08c
	public Void .ctor() { }
}
```