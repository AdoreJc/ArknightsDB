# TokenCard

**Namespace:** ` `


## Fields

- `CardPolicy m_cardPolicy`

- `Boolean m_hostIsAlive`

- `Int32 m_spawnedCnt`

- `Boolean m_rechargeOnlyOnce`

- `Int32 m_rechargeCnt`

- `Boolean m_isInfinity`

- `Boolean m_ignoreExcludeFromBattle`

- `Boolean m_notShowInDeck`

- `Boolean m_asRewardCardInLegionMode`

- `Boolean m_isRallyPoint`

- `ObscuredInt <maxDeployCnt>k__BackingField`

- `ObscuredInt <maxDeckStackCnt>k__BackingField`


## Properties

- `Boolean hostIsAlive`

- `ObscuredInt maxDeployCnt`

- `ObscuredInt maxDeckStackCnt`


## Methods

- `Boolean get_hostIsAlive()`

- `ObscuredInt get_maxDeployCnt()`

- `Void set_maxDeployCnt(ObscuredInt)`

- `ObscuredInt get_maxDeckStackCnt()`

- `Void set_maxDeckStackCnt(ObscuredInt)`

- `Void ForceRecharge(Int32, RechargeTiming, Boolean)`

- `Void OnHostSpawned()`

- `Void OnHostRecycled()`

- `Boolean <>xLuaBaseProxy_get_ignoreExcludeFromBattle()`

- `Boolean <>xLuaBaseProxy_get_notShowInDeck()`

- `Boolean <>xLuaBaseProxy_get_asRewardCardInLegionMode()`

- `Boolean <>xLuaBaseProxy_get_isHidden()`

- `Boolean <>xLuaBaseProxy_get_readyToSpawn()`

- `Int32 <>xLuaBaseProxy_get_cost()`

- `Int32 <>xLuaBaseProxy_get_rawCost()`

- `Boolean <>xLuaBaseProxy_get_isMaxDeployed()`

- `Void <>xLuaBaseProxy_Init(IList`1)`

- `Void <>xLuaBaseProxy_Recharge(Int32, RechargeTiming, Boolean)`

- `Void <>xLuaBaseProxy_OnSpawned(Character, Direction, GridPosition, Boolean)`

- `Void <>xLuaBaseProxy_OnRecycle()`

- `Void <>xLuaBaseProxy_OnFetchDataFromPrefab(Character)`

- `Void <>xLuaBaseProxy_OnReset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TokenCard : Card
{
	private CardPolicy m_cardPolicy; // 0x1a0
	private Boolean m_hostIsAlive; // 0x1a4
	private Int32 m_spawnedCnt; // 0x1a8
	private Boolean m_rechargeOnlyOnce; // 0x1ac
	private Int32 m_rechargeCnt; // 0x1b0
	private Boolean m_isInfinity; // 0x1b4
	private Boolean m_ignoreExcludeFromBattle; // 0x1b5
	private Boolean m_notShowInDeck; // 0x1b6
	private Boolean m_asRewardCardInLegionMode; // 0x1b7
	private Boolean m_isRallyPoint; // 0x1b8
	private ObscuredInt <maxDeployCnt>k__BackingField; // 0x1bc
	private ObscuredInt <maxDeckStackCnt>k__BackingField; // 0x1d0
	private static DelegateBridge __Hotfix0_get_cardPolicy; // 0x0
	private static DelegateBridge __Hotfix0_get_isInfinity; // 0x8
	private static DelegateBridge __Hotfix0_get_ignoreExcludeFromBattle; // 0x10
	private static DelegateBridge __Hotfix0_get_notShowInDeck; // 0x18
	private static DelegateBridge __Hotfix0_get_asRewardCardInLegionMode; // 0x20
	private static DelegateBridge __Hotfix0_get_isFull; // 0x28
	private static DelegateBridge __Hotfix0_get_isHidden; // 0x30
	private static DelegateBridge __Hotfix0_get_readyToSpawn; // 0x38
	private static DelegateBridge __Hotfix0_get_cost; // 0x40
	private static DelegateBridge __Hotfix0_get_rawCost; // 0x48
	private static DelegateBridge __Hotfix0_get_isMaxDeployed; // 0x50
	private static DelegateBridge __Hotfix0_get_hostIsAlive; // 0x58
	private static DelegateBridge __Hotfix0_get_initialCnt; // 0x60
	private static DelegateBridge __Hotfix0_get_maxDeployCnt; // 0x68
	private static DelegateBridge __Hotfix0_set_maxDeployCnt; // 0x70
	private static DelegateBridge __Hotfix0_get_maxDeckStackCnt; // 0x78
	private static DelegateBridge __Hotfix0_set_maxDeckStackCnt; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88
	private static DelegateBridge __Hotfix0_Init; // 0x90
	private static DelegateBridge __Hotfix0_TouchPrefab; // 0x98
	private static DelegateBridge __Hotfix0_SpawnInternal; // 0xa0
	private static DelegateBridge __Hotfix0_CreateDummy; // 0xa8
	private static DelegateBridge __Hotfix0_Recharge; // 0xb0
	private static DelegateBridge __Hotfix0_ForceRecharge; // 0xb8
	private static DelegateBridge __Hotfix0_OnHostSpawned; // 0xc0
	private static DelegateBridge __Hotfix0_OnHostRecycled; // 0xc8
	private static DelegateBridge __Hotfix0_OnSpawned; // 0xd0
	private static DelegateBridge __Hotfix0_OnRecycle; // 0xd8
	private static DelegateBridge __Hotfix0_OnFetchDataFromPrefab; // 0xe0
	private static DelegateBridge __Hotfix0_OnReset; // 0xe8

	public override CardPolicy cardPolicy { get; }
	public override Boolean isInfinity { get; }
	public override Boolean ignoreExcludeFromBattle { get; }
	public override Boolean notShowInDeck { get; }
	public override Boolean asRewardCardInLegionMode { get; }
	public override Boolean isFull { get; }
	public override Boolean isHidden { get; }
	public override Boolean readyToSpawn { get; }
	public override Int32 cost { get; }
	protected override Int32 rawCost { get; }
	public override Boolean isMaxDeployed { get; }
	public Boolean hostIsAlive { get; }
	protected override Int32 initialCnt { get; }
	protected ObscuredInt maxDeployCnt { get; set; }
	protected ObscuredInt maxDeckStackCnt { get; set; }

	// RVA: 0x3fb68d4 VA: 0x75965ce8d4
	public override CardPolicy get_cardPolicy() { }
	// RVA: 0x3fb693c VA: 0x75965ce93c
	public override Boolean get_isInfinity() { }
	// RVA: 0x3fb69a4 VA: 0x75965ce9a4
	public override Boolean get_ignoreExcludeFromBattle() { }
	// RVA: 0x3fb6a0c VA: 0x75965cea0c
	public override Boolean get_notShowInDeck() { }
	// RVA: 0x3fb6a94 VA: 0x75965cea94
	public override Boolean get_asRewardCardInLegionMode() { }
	// RVA: 0x3fb6afc VA: 0x75965ceafc
	public override Boolean get_isFull() { }
	// RVA: 0x3fb6c54 VA: 0x75965cec54
	public override Boolean get_isHidden() { }
	// RVA: 0x3fb6cd8 VA: 0x75965cecd8
	public override Boolean get_readyToSpawn() { }
	// RVA: 0x3fb6d80 VA: 0x75965ced80
	public override Int32 get_cost() { }
	// RVA: 0x3fb6eac VA: 0x75965ceeac
	protected override Int32 get_rawCost() { }
	// RVA: 0x3fb6f80 VA: 0x75965cef80
	public override Boolean get_isMaxDeployed() { }
	// RVA: 0x3fb70f0 VA: 0x75965cf0f0
	public Boolean get_hostIsAlive() { }
	// RVA: 0x3fb7158 VA: 0x75965cf158
	protected override Int32 get_initialCnt() { }
	// RVA: 0x3fb7058 VA: 0x75965cf058
	protected ObscuredInt get_maxDeployCnt() { }
	// RVA: 0x3fb71d4 VA: 0x75965cf1d4
	private Void set_maxDeployCnt(ObscuredInt value) { }
	// RVA: 0x3fb6bc4 VA: 0x75965cebc4
	protected ObscuredInt get_maxDeckStackCnt() { }
	// RVA: 0x3fb7270 VA: 0x75965cf270
	private Void set_maxDeckStackCnt(ObscuredInt value) { }
	// RVA: 0x3fb7308 VA: 0x75965cf308
	public Void .ctor(BattleCharacterData data, Deck deck, IList`1 modifiers, IList`1 costModifier, IList`1 miscModifiers) { }
	// RVA: 0x3fb73ec VA: 0x75965cf3ec
	public override Void Init(IList`1 deckModifiers) { }
	// RVA: 0x3fb7708 VA: 0x75965cf708
	public override Boolean TouchPrefab(Action`1 cb) { }
	// RVA: 0x3fb77d0 VA: 0x75965cf7d0
	protected override Character SpawnInternal(Direction direction, Tile tile, Boolean spawnManually, SpawnDetailsTracker spawnDetailsTracker) { }
	// RVA: 0x3fb78ac VA: 0x75965cf8ac
	public override Character CreateDummy(AdditionalBuildCondition additionalBuildCondition, Boolean useOutline) { }
	// RVA: 0x3fb79e0 VA: 0x75965cf9e0
	public override Void Recharge(Int32 cnt, RechargeTiming timing, Boolean refreshRemainingCnt) { }
	// RVA: 0x3fb7b94 VA: 0x75965cfb94
	public Void ForceRecharge(Int32 cnt, RechargeTiming timing, Boolean refreshRemainingCnt) { }
	// RVA: 0x3fb7df4 VA: 0x75965cfdf4
	public Void OnHostSpawned() { }
	// RVA: 0x3fb7e60 VA: 0x75965cfe60
	public Void OnHostRecycled() { }
	// RVA: 0x3fb7ec8 VA: 0x75965cfec8
	protected override Void OnSpawned(Character inst, Direction direction, GridPosition gridPos, Boolean spawnManually) { }
	// RVA: 0x3fb7f9c VA: 0x75965cff9c
	public override Void OnRecycle() { }
	// RVA: 0x3fb8028 VA: 0x75965d0028
	protected override Void OnFetchDataFromPrefab(Character character) { }
	// RVA: 0x3fb81b4 VA: 0x75965d01b4
	public override Void OnReset() { }
	// RVA: 0x3fb8238 VA: 0x75965d0238
	private Boolean <>xLuaBaseProxy_get_ignoreExcludeFromBattle() { }
	// RVA: 0x3fb8240 VA: 0x75965d0240
	private Boolean <>xLuaBaseProxy_get_notShowInDeck() { }
	// RVA: 0x3fb8248 VA: 0x75965d0248
	private Boolean <>xLuaBaseProxy_get_asRewardCardInLegionMode() { }
	// RVA: 0x3fb8250 VA: 0x75965d0250
	private Boolean <>xLuaBaseProxy_get_isHidden() { }
	// RVA: 0x3fb8258 VA: 0x75965d0258
	private Boolean <>xLuaBaseProxy_get_readyToSpawn() { }
	// RVA: 0x3fb8260 VA: 0x75965d0260
	private Int32 <>xLuaBaseProxy_get_cost() { }
	// RVA: 0x3fb8268 VA: 0x75965d0268
	private Int32 <>xLuaBaseProxy_get_rawCost() { }
	// RVA: 0x3fb8270 VA: 0x75965d0270
	private Boolean <>xLuaBaseProxy_get_isMaxDeployed() { }
	// RVA: 0x3fb8278 VA: 0x75965d0278
	private Void <>xLuaBaseProxy_Init(IList`1 P0) { }
	// RVA: 0x3fb8280 VA: 0x75965d0280
	private Void <>xLuaBaseProxy_Recharge(Int32 P0, RechargeTiming P1, Boolean P2) { }
	// RVA: 0x3fb828c VA: 0x75965d028c
	private Void <>xLuaBaseProxy_OnSpawned(Character P0, Direction P1, GridPosition P2, Boolean P3) { }
	// RVA: 0x3fb8298 VA: 0x75965d0298
	private Void <>xLuaBaseProxy_OnRecycle() { }
	// RVA: 0x3fb82a0 VA: 0x75965d02a0
	private Void <>xLuaBaseProxy_OnFetchDataFromPrefab(Character P0) { }
	// RVA: 0x3fb82a8 VA: 0x75965d02a8
	private Void <>xLuaBaseProxy_OnReset() { }
}
```