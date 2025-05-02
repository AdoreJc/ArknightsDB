# DeckMiscTalent

**Namespace:** `Torappu.Battle`


## Fields

- `Options _options`

- `Boolean _dontOccupyDeployCnt`

- `BuildableType _additionBuildableType`

- `AdvancedBuildableMask _additionMask`

- `Boolean m_dontOccupyDeployCnt`

- `Int32 m_additionBuildableType`

- `Int32 m_additionMask`


## Methods

- `MiscSettingModifier CreateDeckRuntimeMiscModifier(Card)`

- `Boolean <>xLuaBaseProxy_get_attachInDummy()`

- `Boolean <>xLuaBaseProxy_get_affectInDeck()`

- `String <>xLuaBaseProxy_get_talentKey()`

- `Void <>xLuaBaseProxy_AssignData(TalentData, Unit, Delta)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class DeckMiscTalent : BasicTalent
{
	private Options _options; // 0x48
	private Boolean _dontOccupyDeployCnt; // 0x50
	private BuildableType _additionBuildableType; // 0x54
	private AdvancedBuildableMask _additionMask; // 0x58
	private Boolean m_dontOccupyDeployCnt; // 0x5c
	private Int32 m_additionBuildableType; // 0x60
	private Int32 m_additionMask; // 0x64
	private static DelegateBridge __Hotfix0_get_attachInDummy; // 0x0
	private static DelegateBridge __Hotfix0_get_affectInDeck; // 0x8
	private static DelegateBridge __Hotfix0_get_talentKey; // 0x10
	private static DelegateBridge __Hotfix0_AssignData; // 0x18
	private static DelegateBridge __Hotfix0_CreateDeckRuntimeMiscModifier; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Boolean attachInDummy { get; }
	public override Boolean affectInDeck { get; }
	public override String talentKey { get; }

	// RVA: 0x1b7904c VA: 0x759419104c
	public override Boolean get_attachInDummy() { }
	// RVA: 0x1b790b4 VA: 0x75941910b4
	public override Boolean get_affectInDeck() { }
	// RVA: 0x1b7911c VA: 0x759419111c
	public override String get_talentKey() { }
	// RVA: 0x1b791a8 VA: 0x75941911a8
	public override Void AssignData(TalentData data, Unit owner, Delta modifier) { }
	// RVA: 0x1b79318 VA: 0x7594191318
	public MiscSettingModifier CreateDeckRuntimeMiscModifier(Card sourceCard) { }
	// RVA: 0x1b7945c VA: 0x759419145c
	public Void .ctor() { }
	// RVA: 0x1b794c8 VA: 0x75941914c8
	private Boolean <>xLuaBaseProxy_get_attachInDummy() { }
	// RVA: 0x1b794cc VA: 0x75941914cc
	private Boolean <>xLuaBaseProxy_get_affectInDeck() { }
	// RVA: 0x1b794d0 VA: 0x75941914d0
	private String <>xLuaBaseProxy_get_talentKey() { }
	// RVA: 0x1b794d4 VA: 0x75941914d4
	private Void <>xLuaBaseProxy_AssignData(TalentData P0, Unit P1, Delta P2) { }
}
```