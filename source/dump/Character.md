# Character

**Namespace:** ` `


## Fields

- `BuildingCharModel m_buildingChar`

- `CharacterCardViewModel m_cardViewModel`

- `SpriteRenderData m_portraitSprite`

- `Sprite m_faceSprite`

- `Buff m_buff`


## Properties

- `String name`

- `Int32 instId`

- `SpriteRenderData portrait`

- `Sprite face`

- `BuildingCharModel charModel`

- `IMeetingBuildingBuff buildingBuff`


## Methods

- `Void _Init(BuildingCharModel)`

- `Void Setup(BuildingCharModel)`

- `String get_name()`

- `Int32 get_instId()`

- `SpriteRenderData get_portrait()`

- `Sprite get_face()`

- `BuildingCharModel get_charModel()`

- `IMeetingBuildingBuff get_buildingBuff()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class Character : IMeetingStationaryCharacter, IHotfixable
{
	private BuildingCharModel m_buildingChar; // 0x10
	private CharacterCardViewModel m_cardViewModel; // 0x80
	private SpriteRenderData m_portraitSprite; // 0x88
	private Sprite m_faceSprite; // 0xb0
	private Buff m_buff; // 0xb8
	private static DelegateBridge __Hotfix0__Init; // 0x0
	private static DelegateBridge __Hotfix0_Setup; // 0x8
	private static DelegateBridge __Hotfix0_get_name; // 0x10
	private static DelegateBridge __Hotfix0_get_instId; // 0x18
	private static DelegateBridge __Hotfix0_get_portrait; // 0x20
	private static DelegateBridge __Hotfix0_get_face; // 0x28
	private static DelegateBridge __Hotfix0_get_charModel; // 0x30
	private static DelegateBridge __Hotfix0_get_buildingBuff; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public String name { get; }
	public Int32 instId { get; }
	public SpriteRenderData portrait { get; }
	public Sprite face { get; }
	public BuildingCharModel charModel { get; }
	public IMeetingBuildingBuff buildingBuff { get; }

	// RVA: 0x3de7840 VA: 0x75963ff840
	private Void _Init(BuildingCharModel buildingChar) { }
	// RVA: 0x3de1298 VA: 0x75963f9298
	public Void Setup(BuildingCharModel buildingChar) { }
	// RVA: 0x3de7aec VA: 0x75963ffaec
	public String get_name() { }
	// RVA: 0x3de7b88 VA: 0x75963ffb88
	public Int32 get_instId() { }
	// RVA: 0x3de7bf0 VA: 0x75963ffbf0
	public SpriteRenderData get_portrait() { }
	// RVA: 0x3de7c90 VA: 0x75963ffc90
	public Sprite get_face() { }
	// RVA: 0x3de7cf8 VA: 0x75963ffcf8
	public BuildingCharModel get_charModel() { }
	// RVA: 0x3de7d9c VA: 0x75963ffd9c
	public IMeetingBuildingBuff get_buildingBuff() { }
	// RVA: 0x3de1228 VA: 0x75963f9228
	public Void .ctor() { }
}
```