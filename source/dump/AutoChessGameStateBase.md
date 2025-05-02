# AutoChessGameStateBase

**Namespace:** ` `


## Properties

- `Boolean isActiveNode`

- `GameStatus status`

- `AdvancedRuneHolder runeHolder`


## Methods

- `Boolean get_isActiveNode()`

- `GameStatus get_status()`

- `AdvancedRuneHolder get_runeHolder()`

- `Boolean CheckSwitchOut(Int32)`

- `Void ReloadGame(List`1, LevelData, out, Boolean)`

- `Void ResetRuneAndGlobalBuffAndGlobalBlackboard()`

- `Void _InheritFromMainLevel(LevelData, Boolean)`

- `Void _ReloadRunes()`

- `Void _AppendExtraEnabledEnemyBranch(AutoChessDataCenter)`

- `Void _AppendCultivateRune(BattleChessInst, RuneManager)`

- `Void _AppendEquipRunes(ListDict`2, BattleChessInst, RuneManager)`

- `Void _AppendForceRunes(AutoChessDataCenter, RuneManager)`

- `Void _AppendTalentRunes(AutoChessDataCenter, RuneManager)`

- `Void _ConstructCardAndInstIdRelation(BattlePlayerData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AutoChessGameStateBase : IStateNode
{
	protected const Single MISSION_ACC_PERFORM_TIME; // 0x0

	public Boolean isActiveNode { get; }
	public virtual GameState currentState { get; }
	protected GameStatus status { get; }
	protected AdvancedRuneHolder runeHolder { get; }

	// RVA: 0x1caba84 VA: 0x75942c3a84
	public Boolean get_isActiveNode() { }
	// RVA: 0x1cabb24 VA: 0x75942c3b24
	public virtual GameState get_currentState() { }
	// RVA: 0x1cabb2c VA: 0x75942c3b2c
	protected GameStatus get_status() { }
	// RVA: 0x1cabbcc VA: 0x75942c3bcc
	protected AdvancedRuneHolder get_runeHolder() { }
	// RVA: 0x1cabc2c VA: 0x75942c3c2c
	public virtual Void OnEnter(Int32 lastState) { }
	// RVA: 0x1cabc30 VA: 0x75942c3c30
	public virtual Void OnExit(Int32 nextState) { }
	// RVA: 0x1cabc34 VA: 0x75942c3c34
	public virtual Void OnTick(FP deltaTime) { }
	// RVA: 0x1cabc38 VA: 0x75942c3c38
	public Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x1cabc40 VA: 0x75942c3c40
	public virtual Void OnApplyingGlobalModifier(ref Modifier modifier) { }
	// RVA: 0x1cabc44 VA: 0x75942c3c44
	public virtual Void OnCharacterRespawnFailed(Character character, Card card) { }
	// RVA: 0x1cabc48 VA: 0x75942c3c48
	public virtual Boolean OnDestroyEntity(Entity entity, FinishReason reason) { }
	// RVA: 0x1cabc50 VA: 0x75942c3c50
	public virtual Void OnUnitRegistered(Unit unit) { }
	// RVA: 0x1cabc54 VA: 0x75942c3c54
	public virtual Void OnCardReady(Card card) { }
	// RVA: 0x1cabc58 VA: 0x75942c3c58
	public virtual Void OnCharacterFinished(Character character, FinishReason reason) { }
	// RVA: 0x1cabc5c VA: 0x75942c3c5c
	public virtual Void OnEnemyFinished(Enemy enemy, FinishReason reason) { }
	// RVA: 0x1cabc60 VA: 0x75942c3c60
	protected Void ReloadGame(List`1 insts, LevelData levelData, out List`1 data, Boolean loadRune) { }
	// RVA: 0x1cacc70 VA: 0x75942c4c70
	protected Void ResetRuneAndGlobalBuffAndGlobalBlackboard() { }
	// RVA: 0x1cac5dc VA: 0x75942c45dc
	private Void _InheritFromMainLevel(LevelData levelData, Boolean loadRune) { }
	// RVA: 0x1cac930 VA: 0x75942c4930
	protected Void _ReloadRunes() { }
	// RVA: 0x1cad038 VA: 0x75942c5038
	private Void _AppendExtraEnabledEnemyBranch(AutoChessDataCenter center) { }
	// RVA: 0x1cad46c VA: 0x75942c546c
	private Void _AppendCultivateRune(BattleChessInst inst, RuneManager runeManager) { }
	// RVA: 0x1cad240 VA: 0x75942c5240
	private Void _AppendEquipRunes(ListDict`2 equips, BattleChessInst inst, RuneManager runeManager) { }
	// RVA: 0x1cace0c VA: 0x75942c4e0c
	private Void _AppendForceRunes(AutoChessDataCenter center, RuneManager runeManager) { }
	// RVA: 0x1cacd00 VA: 0x75942c4d00
	private Void _AppendTalentRunes(AutoChessDataCenter center, RuneManager runeManager) { }
	// RVA: 0x1cabf60 VA: 0x75942c3f60
	protected Void _ConstructCardAndInstIdRelation(BattlePlayerData battleCharacterData) { }
	// RVA: 0x1cad540 VA: 0x75942c5540
	public Void .ctor() { }
}
```