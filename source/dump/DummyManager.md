# DummyManager

**Namespace:** ` `


## Fields

- `Character <activeCharacter>k__BackingField`

- `Boolean <needForceUpdate>k__BackingField`

- `AutoChessGameMode m_gameMode`


## Properties

- `Character activeCharacter`

- `Boolean needForceUpdate`

- `TileCache tileCache`

- `AutoChessGameMode gameMode`

- `Boolean isAsyncBuildDone`


## Methods

- `Character get_activeCharacter()`

- `Void set_activeCharacter(Character)`

- `Boolean get_needForceUpdate()`

- `Void set_needForceUpdate(Boolean)`

- `TileCache get_tileCache()`

- `AutoChessGameMode get_gameMode()`

- `Void OnTick(FP)`

- `Void _OnStateChanged(Int32, Int32)`

- `Boolean get_isAsyncBuildDone()`

- `Void _InitEffectContiner()`

- `Character GetCharacter(Tile)`

- `Character GetCharacter(GridPosition)`

- `Boolean ContainsKey(Tile)`

- `Tile GetTile(Character)`

- `Void Add(Tile, Character)`

- `Void Remove(Tile)`

- `Void SetCharacter(Tile, Character, Direction)`

- `Void _OnCharacterPlaced(Character, Direction, Tile)`

- `Void SetCharacterDirection(Tile, Character, Direction)`

- `IEnumerator _PlayIdleAfterBorn(Character, Boolean, AutoChessDataCenter, FP)`

- `Character MarkLeaving(Tile)`

- `Void MarkReturned(Character, Tile)`

- `Void FreezeAll()`

- `Void UnFreezeAll()`

- `Void CreateDummyOnTile(AutoChessUnitQuery, Direction, Tile)`

- `Void _DoCreateOnTile(AutoChessUnitQuery, Direction, Tile)`

- `Character CreateDummy(AutoChessUnitQuery)`

- `Void _DoDefaultAnimIfNeed(Character)`

- `Void _CreateIdleEffectIfNeed(Character)`

- `Void _CreateGoldEffectIfNeed(AutoChessUnitQuery, Character)`

- `Void CreateDupEffectIfNeed(Character, Tile, Boolean)`

- `Character _CreateDummyChess(AutoChessUnitQuery)`

- `IEnumerator FinishAllDummy(Single)`

- `Void BuildShopChess(ShopChess, Tile)`

- `Void FinishDummyByTile(Tile)`

- `Void FinishDummy(Character)`

- `Void FinishDupEffectIfNeed(Character)`

- `Void _FinishEffectByEffectGroup(String, Character)`

- `Void OnNotifyUpdate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DummyManager : IHotfixable
{
	private const Int32 CHAR_INST_ID_OFFSET; // 0x0
	private const Int32 TOKEN_INST_ID_OFFSET; // 0x0
	private const Int32 TRAP_INST_ID_OFFSET; // 0x0
	private Character <activeCharacter>k__BackingField; // 0x10
	private Boolean <needForceUpdate>k__BackingField; // 0x18
	private ListDict`2 m_effectContainer; // 0x20
	private List`1 m_dummyCharacters; // 0x28
	private List`1 m_tileNeedRemove; // 0x30
	private Queue`1 m_createDummyQueue; // 0x38
	private AutoChessGameMode m_gameMode; // 0x40
	private static DelegateBridge __Hotfix0_get_shopTiles; // 0x0
	private static DelegateBridge __Hotfix0_get_handTiles; // 0x8
	private static DelegateBridge __Hotfix0_get_validHandTiles; // 0x10
	private static DelegateBridge __Hotfix0_get_battleTiles; // 0x18
	private static DelegateBridge __Hotfix0_get_activeCharacter; // 0x20
	private static DelegateBridge __Hotfix0_set_activeCharacter; // 0x28
	private static DelegateBridge __Hotfix0_get_needForceUpdate; // 0x30
	private static DelegateBridge __Hotfix0_set_needForceUpdate; // 0x38
	private static DelegateBridge __Hotfix0_get_tileCache; // 0x40
	private static DelegateBridge __Hotfix0_get_gameMode; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50
	private static DelegateBridge __Hotfix0_OnTick; // 0x58
	private static DelegateBridge __Hotfix0__OnStateChanged; // 0x60
	private static DelegateBridge __Hotfix0_get_isAsyncBuildDone; // 0x68
	private static DelegateBridge __Hotfix0__InitEffectContiner; // 0x70
	private static DelegateBridge __Hotfix0_GetCharacter; // 0x78
	private static DelegateBridge __Hotfix1_GetCharacter; // 0x80
	private static DelegateBridge __Hotfix0_ContainsKey; // 0x88
	private static DelegateBridge __Hotfix0_GetTile; // 0x90
	private static DelegateBridge __Hotfix0_Add; // 0x98
	private static DelegateBridge __Hotfix0_Remove; // 0xa0
	private static DelegateBridge __Hotfix0_SetCharacter; // 0xa8
	private static DelegateBridge __Hotfix0__OnCharacterPlaced; // 0xb0
	private static DelegateBridge __Hotfix0_SetCharacterDirection; // 0xb8
	private static DelegateBridge __Hotfix0__PlayIdleAfterBorn; // 0xc0
	private static DelegateBridge __Hotfix0_MarkLeaving; // 0xc8
	private static DelegateBridge __Hotfix0_MarkReturned; // 0xd0
	private static DelegateBridge __Hotfix0_FreezeAll; // 0xd8
	private static DelegateBridge __Hotfix0_UnFreezeAll; // 0xe0
	private static DelegateBridge __Hotfix0_CreateDummyOnTile; // 0xe8
	private static DelegateBridge __Hotfix0__DoCreateOnTile; // 0xf0
	private static DelegateBridge __Hotfix0_CreateDummy; // 0xf8
	private static DelegateBridge __Hotfix0__DoDefaultAnimIfNeed; // 0x100
	private static DelegateBridge __Hotfix0__CreateIdleEffectIfNeed; // 0x108
	private static DelegateBridge __Hotfix0__CreateGoldEffectIfNeed; // 0x110
	private static DelegateBridge __Hotfix0_CreateDupEffectIfNeed; // 0x118
	private static DelegateBridge __Hotfix0__CreateDummyChess; // 0x120
	private static DelegateBridge __Hotfix0_FinishAllDummy; // 0x128
	private static DelegateBridge __Hotfix0_BuildShopChess; // 0x130
	private static DelegateBridge __Hotfix0_FinishDummyByTile; // 0x138
	private static DelegateBridge __Hotfix0_FinishDummy; // 0x140
	private static DelegateBridge __Hotfix0_FinishDupEffectIfNeed; // 0x148
	private static DelegateBridge __Hotfix0__FinishEffectByEffectGroup; // 0x150
	private static DelegateBridge __Hotfix0_OnNotifyUpdate; // 0x158

	public IEnumerable`1 shopTiles { get; }
	public IEnumerable`1 handTiles { get; }
	public IEnumerable`1 validHandTiles { get; }
	public IEnumerable`1 battleTiles { get; }
	public Character activeCharacter { get; set; }
	public Boolean needForceUpdate { get; set; }
	private TileCache tileCache { get; }
	private AutoChessGameMode gameMode { get; }
	public Boolean isAsyncBuildDone { get; }

	// RVA: 0x1ca3f3c VA: 0x75942bbf3c
	public IEnumerable`1 get_shopTiles() { }
	// RVA: 0x1ca3c14 VA: 0x75942bbc14
	public IEnumerable`1 get_handTiles() { }
	// RVA: 0x1ca40b0 VA: 0x75942bc0b0
	public IEnumerable`1 get_validHandTiles() { }
	// RVA: 0x1ca3de4 VA: 0x75942bbde4
	public IEnumerable`1 get_battleTiles() { }
	// RVA: 0x1ca4198 VA: 0x75942bc198
	public Character get_activeCharacter() { }
	// RVA: 0x1ca4200 VA: 0x75942bc200
	public Void set_activeCharacter(Character value) { }
	// RVA: 0x1ca0980 VA: 0x75942b8980
	public Boolean get_needForceUpdate() { }
	// RVA: 0x1ca4284 VA: 0x75942bc284
	public Void set_needForceUpdate(Boolean value) { }
	// RVA: 0x1ca4024 VA: 0x75942bc024
	private TileCache get_tileCache() { }
	// RVA: 0x1ca4304 VA: 0x75942bc304
	private AutoChessGameMode get_gameMode() { }
	// RVA: 0x1ca43b4 VA: 0x75942bc3b4
	public Void .ctor() { }
	// RVA: 0x1ca4914 VA: 0x75942bc914
	public Void OnTick(FP deltaTime) { }
	// RVA: 0x1ca4bdc VA: 0x75942bcbdc
	private Void _OnStateChanged(Int32 stateId, Int32 stateIdNew) { }
	// RVA: 0x1ca4cb8 VA: 0x75942bccb8
	public Boolean get_isAsyncBuildDone() { }
	// RVA: 0x1ca463c VA: 0x75942bc63c
	private Void _InitEffectContiner() { }
	// RVA: 0x1ca0e9c VA: 0x75942b8e9c
	public Character GetCharacter(Tile tile) { }
	// RVA: 0x1ca26d4 VA: 0x75942ba6d4
	public Character GetCharacter(GridPosition pos) { }
	// RVA: 0x1ca4d48 VA: 0x75942bcd48
	public Boolean ContainsKey(Tile tile) { }
	// RVA: 0x1ca4f8c VA: 0x75942bcf8c
	public Tile GetTile(Character character) { }
	// RVA: 0x1ca5210 VA: 0x75942bd210
	public Void Add(Tile tile, Character character) { }
	// RVA: 0x1ca2938 VA: 0x75942ba938
	public Void Remove(Tile tile) { }
	// RVA: 0x1ca5404 VA: 0x75942bd404
	public Void SetCharacter(Tile tile, Character character, Direction dir) { }
	// RVA: 0x1ca5528 VA: 0x75942bd528
	private Void _OnCharacterPlaced(Character character, Direction dir, Tile tile) { }
	// RVA: 0x1ca5d38 VA: 0x75942bdd38
	public Void SetCharacterDirection(Tile tile, Character character, Direction dir) { }
	// RVA: 0x1ca6008 VA: 0x75942be008
	private IEnumerator _PlayIdleAfterBorn(Character character, Boolean isShop, AutoChessDataCenter center, FP time) { }
	// RVA: 0x1ca6130 VA: 0x75942be130
	public Character MarkLeaving(Tile tile) { }
	// RVA: 0x1ca640c VA: 0x75942be40c
	public Void MarkReturned(Character character, Tile tile) { }
	// RVA: 0x1c9fd48 VA: 0x75942b7d48
	public Void FreezeAll() { }
	// RVA: 0x1ca03fc VA: 0x75942b83fc
	public Void UnFreezeAll() { }
	// RVA: 0x1ca3868 VA: 0x75942bb868
	public Void CreateDummyOnTile(AutoChessUnitQuery query, Direction direction, Tile tile) { }
	// RVA: 0x1ca49fc VA: 0x75942bc9fc
	private Void _DoCreateOnTile(AutoChessUnitQuery query, Direction dir, Tile tile) { }
	// RVA: 0x1ca6730 VA: 0x75942be730
	public Character CreateDummy(AutoChessUnitQuery query) { }
	// RVA: 0x1ca724c VA: 0x75942bf24c
	private Void _DoDefaultAnimIfNeed(Character character) { }
	// RVA: 0x1ca6ff4 VA: 0x75942beff4
	private Void _CreateIdleEffectIfNeed(Character character) { }
	// RVA: 0x1ca6d38 VA: 0x75942bed38
	private Void _CreateGoldEffectIfNeed(AutoChessUnitQuery query, Character character) { }
	// RVA: 0x1ca158c VA: 0x75942b958c
	public Void CreateDupEffectIfNeed(Character character, Tile tile, Boolean isTrap) { }
	// RVA: 0x1ca68e0 VA: 0x75942be8e0
	private Character _CreateDummyChess(AutoChessUnitQuery query) { }
	// RVA: 0x1ca74f0 VA: 0x75942bf4f0
	public IEnumerator FinishAllDummy(Single finishTiming) { }
	// RVA: 0x1ca2b00 VA: 0x75942bab00
	public Void BuildShopChess(ShopChess shopChess, Tile tile) { }
	// RVA: 0x1ca2bd8 VA: 0x75942babd8
	public Void FinishDummyByTile(Tile tile) { }
	// RVA: 0x1ca27d8 VA: 0x75942ba7d8
	public Void FinishDummy(Character character) { }
	// RVA: 0x1ca73a8 VA: 0x75942bf3a8
	public Void FinishDupEffectIfNeed(Character character) { }
	// RVA: 0x1ca75dc VA: 0x75942bf5dc
	private Void _FinishEffectByEffectGroup(String group, Character character) { }
	// RVA: 0x1ca7748 VA: 0x75942bf748
	public Void OnNotifyUpdate() { }
}
```