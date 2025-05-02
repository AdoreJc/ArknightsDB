# StationaryCharacter

**Namespace:** ` `


## Fields

- `BuildingCharModel m_buildingChar`

- `CharacterCardViewModel m_cardViewModel`

- `SpriteRenderData m_portraitSprite`

- `Buff m_buff`


## Properties

- `String charId`

- `Int32 instId`

- `String name`

- `SpriteRenderData portrait`

- `Int32 mood`

- `Int64 manpower`

- `Int32 realMood`

- `IWorkshopBuildingBuff buildingBuff`

- `Int32 maxMood`

- `CharManpowerState mpState`


## Methods

- `Void Setup(BuildingCharModel)`

- `String get_charId()`

- `Int32 get_instId()`

- `String get_name()`

- `SpriteRenderData get_portrait()`

- `Int32 get_mood()`

- `Int64 get_manpower()`

- `Int32 get_realMood()`

- `IWorkshopBuildingBuff get_buildingBuff()`

- `Int32 get_maxMood()`

- `CharManpowerState get_mpState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class StationaryCharacter : IWorkshopStationaryCharacter, IHotfixable
{
	private BuildingCharModel m_buildingChar; // 0x10
	private CharacterCardViewModel m_cardViewModel; // 0x80
	private SpriteRenderData m_portraitSprite; // 0x88
	private Buff m_buff; // 0xb0
	private static DelegateBridge __Hotfix0_Setup; // 0x0
	private static DelegateBridge __Hotfix0_get_charId; // 0x8
	private static DelegateBridge __Hotfix0_get_instId; // 0x10
	private static DelegateBridge __Hotfix0_get_name; // 0x18
	private static DelegateBridge __Hotfix0_get_portrait; // 0x20
	private static DelegateBridge __Hotfix0_get_mood; // 0x28
	private static DelegateBridge __Hotfix0_get_manpower; // 0x30
	private static DelegateBridge __Hotfix0_get_realMood; // 0x38
	private static DelegateBridge __Hotfix0_get_buildingBuff; // 0x40
	private static DelegateBridge __Hotfix0_get_maxMood; // 0x48
	private static DelegateBridge __Hotfix0_get_mpState; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public String charId { get; }
	public Int32 instId { get; }
	public String name { get; }
	public SpriteRenderData portrait { get; }
	public Int32 mood { get; }
	public Int64 manpower { get; }
	public Int32 realMood { get; }
	public IWorkshopBuildingBuff buildingBuff { get; }
	public Int32 maxMood { get; }
	public CharManpowerState mpState { get; }

	// RVA: 0x3d61520 VA: 0x7596379520
	public Void Setup(BuildingCharModel buildingChar) { }
	// RVA: 0x3d6614c VA: 0x759637e14c
	public String get_charId() { }
	// RVA: 0x3d613a4 VA: 0x75963793a4
	public Int32 get_instId() { }
	// RVA: 0x3d661b4 VA: 0x759637e1b4
	public String get_name() { }
	// RVA: 0x3d66250 VA: 0x759637e250
	public SpriteRenderData get_portrait() { }
	// RVA: 0x3d662f0 VA: 0x759637e2f0
	public Int32 get_mood() { }
	// RVA: 0x3d6140c VA: 0x759637940c
	public Int64 get_manpower() { }
	// RVA: 0x3d6250c VA: 0x759637a50c
	public Int32 get_realMood() { }
	// RVA: 0x3d66384 VA: 0x759637e384
	public IWorkshopBuildingBuff get_buildingBuff() { }
	// RVA: 0x3d66450 VA: 0x759637e450
	public Int32 get_maxMood() { }
	// RVA: 0x3d664e4 VA: 0x759637e4e4
	public CharManpowerState get_mpState() { }
	// RVA: 0x3d61474 VA: 0x7596379474
	public Void .ctor() { }
}
```