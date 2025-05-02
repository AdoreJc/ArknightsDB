# Clue

**Namespace:** ` `


## Fields

- `PlayerBuildingMeetingClue m_clue`

- `ClueData m_clueData`

- `ClueTypeData m_typeData`

- `SpriteHub m_spriteHub`

- `Boolean m_external`


## Properties

- `String clueId`

- `Boolean isInSlot`

- `Int32 category`

- `Int32 number`

- `String name`

- `String description`

- `Sprite image`

- `Boolean external`

- `Int64 expireTime`

- `Int32 collectBonus`

- `Int32 removeBonus`

- `String fromString`

- `String typeName`


## Methods

- `Void UpdatePlayerClue(PlayerBuildingMeetingClue)`

- `String get_clueId()`

- `Boolean get_isInSlot()`

- `Int32 get_category()`

- `Int32 get_number()`

- `String get_name()`

- `String get_description()`

- `Sprite get_image()`

- `Boolean get_external()`

- `Int64 get_expireTime()`

- `Int32 get_collectBonus()`

- `Int32 get_removeBonus()`

- `String get_fromString()`

- `String get_typeName()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class Clue : IMeetingClue, IHotfixable
{
	private PlayerBuildingMeetingClue m_clue; // 0x10
	private ClueData m_clueData; // 0x18
	private ClueTypeData m_typeData; // 0x20
	private SpriteHub m_spriteHub; // 0x28
	private Boolean m_external; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_UpdatePlayerClue; // 0x8
	private static DelegateBridge __Hotfix0_get_clueId; // 0x10
	private static DelegateBridge __Hotfix0_get_isInSlot; // 0x18
	private static DelegateBridge __Hotfix0_get_category; // 0x20
	private static DelegateBridge __Hotfix0_get_number; // 0x28
	private static DelegateBridge __Hotfix0_get_name; // 0x30
	private static DelegateBridge __Hotfix0_get_description; // 0x38
	private static DelegateBridge __Hotfix0_get_image; // 0x40
	private static DelegateBridge __Hotfix0_get_external; // 0x48
	private static DelegateBridge __Hotfix0_get_expireTime; // 0x50
	private static DelegateBridge __Hotfix0_get_collectBonus; // 0x58
	private static DelegateBridge __Hotfix0_get_removeBonus; // 0x60
	private static DelegateBridge __Hotfix0_get_producers; // 0x68
	private static DelegateBridge __Hotfix0_get_fromString; // 0x70
	private static DelegateBridge __Hotfix0_get_typeName; // 0x78

	public String clueId { get; }
	public Boolean isInSlot { get; }
	public Int32 category { get; }
	public Int32 number { get; }
	public String name { get; }
	public String description { get; }
	public Sprite image { get; }
	public Boolean external { get; }
	public Int64 expireTime { get; }
	public Int32 collectBonus { get; }
	public Int32 removeBonus { get; }
	public IEnumerable`1 producers { get; }
	public String fromString { get; }
	public String typeName { get; }

	// RVA: 0x3de28a0 VA: 0x75963fa8a0
	public Void .ctor(PlayerBuildingMeetingClue clue, ClueData clueData, ClueTypeData typeData, SpriteHub spriteHub, Boolean external) { }
	// RVA: 0x3de29a8 VA: 0x75963fa9a8
	public Void UpdatePlayerClue(PlayerBuildingMeetingClue clue) { }
	// RVA: 0x3de282c VA: 0x75963fa82c
	public String get_clueId() { }
	// RVA: 0x3de5c98 VA: 0x75963fdc98
	public Boolean get_isInSlot() { }
	// RVA: 0x3de5d14 VA: 0x75963fdd14
	public Int32 get_category() { }
	// RVA: 0x3de5d8c VA: 0x75963fdd8c
	public Int32 get_number() { }
	// RVA: 0x3de5e00 VA: 0x75963fde00
	public String get_name() { }
	// RVA: 0x3de5e94 VA: 0x75963fde94
	public String get_description() { }
	// RVA: 0x3de5f18 VA: 0x75963fdf18
	public Sprite get_image() { }
	// RVA: 0x3de3f80 VA: 0x75963fbf80
	public Boolean get_external() { }
	// RVA: 0x3de5ffc VA: 0x75963fdffc
	public Int64 get_expireTime() { }
	// RVA: 0x3de6074 VA: 0x75963fe074
	public Int32 get_collectBonus() { }
	// RVA: 0x3de60d8 VA: 0x75963fe0d8
	public Int32 get_removeBonus() { }
	// RVA: 0x3de6164 VA: 0x75963fe164
	public IEnumerable`1 get_producers() { }
	// RVA: 0x3de6254 VA: 0x75963fe254
	public String get_fromString() { }
	// RVA: 0x3de3a58 VA: 0x75963fba58
	public String get_typeName() { }
}
```