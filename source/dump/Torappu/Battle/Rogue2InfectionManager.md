# Rogue2InfectionManager

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 _maxInfectionCount`

- `String _projectileKey`

- `String _projectileAbilityName`

- `String _mutationEffectDeckBuffKey`

- `String _ascensionEffectDeckBuffKey`

- `BuffData _originalInfectedEffectBuffData`

- `BuffData _ascensionBuffData`

- `Blackboard m_infectedBlackboard`

- `Int32 m_maxInfectionCount`

- `BuffData m_infectedBuffData`


## Methods

- `Void _OnGameReady(Object)`

- `Void _OnCharacterLocate(Object)`

- `Void _OnGameOver(Object)`

- `Void _RegisterOriginalCharBuff(UInt32, Blackboard)`

- `Void _GenerateInfectionBuffData()`

- `Void _CheckAndCreateInfectionCardBuff(String)`

- `Void _CreateCardEffect(List`1, CardEffectType)`

- `Void _OnOriginallyAscendedCharacterBorn(Character)`

- `Void _OnOriginallyInfectedCharacterBorn(Character, Int32)`

- `Void _OnClearCharacterBorn(Character)`

- `Void _DoActiveInfection(Character)`

- `Boolean _TryInfectCharacterOnTile(Character, GridPosition)`

- `Boolean _DecAndCheckIfInfectionCountZero(UInt32)`

- `Void _Infect(Character)`

- `Void _Ascend(Character)`

- `Boolean _TryGetCardBuffKey(String, out)`

- `Void _CreateInfectionProjectile(Entity, Entity)`

- `BuffData _GetBuffData(String)`

- `Void _CreateCardEffectDeckBuff(Card, CardEffectType)`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Rogue2InfectionManager : EnvManager
{
	private Int32 _maxInfectionCount; // 0x28
	private List`1 _gridCheckList; // 0x30
	private List`1 _cardBuffKeys; // 0x38
	private String _projectileKey; // 0x40
	private String _projectileAbilityName; // 0x48
	private String _mutationEffectDeckBuffKey; // 0x50
	private String _ascensionEffectDeckBuffKey; // 0x58
	private List`1 _infectionBuffDataList; // 0x60
	private BuffData _originalInfectedEffectBuffData; // 0x68
	private BuffData _ascensionBuffData; // 0x70
	private Blackboard m_infectedBlackboard; // 0x78
	private Int32 m_maxInfectionCount; // 0x80
	private readonly Dictionary`2 m_originallyInfectedCharUid; // 0x88
	private readonly List`1 m_originallyAscendedCharUid; // 0x90
	private readonly List`1 m_infectedCharUid; // 0x98
	private readonly List`1 m_ascendedCharUid; // 0xa0
	private BuffData m_infectedBuffData; // 0xa8
	private const Single NEARBY_DISTANCE; // 0x0
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge __Hotfix0__OnGameReady; // 0x18
	private static DelegateBridge __Hotfix0__OnCharacterLocate; // 0x20
	private static DelegateBridge __Hotfix0__OnGameOver; // 0x28
	private static DelegateBridge __Hotfix0__RegisterOriginalCharBuff; // 0x30
	private static DelegateBridge __Hotfix0__GenerateInfectionBuffData; // 0x38
	private static DelegateBridge __Hotfix0__CheckAndCreateInfectionCardBuff; // 0x40
	private static DelegateBridge __Hotfix0__CreateCardEffect; // 0x48
	private static DelegateBridge __Hotfix0__OnOriginallyAscendedCharacterBorn; // 0x50
	private static DelegateBridge __Hotfix0__OnOriginallyInfectedCharacterBorn; // 0x58
	private static DelegateBridge __Hotfix0__OnClearCharacterBorn; // 0x60
	private static DelegateBridge __Hotfix0__DoActiveInfection; // 0x68
	private static DelegateBridge __Hotfix0__TryInfectCharacterOnTile; // 0x70
	private static DelegateBridge __Hotfix0__DecAndCheckIfInfectionCountZero; // 0x78
	private static DelegateBridge __Hotfix0__Infect; // 0x80
	private static DelegateBridge __Hotfix0__Ascend; // 0x88
	private static DelegateBridge __Hotfix0__CollectOriginallyInfectedCharactersInRange; // 0x90
	private static DelegateBridge __Hotfix0__TryGetCardBuffKey; // 0x98
	private static DelegateBridge __Hotfix0__CreateInfectionProjectile; // 0xa0
	private static DelegateBridge __Hotfix0__GetBuffData; // 0xa8
	private static DelegateBridge __Hotfix0__CreateCardEffectDeckBuff; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x4061b84 VA: 0x7596679b84
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x4061e20 VA: 0x7596679e20
	public override Void Init(GlobalEnvSystem envSystem) { }
	// RVA: 0x4061ee8 VA: 0x7596679ee8
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x4062064 VA: 0x759667a064
	private Void _OnGameReady(Object arg) { }
	// RVA: 0x4062898 VA: 0x759667a898
	private Void _OnCharacterLocate(Object arg) { }
	// RVA: 0x4063248 VA: 0x759667b248
	private Void _OnGameOver(Object arg) { }
	// RVA: 0x40622bc VA: 0x759667a2bc
	private Void _RegisterOriginalCharBuff(UInt32 uniqueId, Blackboard bb) { }
	// RVA: 0x40625b0 VA: 0x759667a5b0
	private Void _GenerateInfectionBuffData() { }
	// RVA: 0x4063508 VA: 0x759667b508
	private Void _CheckAndCreateInfectionCardBuff(String buffKey) { }
	// RVA: 0x40626a0 VA: 0x759667a6a0
	private Void _CreateCardEffect(List`1 uids, CardEffectType effectType) { }
	// RVA: 0x4062b40 VA: 0x759667ab40
	private Void _OnOriginallyAscendedCharacterBorn(Character character) { }
	// RVA: 0x4062c70 VA: 0x759667ac70
	private Void _OnOriginallyInfectedCharacterBorn(Character character, Int32 infectionCount) { }
	// RVA: 0x4062e8c VA: 0x759667ae8c
	private Void _OnClearCharacterBorn(Character character) { }
	// RVA: 0x4063a2c VA: 0x759667ba2c
	private Void _DoActiveInfection(Character character) { }
	// RVA: 0x4064ae4 VA: 0x759667cae4
	private Boolean _TryInfectCharacterOnTile(Character source, GridPosition gridPosition) { }
	// RVA: 0x406472c VA: 0x759667c72c
	private Boolean _DecAndCheckIfInfectionCountZero(UInt32 uid) { }
	// RVA: 0x4064348 VA: 0x759667c348
	private Void _Infect(Character character) { }
	// RVA: 0x4064824 VA: 0x759667c824
	private Void _Ascend(Character character) { }
	// RVA: 0x4063ca0 VA: 0x759667bca0
	private List`1 _CollectOriginallyInfectedCharactersInRange(Character source) { }
	// RVA: 0x406378c VA: 0x759667b78c
	private Boolean _TryGetCardBuffKey(String coreBuffKey, out String cardBuffKey) { }
	// RVA: 0x4064564 VA: 0x759667c564
	private Void _CreateInfectionProjectile(Entity source, Entity target) { }
	// RVA: 0x406334c VA: 0x759667b34c
	private BuffData _GetBuffData(String buffKey) { }
	// RVA: 0x40638c0 VA: 0x759667b8c0
	private Void _CreateCardEffectDeckBuff(Card card, CardEffectType effectType) { }
	// RVA: 0x4064d1c VA: 0x759667cd1c
	public Void .ctor() { }
	// RVA: 0x4064f80 VA: 0x759667cf80
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
	// RVA: 0x4064f88 VA: 0x759667cf88
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x4064f90 VA: 0x759667cf90
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
}
```