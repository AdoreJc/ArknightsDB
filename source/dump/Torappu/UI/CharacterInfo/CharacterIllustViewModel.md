# CharacterIllustViewModel

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharUISkinStruct m_selectedSkin`

- `Boolean m_isNPC`

- `Int32 m_instIdCache`

- `String <charOrNpcId>k__BackingField`

- `EvolvePhase <evolvePhase>k__BackingField`

- `Boolean <autoActivateIllust>k__BackingField`

- `IllustNPCResType <illustType>k__BackingField`


## Properties

- `CharUISkinStruct selectedSkin`

- `String charOrNpcId`

- `EvolvePhase evolvePhase`

- `Boolean isNPC`

- `Boolean autoActivateIllust`

- `IllustNPCResType illustType`


## Methods

- `CharUISkinStruct get_selectedSkin()`

- `Void set_selectedSkin(CharUISkinStruct)`

- `String get_charOrNpcId()`

- `Void set_charOrNpcId(String)`

- `EvolvePhase get_evolvePhase()`

- `Void set_evolvePhase(EvolvePhase)`

- `Boolean get_isNPC()`

- `Boolean get_autoActivateIllust()`

- `Void set_autoActivateIllust(Boolean)`

- `IllustNPCResType get_illustType()`

- `Void set_illustType(IllustNPCResType)`

- `Void LoadData(PlayerCharacter, CharacterData, Boolean)`

- `Void LoadData(HandBookCardViewModel)`

- `Void _LoadChrDataInternal(Int32, String, EvolvePhase, IllustNPCResType)`

- `Void _LoadNpcDataInternal(String, String, IllustNPCResType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterIllustViewModel
{
	private CharUISkinStruct m_selectedSkin; // 0x10
	private Boolean m_isNPC; // 0x20
	private Int32 m_instIdCache; // 0x24
	private String <charOrNpcId>k__BackingField; // 0x28
	private EvolvePhase <evolvePhase>k__BackingField; // 0x30
	private Boolean <autoActivateIllust>k__BackingField; // 0x34
	private IllustNPCResType <illustType>k__BackingField; // 0x38

	public CharUISkinStruct selectedSkin { get; set; }
	public String charOrNpcId { get; set; }
	public EvolvePhase evolvePhase { get; set; }
	public Boolean isNPC { get; }
	public Boolean autoActivateIllust { get; set; }
	public IllustNPCResType illustType { get; set; }

	// RVA: 0x2d54064 VA: 0x759536c064
	public CharUISkinStruct get_selectedSkin() { }
	// RVA: 0x2d54114 VA: 0x759536c114
	public Void set_selectedSkin(CharUISkinStruct value) { }
	// RVA: 0x2d54124 VA: 0x759536c124
	public String get_charOrNpcId() { }
	// RVA: 0x2d5412c VA: 0x759536c12c
	private Void set_charOrNpcId(String value) { }
	// RVA: 0x2d54134 VA: 0x759536c134
	public EvolvePhase get_evolvePhase() { }
	// RVA: 0x2d5413c VA: 0x759536c13c
	private Void set_evolvePhase(EvolvePhase value) { }
	// RVA: 0x2d54144 VA: 0x759536c144
	public Boolean get_isNPC() { }
	// RVA: 0x2d5414c VA: 0x759536c14c
	public Boolean get_autoActivateIllust() { }
	// RVA: 0x2d54154 VA: 0x759536c154
	private Void set_autoActivateIllust(Boolean value) { }
	// RVA: 0x2d54160 VA: 0x759536c160
	public IllustNPCResType get_illustType() { }
	// RVA: 0x2d54168 VA: 0x759536c168
	private Void set_illustType(IllustNPCResType value) { }
	// RVA: 0x2d53d04 VA: 0x759536bd04
	public Void LoadData(PlayerCharacter playerChar, CharacterData charData, Boolean autoActivateIllust) { }
	// RVA: 0x2d5421c VA: 0x759536c21c
	public Void LoadData(HandBookCardViewModel cardData) { }
	// RVA: 0x2d54170 VA: 0x759536c170
	private Void _LoadChrDataInternal(Int32 instId, String charId, EvolvePhase evolvePhase, IllustNPCResType resFolder) { }
	// RVA: 0x2d542cc VA: 0x759536c2cc
	private Void _LoadNpcDataInternal(String npcId, String illustId, IllustNPCResType resFolder) { }
	// RVA: 0x2d53dc8 VA: 0x759536bdc8
	public Void .ctor() { }
}
```