# CharacterCard

**Namespace:** ` `


## Methods

- `Boolean <>xLuaBaseProxy_CheckBuildable(Tile, Boolean, Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CharacterCard : Card
{
	private static DelegateBridge __Hotfix0_get_isInfinity; // 0x0
	private static DelegateBridge __Hotfix0_get_isFull; // 0x8
	private static DelegateBridge __Hotfix0_get_initialCnt; // 0x10
	private static DelegateBridge __Hotfix0_get_cardPolicy; // 0x18
	private static DelegateBridge __Hotfix0_TouchPrefab; // 0x20
	private static DelegateBridge __Hotfix0_SpawnInternal; // 0x28
	private static DelegateBridge __Hotfix0_CreateDummy; // 0x30
	private static DelegateBridge __Hotfix0_CheckBuildable; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override Boolean isInfinity { get; }
	public override Boolean isFull { get; }
	protected override Int32 initialCnt { get; }
	public override CardPolicy cardPolicy { get; }

	// RVA: 0x3fb628c VA: 0x75965ce28c
	public override Boolean get_isInfinity() { }
	// RVA: 0x3fb62f4 VA: 0x75965ce2f4
	public override Boolean get_isFull() { }
	// RVA: 0x3fb635c VA: 0x75965ce35c
	protected override Int32 get_initialCnt() { }
	// RVA: 0x3fb63c4 VA: 0x75965ce3c4
	public override CardPolicy get_cardPolicy() { }
	// RVA: 0x3fb642c VA: 0x75965ce42c
	public override Boolean TouchPrefab(Action`1 cb) { }
	// RVA: 0x3fb64f4 VA: 0x75965ce4f4
	protected override Character SpawnInternal(Direction direction, Tile tile, Boolean spawnManually, SpawnDetailsTracker spawnDetailsTracker) { }
	// RVA: 0x3fb65d0 VA: 0x75965ce5d0
	public override Character CreateDummy(AdditionalBuildCondition additionalBuildCondition, Boolean useOutline) { }
	// RVA: 0x3fb66b0 VA: 0x75965ce6b0
	public override Boolean CheckBuildable(Tile tile, Boolean checkHost, Boolean spawnManually, Boolean ignoreAdvancedBuildableMask) { }
	// RVA: 0x3fb67f0 VA: 0x75965ce7f0
	public Void .ctor(BattleCharacterData data, Deck deck, IList`1 modifiers, IList`1 runtimeCostModifiers, IList`1 miscModifiers) { }
	// RVA: 0x3fb68c0 VA: 0x75965ce8c0
	private Boolean <>xLuaBaseProxy_CheckBuildable(Tile P0, Boolean P1, Boolean P2, Boolean P3) { }
}
```